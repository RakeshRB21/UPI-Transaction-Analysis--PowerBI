![Screenshot 2024-11-09 005644](https://github.com/user-attachments/assets/554d50b9-8c73-4abf-a200-427c00bf7f81)# UPI Transaction Analysis

This project analyzes UPI (Unified Payments Interface) transaction data to gain insights into transaction trends over time. Visualizations were created in Power BI to provide an interactive and informative overview of transaction behaviors across various dimensions, including month, bank names, gender, payment method, and more.

## Project Overview

The UPI Transaction Analysis project aims to visualize UPI transaction patterns across different categories and demographic factors. The Power BI dashboard includes filters and interactive charts that allow users to explore transaction amounts and balances by various attributes, such as gender, bank name, and merchant type.

## Data Source

The dataset for this analysis is sourced from a CSV file containing UPI transaction data. It includes fields such as:
- `BankNameSent`: The bank initiating the transaction.
- `BankNameReceived`: The bank receiving the transaction.
- `City`: The city in which the transaction occurred.
- `AgeGroup`: Age group of the user.
- `DeviceType`: The type of device used.
- `Gender`: Gender of the user.
- `MerchantName`: The merchant involved in the transaction.
- `PaymentMethod`: The payment method used.
- `TransactionType`: Type of transaction (e.g., payment, transfer).
- `Purpose`: The purpose of the transaction.
- `TransactionAmount`: The amount transacted.
- `Balance`: Remaining balance after the transaction.
  
##Dashboard Images

![Screenshot 2024-11-09 005634](https://github.com/user-attachments/assets/bf4009c2-dc28-4aa1-b7a9-6c55b43140d0)
![Screenshot 2024-11-09 005654](https://github.com/user-attachments/assets/5a34b4f9-b51a-4a06-bdf0-c9c9bbba9fa2)
![Screenshot 2024-11-09 005858](https://github.com/user-attachments/assets/da04fe64-f1ac-41e3-9f74-7340eb6442c6)
![Screenshot 2024-11-09 005944](https://github.com/user-attachments/assets/7543376e-a1ed-4e85-8875-9d1a9e1eefd6)

## Dashboard Overview

The Power BI dashboard includes the following visualizations:

1. **Monthly Transaction Trends**: A line chart showing monthly transaction amounts over the year.
2. **Transaction Amount by Category**: Multiple filter options, such as BankNameSent, BankNameReceived, City, AgeGroup, DeviceType, and more, allow users to drill down into the data and analyze transaction behavior across categories.
3. **Column and Line Charts**: Comparison of transaction amounts and balances across various dimensions.

## Features

- **Interactive Filters**: Users can filter data by Bank Name, Gender, Age Group, Merchant Name, etc., for focused analysis.
- **Dynamic Visualizations**: The charts update dynamically based on selected filters, providing insights into transaction trends.
- **Month-by-Month Analysis**: Visualizes how transaction amounts vary across each month.

## Getting Started

1. **Data Preparation**:
   - Ensure the CSV file is available and formatted correctly.
   - Load the CSV data into Power BI.

2. **Data Import**:
   - Import the CSV data into Power BI by using the “Get data” option.

3. **Creating Visuals**:
   - Create visuals such as line charts, column charts, and slicers for filtering data by different dimensions.

4. **Configuring Filters**:
   - Use slicers to enable filtering by Bank Name, Gender, City, Age Group, and other dimensions.

## Usage

1. Open the Power BI dashboard.
2. Use the slicers on the right to filter data by various categories.
3. Observe the interactive changes in the visualizations to gain insights.

