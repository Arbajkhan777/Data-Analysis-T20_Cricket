# T20 World Cup 2022 Data Analysis - Power BI Dashboard

This repository contains a comprehensive analysis of the **2022 T20 World Cup** data, visualized using Power BI. The data includes detailed summaries of batting, bowling, match outcomes, and player statistics, scraped from ESPNcricinfo.

## 🔥 Features

- **Batting and Bowling Summaries**: In-depth analysis of player and team performance during the 2022 T20 World Cup.
- **Match Summaries**: Overview of match results, team performance.
- **Player Insights**: Detailed player statistics with interactive filters.
- **Team Selection Tool**: An interactive feature to select the optimal playing XI based on specific parameters for openers, anchors, finishers, and pacers.
- **Comprehensive Preprocessing**: Jupyter Notebook used for cleaning and processing data before loading into Power BI.

[Click here to view the live dashboard](https://app.powerbi.com/groups/me/reports/24d63e7e-3b12-4feb-8487-1a08b6e1478e/ReportSection3a8cb23b814911c94608?experience=power-bi)

## 📊 Dashboard Preview

![image](https://github.com/user-attachments/assets/a3f9e94a-76f9-48a7-916c-6355f0e9e538)

## 📁 Data Overview

The data used in this project is scraped from the ESPNcricinfo website and is organized into the following folders:

- **CSV**:
  - `Batting_summery.csv`
  - `Bowling_summery.csv`
  - `Match_summery.csv`
  - `Players.csv`
  
- **JSON**:
  - `Batting_summery.json`
  - `Bowling_summery.json`
  - `Match_summery.json`
  - `Players.json`

## 🛠️ Tools and Technologies

- **Power BI**: To visualize the data in an interactive and user-friendly format.
- **Python (Jupyter Notebook)**: Used for data preprocessing and cleaning.
- **Data Source**: Scraped from ESPNcricinfo.

## 📄 Project Structure

- `T20_Cricket.pbix`: The Power BI dashboard file.
- `data/`: Contains the raw data in both CSV and JSON formats.
  - `CSV/`: CSV files for batting, bowling, match summaries, and players.
  - `JSON/`: JSON files for the same categories.
- `preprocessing.ipynb`: Jupyter Notebook for data preprocessing and cleaning.

## 📊 Data Processing

The `preprocessing.ipynb` notebook performs the following steps:

- Data cleaning and formatting.
- Handling missing values and inconsistent data.
- Exporting the cleaned data into formats ready for Power BI visualization.

## 🏏 Team Selection Feature

An interactive team selection tool is included in the dashboard to help choose the optimal playing XI based on specific performance criteria:

### **Player Roles and Selection Criteria**

- **Openers**:
  - **Batting Average**: Greater than 30
  - **Strike Rate**: Greater than 140
  - **Boundary Percentage**: More than 50% of runs scored in boundaries

- **Anchors**:
  - **Batting Average**: Greater than > 40 
  - **Strike Rate**: Greater than > 125
  - **AVG Ball Faced**: Greater than > 20

- **Finishers**:
  - **Strike Rate**: Greater than 130
  - **Batting Average**: Greater than > 25 
  - **Batting Position**: Greater than > 4

- **Pacers**:
  - **Bowling Average**: Less than 20
  - **Economy Rate**: Less than 7 runs per over
  - **Dot Ball %**: Greater than > 40

## 📬 Contact

For any questions or suggestions, feel free to reach out at your-arbajkhan2117@gmail.com
