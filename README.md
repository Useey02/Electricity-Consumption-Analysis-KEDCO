# Electricity-Consumption-Analysis-KEDCO
Analysis of electricity consumption trends and infrastructural efficiencies in Kano and Katsina States using KEDCO data.

# Electricity Consumption Analysis in Kano and Katsina States

## Project Overview
This study uses the Kano Electricity Distribution Company (KEDCO) dataset to analyze electricity consumption trends and patterns across Kano and Katsina states. The primary goal is to identify key factors influencing consumption and revenue, and to pinpoint infrastructural inefficiencies, ultimately aiming to improve grid efficiency and service delivery.

## Problem Statement
Despite increasing demand due to rapid urbanization, inefficient electricity distribution and energy losses pose significant challenges in Kano and Katsina states. This project addresses these issues by providing a data-driven analysis to understand consumption behaviors, sectoral performance, and infrastructure bottlenecks.

## Aims and Objectives
The main objectives of this study are:
1.  To analyze electricity consumption trends and patterns across Kano and Katsina using the Energy Mix Model.
2.  To identify the sectors (residential, commercial, and industrial) that consume the most electricity and generate the highest revenue.
3.  To examine the relationship between electricity prices, consumptions, and revenue generation using the Three-Dimensional Energy Profile framework.
4.  To identify key infrastructural inefficiencies, such as underperforming feeders, transformers, and potential energy transmission losses, contributing to energy losses using the Super Efficiency Model.

## Key Findings
Based on the analysis, the following key findings were identified:
* **Dominant Sectors:** The **Private Account**, **Commercial Account**, and **Private Residential** sectors were the largest contributors in both consumption and revenue.
* **Consumption-Revenue Relationship:** A general positive correlation was observed between ConsumptionKWH and CurrentChgTotal (revenue), though this relationship varied by sector.
* **Price-Consumption Relationship:** The average price per KWH varied significantly depending on the sector and consumption level.
* **Infrastructural Inefficiencies:** Feeders and transformers with notably low consumption, such as 'Dangote' and 'Ajiwa Water Works' feeders, and 'Bashir Tofa' and 'Kusa Village' transformers, were identified as potentially underperforming assets.
* **Data Limitation on Losses:** A direct 'Loss_Percentage' column was not available, requiring a qualitative approach to identify potential inefficiencies by comparing consumption and revenue against average prices per KWH for individual assets.

## Technologies and Libraries Used
* **Programming Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn, Plotly
* **Business Intelligence:** Power BI (for external dashboarding if applicable)
* **Development Environment:** Google Colab (for initial data loading and processing with chunking)

## Data Source
The analysis was conducted using a comprehensive dataset from the Kano Electricity Distribution Company (KEDCO) covering a two-year period (2021-2022).
The dataset used for this analysis was provided by the Kano Electricity Distribution Company (KEDCO), covering a two-year period (2021-2022). Due to its size and proprietary nature, it is not included in this repository. Please contact [relevant party/KEDCO] for data access if required.

## Project Structure
