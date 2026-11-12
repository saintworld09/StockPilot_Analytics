# StockPilot – Retail Sales and Inventory Management System

StockPilot is a multi-branch retail sales and inventory management application designed to help retail businesses manage their products, stock levels, sales transactions, purchases, customers, and branch performance from one centralized platform.

The project is being developed using **Google Sheets and Google Apps Script**, with the goal of providing a simple, accessible, and practical business management solution.

## Project Objectives

- Manage products and product categories.
- Track inventory levels across multiple branches.
- Record and monitor daily sales transactions.
- Manage purchases and suppliers.
- Maintain customer records.
- Monitor branch and sales representative performance.
- Provide business dashboards and operational insights.
- Apply role-based access to business records.

## Business Overview

StockPilot uses a fictional retail business called **PrimeMart**, operating across three branches:

- Ikeja Branch
- Lekki Branch
- Ibadan Branch

The application is designed around three user roles:

| Role | Responsibilities |
|---|---|
| Business Owner | Access business-wide records, dashboards, reports, users, and all branches. |
| Branch Manager | Manage and monitor sales and inventory within an assigned branch. |
| Sales Rep | Record sales, check product availability, and view personal sales history. |

## Technology Stack

| Technology | Purpose |
|---|---|
| Google Sheets | Centralized data storage |
| Google Apps Script | Application logic and backend operations |
| HTML | Application page structure |
| CSS | User interface styling |
| JavaScript | Frontend interactions and application functionality |
| Git & GitHub | Version control and project documentation |

## Project Structure

```text
StockPilot_Analytics/
│
├── README.md
│
├── apps-script/
│
├── documentation/
│
├── database/
│   └── StockPilot_Starter_Dataset_Large.xlsx
│
├── assets/
│
└── testing/
```

## Database Overview

The starter dataset contains 12 worksheets:

| Worksheet | Description |
|---|---|
| Branches | Business branch information |
| Users | Application users and their roles |
| Categories | Product categories |
| Products | Product details and pricing |
| Suppliers | Supplier information |
| Customers | Registered and walk-in customers |
| Opening_Stock | Initial stock quantities by branch |
| Sales | Sales transaction records |
| Sales_Details | Individual products recorded in each sale |
| Purchases | Purchase transaction records |
| Purchase_Details | Individual products included in each purchase |
| README | Dataset documentation and data dictionary |

The workbook includes more than 1,500 sales transactions and several thousand transaction-detail records.

## Development Roadmap

- [x] Create GitHub repository.
- [x] Configure local Git environment.
- [x] Create initial project folder structure.
- [x] Prepare the starter dataset.
- [ ] Complete database validation and Google Sheets setup.
- [ ] Design the application structure.
- [ ] Develop user authentication and role-based access.
- [ ] Build the business dashboard.
- [ ] Develop product and inventory management.
- [ ] Develop sales and purchase management.
- [ ] Build business reports and insights.
- [ ] Test application functionality and data accuracy.
- [ ] Complete project documentation and deployment.

## Project Status

**Currently in development.**

StockPilot is a portfolio project focused on demonstrating practical business analysis, database design, application development, data management, and business reporting.

## Author

**Adekola Babatunde**

GitHub: [Your GitHub Profile](https://github.com/)

