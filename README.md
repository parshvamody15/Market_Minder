# MarketMinder

This project is a finance dashboard application utilizing the MERN stack (MongoDB, Express.js, React, and Node.js), integrated with Machine Learning predictions for revenue trends. 

## Features

- **Machine Learning Predictions**: Simple regression line fit to data to predict next year's revenue
- **Responsive Design**: Crafted with Material UI for a modern interface.
- **Data Visualization**: Implemented with Recharts for insightful charts.
- **Database Integration**: Utilizes MongoDB for data storage.

## Installation

1. **Clone and Navigate to the directory**

2. **Frontend Setup**

    ```sh
    cd client
    npm install
    ```

3. **Backend Setup**

    ```sh
    cd ..
    cd server
    npm install
    ```

4. **Configure Environment**

    Set up `.env` files in server directory (add mongoDB URL and port)

5. **Run the Application**

    - **Both client and server**: `npm run dev`

## Usage

- Navigate through the dashboard to view charts and tables visualising data and ML-based predictions.
- Use the menu to switch between different sections like Products, Transactions, and Predictions.
- Interact with charts for deeper financial insights.

## Data Pattern
- Key Performance Indicators: totalProfit, totalRevenue, totalExpenses, dailyData, monthlyData
- Transaction: buyer, amount, products
- Product: price, expense, transactions

## Demo


https://github.com/i-risa/MarketMinder/assets/90930340/c8d8928a-ec06-4a8e-ae8e-a76fb5d62ad7



