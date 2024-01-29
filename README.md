# Crypto Tracker App

A simple React application for tracking cryptocurrency information using the CoinGecko API.

## Table of Contents

- [Description](#description)
- [Files](#files)
- [Installation](#installation)
- [Usage](#usage)
## Description

This project is a React-based cryptocurrency tracker that fetches data from the CoinGecko API and displays it in a visually appealing manner. It includes components for listing top cryptocurrencies, a search functionality, and individual coin details.

## Files

### 1. App.js

This file contains the main React component (`App`) responsible for fetching and displaying cryptocurrency data using the CoinGecko API.

### 2. App.css

The stylesheet for styling the components in `App.js`. It includes styles for the overall layout, search bar, and individual coin information.

### 3. Coin.js

The `Coin` component renders individual cryptocurrency information. It takes props such as `name`, `price`, `symbol`, `marketcap`, `volume`, `image`, and `priceChange`.

### 4. Coin.css

The stylesheet for styling the `Coin` component, providing styles for coin containers, rows, images, text, and conditional styling for price changes.

### 5. index.js

The entry point of the React application, rendering the `App` component into the HTML element with the id of 'root'.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ROHIT9783/CRYPTO-PRICE-TRACKER.git


   
2. Install dependencies: npm install

 
3. Run the application: npm start

 
## Usage 
1.Run the application locally after installation.
2.Enter search queries to find specific cryptocurrencies.
3.Explore individual coin details such as price, volume, market cap, and price change.


 



