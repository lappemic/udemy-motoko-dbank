# Motoko Familiarization Project - DBank

## Project Overview

This project, titled "DBank," is a basic banking application built to familiarize myself with Motoko and the Internet Computer. Motoko is a programming language designed specifically for the Internet Computer, a blockchain-based platform that aims to expand the functionality of the internet. The application allows users to top up, withdraw, and view their balance, implementing simple interest compounding over time.

![DBank](./src/dbank_assets/assets/dbank_logo.png)

## Key Features

- **Top Up**: Deposit funds into your account.
- **Withdraw**: Withdraw funds from your account.
- **Balance Check**: View your current account balance.
- **Interest Compounding**: Automatically applies a simple interest rate over time.

## Technology Stack

- **Motoko**: The backend logic is written in Motoko.
- **Internet Computer**: Utilizes the Internet Computer for decentralized computing.
- **HTML/CSS/JS**: Frontend implementation.

## Installation and Running

To run this project, follow these steps:

1. **Start the DFINITY Canister SDK:**

   ```bash
   dfx start --clean
   ```

2. **Deploy the Project:**

   ```bash
   dfx deploy
   ```

3. **View the Application:**

   Open `index.html` in a web browser to interact with the application.

## Internet Computer (IC)

The Internet Computer represents a paradigm shift in blockchain technology, aiming to extend the capabilities of the internet. It provides a scalable and efficient platform for smart contracts and decentralized applications (dApps). The IC is designed to host software and data in a secure and tamper-proof environment, offering a revolutionary approach to building and hosting applications.

## Future Enhancements

- **User Authentication**: Implement secure login for individual user accounts.
- **Transaction History**: Keep track of all user transactions.
- **UI/UX Improvements**: Enhance the frontend design for a better user experience.
- **Advanced Financial Features**: Introduce more complex banking operations like loans or multiple account types.

## Repository Structure

- **index.html**: The main HTML file for the frontend.
- **index.js**: JavaScript file handling frontend logic.
- **main.mo**: The Motoko file containing the backend logic.
- **styles.css**: CSS file for styling the frontend.

## Additional Resources

- [Internet Computer Documentation](https://sdk.dfinity.org/docs/index.html)
- [Motoko Language Guide](https://sdk.dfinity.org/docs/language-guide/motoko.html)
- [DFINITY Foundation](https://dfinity.org/)
