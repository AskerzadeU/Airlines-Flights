# Airlines Flights Price Analysis

## Project Overview
This project focuses on exploratory data analysis (EDA) of airline flight data
to understand how different factors influence flight duration and ticket prices.
The analysis aims to uncover patterns related to departure time, arrival time,
number of stops, flight class, and source/destination cities.

This project is designed as a portfolio-level data analysis project and
demonstrates practical usage of Python for data exploration and visualization.

---

## Dataset
- Source: Public airline flights dataset
- Format: CSV
- Key features include:
  - airline
  - source_city
  - destination_city
  - departure_time
  - arrival_time
  - stops
  - class
  - duration
  - price

---

## Key Questions
- How does the average ticket price vary by departure and arrival time?
- What is the impact of the number of stops on flight duration and price?
- Are there noticeable price differences between source and destination cities?
- How do Economy and Business class flights compare in terms of price?
- Which airlines tend to have higher average prices?

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Jupyter Notebook

---

## Analysis Highlights
- Flights with fewer stops generally have shorter durations but higher average prices.
- Departure and arrival times play a significant role in ticket pricing.
- Business class flights are consistently more expensive across all routes.
- Certain source cities show higher average ticket prices compared to others.
- Airline choice has a noticeable impact on pricing trends.

---

## Project Structure

Airlines-Flights/
│
├── Airlines Flights.ipynb # Main analysis notebook
├── airlines_flights_data.csv
└── README.md

---

## How to Run the Project
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pandas numpy seaborn matplotlib
Open the notebook:
jupyter notebook Airlines Flights.ipynb
