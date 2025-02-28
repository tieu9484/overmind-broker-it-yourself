
# Overmind Broker It Yourself

## Introduction

**Overmind Broker It Yourself** is a peer-to-peer (P2P) marketplace built on the Aptos blockchain. This project enables users to trade digital assets in a decentralized manner, ensuring security, transparency, and efficiency without relying on intermediaries.

## Features

-   **Decentralized Trading**: Users can securely exchange assets without the need for a central authority.
    
-   **Smart Contracts**: Ensures trustless transactions through Aptos Move smart contracts.
    
-   **Fast and Scalable**: Built on Aptos for high performance and low transaction fees.
    
-   **Non-Custodial**: Users maintain full control over their assets.
    
-   **User-Friendly Interface**: Simple and intuitive UI for seamless trading.
    

## Technology Stack

-   **Blockchain**: Aptos
    
-   **Smart Contracts**: Move
    
-   **Backend**: Rust, TypeScript
    
-   **Frontend**: React, Next.js
    
-   **Database**: PostgreSQL (if applicable)
    

## Installation

1.  Clone the repository:
    
    ```
    git clone https://github.com/tieu9484/overmind-broker-it-yourself.git
    cd overmind-broker-it-yourself
    ```
    
2.  Install dependencies:
    
    ```
    npm install  # For frontend
    cargo build  # For backend
    ```
    
3.  Deploy smart contracts to Aptos:
    
    ```
    aptos move publish --profile default
    ```
    
4.  Run the application:
    
    ```
    npm run dev  # Start frontend
    cargo run  # Start backend
    ```
    

## Usage

-   Connect your Aptos wallet.
    
-   List items for sale or browse available listings.
    
-   Initiate and confirm transactions through smart contracts.
    
-   Complete secure P2P trades with transparency.
    

## Contributing

Contributions are welcome! Please submit a pull request or open an issue if you encounter any problems.
