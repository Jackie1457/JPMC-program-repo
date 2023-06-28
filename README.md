# JPMC-program-repo

This project aims to enhance a trader's dashboard by adding a chart that allows them to better identify under/over-valued stocks based on historical correlations. The chart will help the trader monitor two historically correlated stocks and visualize when the correlation between them weakens, indicating potential trade opportunities.

### Introduction
Traders often rely on visual representations of stock prices and trading strategies displayed on their screens. This project utilizes JPMorgan Chase's Perspective data visualization software, which provides a powerful toolset for presenting and manipulating financial data feeds visually in web applications.

The goal of this project is to interface with the relevant financial data feed and integrate it with Perspective to create a live graph that tracks the correlation between two stock prices. By monitoring this correlation and identifying instances where one stock moves more than the historical correlation implies, traders can potentially execute profitable trade strategies.

### Prerequisites
Before running the project, ensure that the following prerequisites are met:

Python (version 3.0)

JPMorgan Chase's Perspective library

Financial data feed API

### Installation
Clone the repository: git clone https://github.com/your-username/jpmc-stock-correlation.git

Navigate to the project directory: cd jpmc-stock-correlation

Install the required dependencies: pip install -r requirements.txt

### Usage
Run the Python script to start streaming data from the financial data feed: python stream_data.py

Open the trader's dashboard web application.

The live Perspective graph will automatically update with the stock's top ask price and timestamp, visualizing the correlation between the two stocks.

The graph will display upper and lower bounds based on the 12-month historical average ratio. An alert will be shown whenever the bounds are crossed.

### Features
Continuous live graph updates based on data received from the server application

Aggregation of duplicated data retrieved from the server

Real-time tracking and display of the correlation between two stock prices

Visual representation of upper and lower bounds on the graph

Alerts to notify traders when the bounds are crossed

### Tasks
#### 1. Interface with a stock price data feed [Click here to see Task-1](https://github.com/manikanta222010/JPMorgan-Virtual-Internship/tree/main/JPMC-tech-task-1-py3)
- Interface with a stock price data feed and set your system for analysis of data
- `Financial Data` 
- `Python3`
- `Git`
- `Basic Programming`

#### 2. Use JPMorgan Chase frameworks and tools [Click here to see Task-2](https://github.com/manikanta222010/JPMorgan-Virtual-Internship/tree/main/JPMC-tech-task-2-PY3)
- Implement the perspective open source code in prepration for data visualization 
- `React.js` 
- `TypeScript`
- `Web Applications`

#### 3. Display data visually for traders [Click here to see Task-3](https://github.com/manikanta222010/JPMorgan-Virtual-Internship/tree/main/JPMC-tech-task-3-PY3)
- Use Perspective to create the chart for the trader's dashboard  
- `Technical Communications` 
- `Financial Analysis`
- `Web Applications`
  
#### 4. Bonus task: Open source contribution
- Make a contribution to Perspective or other projects backlogs 
- `Contributing to the Open Source Community`

### Contributing
Contributions to this project are welcome. To contribute, please follow these steps:

Fork the repository

Create a new branch

Make your changes and commit them

Push your changes to your forked repository

Submit a pull request explaining your changes

### Resources
JPMorgan Chase's Perspective data visualization software: [Link to Perspective repository](https://perspective.finos.org/)

Financial data feed API documentation

### License
This project is licensed under the MIT License.
