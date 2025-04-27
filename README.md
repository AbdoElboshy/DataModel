# DataModel Project – Global Super Store Data Warehouse & Analytics

## Project Overview

This project is a comprehensive data modeling and analytics solution for the Global Super Store scenario, developed as part of a peer-graded assignment. It demonstrates the full workflow from ER modeling and normalization in MySQL Workbench, through dimensional modeling (star schema), to interactive analytics and dashboards in Tableau.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Project Tasks & Steps](#project-tasks--steps)
- [Deliverables](#deliverables)
- [How to Review](#how-to-review)
- [License](#license)

## Features

- High-level conceptual data model & logical ER diagram for Global Super Store
- Database normalization up to 3NF
- MySQL Workbench environment setup and schema deployment (Forward Engineer method)
- Creation of virtual summary tables
- Dimensional star schema design for sales analysis
- Data preparation and analytics in Tableau Desktop
- Interactive dashboard with map, bubble, and line charts for sales and profit analysis

## Technologies Used

- **MySQL Workbench** & **MySQL Server** – Data modeling, ER diagrams, schema deployment
- **Tableau Desktop** – Data visualization & dashboard creation

## Setup Instructions

### Prerequisites

- MySQL Workbench with MySQL Server installed
- Tableau Desktop installed

### Getting Started

1. **Clone this repository**  
   ```bash
   git clone https://github.com/AbdoElboshy/DataModel.git
   cd DataModel
   ```
2. **Open the `.mwb` file** in MySQL Workbench for ER diagrams and data model.
3. **Use Forward Engineer** in MySQL Workbench to deploy the schema to your MySQL server.
4. **Open Tableau files** provided in the project to view and interact with the analytics dashboard.

## Project Tasks & Steps

### 1. Design ER Diagram
- Created a physical ER diagram in MySQL Workbench, modeling entities and relationships based on the Global Super Store scenario.
- Ensured all tables conform to the three normal forms.

### 2. Deploy Data Model
- Used the Forward Engineer feature in MySQL Workbench to implement the ER diagram in MySQL Server.

### 3. Create Star Schema
- Designed a dimensional model (star schema) with appropriate fact and dimension tables for sales analysis, focusing on products, locations, and time.

### 4. Data Analysis in Tableau
- Prepared the data and connected Tableau to the MySQL database.
- Created the following charts:
  - **Map Chart**: Visualizes sales across U.S. states.
  - **Bubble Chart**: Displays profits, quantity sold, and shipping costs per state.
  - **Line Chart**: Shows sales trends over four years for states with sales > $40,000.

### 5. Interactive Dashboard
- Built an interactive dashboard in Tableau named “USA Sales and Profits” combining all charts.
- Implemented interactivity: selecting a state filters the bubble and line charts to show relevant data.

## Deliverables

- MySQL Workbench model file (`.mwb`)
- SQL schema/scripts for database deployment
- Example ER and Star Schema diagrams (images or exported PDFs)
- Tableau workbook/dashboard files (`.twb` or `.twbx`)
- Step-by-step documentation with comments and explanations

## How to Review

1. Download and unzip the project folder.
2. Open the data model in MySQL Workbench and deploy using Forward Engineer.
3. Open the Tableau workbook to explore the charts and dashboard.
4. Review the ER diagrams, star schema, and dashboard for completeness, normalization, and interactivity.
5. Compare the results and charts with the assignment brief and grading criteria.

### Feedback Examples

- “The data model contains all required entities and relationships, and conforms to 3NF.”
- “The star schema is robust, but consider adding more dimensions to enrich analysis.”
- “Interactive dashboard works as intended and follows assignment requirements.”

## License

This project is for educational purposes. See the repository for license details.
