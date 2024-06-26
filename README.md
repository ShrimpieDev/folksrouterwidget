# Folks Swap Widget

## Overview

Welcome to the Folks Swap Widget! I'm thrilled to introduce this powerful and flexible tool, designed for seamless asset swapping on the Algorand blockchain. Our widget is packed with features to enhance your user experience, streamline transactions, and provide a visually appealing interface for both web and mobile applications.

Link to the slides -> https://docs.google.com/presentation/d/1fFAy0ZcY9Hovi51mFc8BFprUJU6fCgRJPtRhUrY4JKE/edit?usp=sharing

![image](https://github.com/kamalbuilds/folksrouterwidget/assets/95926324/6bb39d17-1633-4207-9f85-e2aa821eb37d)

## Development and Technologies

### Monorepo Structure

Organized for flexibility and scalability:

- **/apps/swap-widget-website:** Web application deployment.
- **/packages/swap-widget-react:** React component for easy integration.
- **/packages/swap-widget-js:** Communication library for diverse technology stacks.

This approach ensures a scalable and maintainable solution for our project.

## Core Features with their Description

| **Feature**                   | **Description**                                                                                                                                                                                                                                                                                                             |
|-------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Wallet Connectivity**       | Easily connect your wallet using [TxnLab's use-wallet](https://github.com/TxnLab/use-wallet/tree/main). The widget supports direct wallet integration or, if your protocol has its own infrastructure, facilitates the exchange of unsigned transactions.                                                                             |
| **API Utilization**           | Harness the power of Folks Router's APIs for fetching swap quotations and related transactions.                                                                                                                                                                                                                              |
| **Themes**                    | Choose between light and dark themes, with easy customization options for you.                                                                                                                                                                                                                                               |
| **Swap Modes**                | Dynamic swap modes allow you to execute "fixed input" or "fixed output" swaps based on the last manually entered value.                                                                                                                                                                                                    |
| **API Request Debouncing**    | Debounce API calls when you manually input values for a smoother experience.                                                                                                                                                                                                                                                 |
| **Automatic Quotation Updates** | Stay informed with automatic quotation updates at regular intervals, complete with a countdown or indicator for transparency.                                                                                                                                                                                               |
| **Asset Selection**           | Select from a preset list of assets or manually input an asset ID. Display asset information, including name, icon, and wallet amount.                                                                                                                                                                                      |
| **Simulate Swap**             | Even without a connected wallet, you can enter arbitrary amounts for simulation, with a clear indication of the reason for any disabled swap button.                                                                                                                                                                       |
| **Invert Selected Assets**    | Swap the two selected assets effortlessly with a single click.                                                                                                                                                                                                                                                              |
| **Dollar Prices**             | View dollar values based on the amounts used, with multi-currency support.                                                                                                                                                                                                                                                  |
| **Swap Routes**               | Visualize swap routes with an intuitive accordion interface.                                                                                                                                                                                                                                                               |
| **Handle Opt-in**             | Efficiently handle opt-in transactions if required by your connected wallet.                                                                                                                                                                                                                                               |
| **Gas Fee Management**        | We'll warn you if you lack sufficient funds to cover gas fees, preventing failed transactions.                                                                                                                                                                                                                               |
| **Compatibility**             | Our widget seamlessly integrates with both web and mobile contexts and is not restricted to React applications.                                                                                                                                                                                                              |


## About Folks Finance

We are Folks Finance, a leading DeFi platform, revolutionizing lending, borrowing, trading, and asset management on the Algorand Blockchain. Our user-centric approach combines DeFi innovation with a competitive UI/UX, all powered by permissionless smart contract technology. Join us in shaping the future of decentralized finance!
