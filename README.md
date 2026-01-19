# House Rental Portal | Web3 IoT Node Dashboard

A decentralized leasing and monitoring ecosystem for smart architectural nodes. This project demonstrates the integration of Ethereum smart contracts with physical IoT hardware to automate rentals and provide real-time hardware diagnostics.



## 🌟 Key Features
- **MetaMask Identity Protocol**: Secure "Connect Wallet" functionality that validates roles (Guest, Tenant, or Landlord) via blockchain signatures.
- **Smart Contract Automated Leasing**:
    - Atomic booking involving a security deposit and initial rent cycle.
    - Automated fund management handled entirely on-chain.
- **Real-Time IoT Diagnostics**:
    - Live data visualization for DHT11 (Temp/Humidity) and Gas sensors.
    - Dynamic monitoring of the Peltier cooling system, fan states, and voltage supply.
- **Role-Based Portals**:
    - **Tenant Portal**: An emerald-glowing interface for monthly rent broadcasting and status tracking.
    - **Landlord Suite**: Administrative controls for agreement termination and node resets.
- **High-Fidelity UI**: Modern command-center aesthetic using glassmorphism, responsive Tailwind layouts, and interactive SVG state indicators.



## 🛠 Technology Stack
- **Blockchain**: Solidity (Smart Contract), Ethereum Network.
- **Frontend**: HTML5, Tailwind CSS, JavaScript (ES6+).
- **Libraries**:
    - **Ethers.js v5.7**: For seamless blockchain communication and event listening.
    - **FontAwesome 6.4**: For professional diagnostic iconography.
- **Hardware Context**: Integration support for Peltier kits, RFID access, and multi-sensor arrays (DHT11, Gas, IR, Voltage).

## 🚀 Getting Started
1. **Prerequisites**: Install the [MetaMask](https://metamask.io/) browser extension.
2. **Identity Link**: Open `index.html`, click **"Establish Connection"**, and authorize the identity sync via your wallet.
3. **Usage**:
    - **Vacant Node**: Transmit the total payload (Rent + Deposit) to book the unit.
    - **Occupied Node**: Use the Tenant Portal to broadcast the monthly rent cycle.

## 📜 Smart Contract Information
- **Contract Address**: `0xE4DF7316ACDD39cdc75f454162b7Bb6Ad15C05e0`
- **Compiler Version**: Solidity 0.8.x

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.
