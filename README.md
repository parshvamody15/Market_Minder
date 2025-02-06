# Market Minder : A Finance Dashboard App
Welcome to Market Minder, a finance dashboard application built with the MERN stack (MongoDB, Express.js, React, and Node.js), integrated with Machine Learning predictions for revenue trends.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
- [Data Pattern](#data-pattern)
- [Demo](#demo)
- [Contributing](#contributing)
- [Contributors and Contact](#contributors-and-contact)
- [Project Status](#project-status)
- [License](#license)

## Introduction

Market Minder is a modern finance dashboard that provides valuable insights into revenue trends using data visualization and machine learning. The platform is designed to help users track financial metrics with ease.

## Features

1. **Machine Learning Predictions:** Implements a simple regression model to predict next year's revenue.
2. **Responsive Design:** Built with Material UI for a modern and user-friendly interface.
3. **Data Visualization:** Uses Recharts to create interactive and insightful charts.
4. **Database Integration:** Utilizes MongoDB for secure and efficient data storage.

## Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js**: [Download Node.js](https://nodejs.org/)
- **MongoDB**: [Download MongoDB](https://www.mongodb.com/try/download/community)
- **Git**: [Download Git](https://git-scm.com/downloads)

## Getting Started

Follow these steps to set up and run the Market Minder application:

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/parshvamody15/Market_Minder.git
   
2. **Navigate to the project directory**:
    ```bash
    cd MarketMinder

3. **Frontend Setup**:
    
    ```bash
    cd client
    npm install

4. **Backend Setup**:
    ```bash
    cd ..
    cd server
    npm install

5. **Enivronment Setup**:

Create a `.env` file in the `server` directory and configure the MongoDB connection URL and server port.

### Running the Application

1. **Run both the client and server** in development mode:
     ```bash
     npm run dev

This will start both the frontend and backend simultaneously, allowing you to view the app on `http://localhost:3000`.

## Usage

- Navigate through the dashboard to view charts and tables visualizing financial data and ML-based predictions.
- Use the menu to switch between different sections such as **Products, Transactions, and Predictions**.
- Interact with charts to analyze financial trends and gain deeper insights.

## Data Pattern

- **Key Performance Indicators (KPIs):** `totalProfit`, `totalRevenue`, `totalExpenses`, `dailyData`, `monthlyData`
- **Transaction Data:** `buyer`, `amount`, `products`
- **Product Data:** `price`, `expense`, `transactions`

## Demo

[![Market Minder Demo](https://github.com/parshvamody15/Market_Minder/demo.mp4)]

Click the link below to watch the demo video of Market Minder:

[Watch Market Minder Demo](https://github.com/parshvamody15/Market_Minder/raw/main/demo.mp4)

## Contributing

We welcome your contributions to [Market Minder](https://github.com/parshvamody15/Market_Minder.git)! Start by forking the repository, cloning it to your local machine, creating a new branch, making your changes, and committing them. Then, push your changes to your fork on GitHub and create a pull request. Your contributions will be reviewed and, once approved, merged into the main project. Thank you for your help!

## Contributors and Contact

A big thank you to the following contributors who have helped improve this project:

- Risa ([@i-risa](https://github.com/i-risa))

Your contributions are greatly appreciated!

Feel free to contact me ([Parshva Mody](mailto:parshva.p.mody@gmail.com)) or any of the contributors for further information or support regarding this project.

## Project Status

This project is **complete**. No further major updates are planned at the moment. If you encounter any issues, feel free to [open an issue](https://github.com/parshvamody15/Market_Minder/issues).

## License

This project is licensed under the [MIT License](LICENSE).
