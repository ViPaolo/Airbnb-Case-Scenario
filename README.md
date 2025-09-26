# Airbnb-Case-Scenario: Data Visualization Project

This repository showcases a data visualization business case developed as a project for a Big Data Analytics class. It focuses on analyzing Airbnb data to derive insights through a data-driven approach.

## Project Overview

The core of this project involves an in-depth analysis of Airbnb listing data. The process includes:
*   **Data Sourcing**: Utilizing various CSV datasets.
*   **Data Preparation**: Applying specific assumptions and performing data manipulations, which are detailed comprehensively in the `.pdf` documentation within this repository.
*   **Visualization**: Developing a Tableau workflow and interactive dashboards to present key findings.

## Tableau Deliverables

The project culminates in a complete Tableau flow and two distinct dashboards designed to explore the Airbnb dataset.

### Tableau Flow
This image displays the overall data preparation and transformation flow in Tableau Prep.
![Tableau Prep Flow](./flow%20airbnb.png)

### Interactive Dashboards
Two primary dashboards are provided for interactive data exploration:

#### 1. Aggregated Dashboard
This dashboard offers a high-level overview, presenting data based on aggregated metrics for houses within specific towns, primarily focusing on average prices and other key summary statistics.
![Aggregated Dashboard](./Aggregated%20Dashboard.png)

#### 2. Explorative (Non-Aggregated) Dashboard
Designed for granular insights, this dashboard allows users to examine individual houses, their specific pricing, features, and other detailed attributes, facilitating a deeper, non-aggregated exploration of the data.
![Explorative Dashboard - Individual Houses](./Explorative%20Dashboard%20-%20Individual%20Houses.png)

## Getting Started

To interact with the Tableau workbooks and replicate the analysis:

**Note on Compatibility**: This project was last tested with **Tableau Desktop 2024.1** and **Tableau Prep 2023.2**. Using different versions may require minor adjustments.

### Instructions:

1.  **Download the Repository**: Clone or download a copy of this repository to your local machine.
2.  **Update Data Source Paths**: Inside both the Tableau Prep flow (`.tfl`) and Tableau Desktop workbook (`.twb`/`.twbx`) files, you will need to modify the data source links to point to the CSV files on your local system. Ensure the paths correctly reference the original data files downloaded with this repository.

---
