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
There are multiple questions given that we answered with Python :
Q.1 What are the airlines in the dataset, accompanied by their frequencies?
Q.2. Show Bar Graphs representing the Departure Time & Arrival Time.
Q.3. Show Bar Graphs representing the Source City & Destination City.
Q.4. Does price varies with airlines ?
Q.5. Does ticket price change based on the departure time and arrival time?
Q.6. How the price changes with change in Source and Destination?
Q.7. How is the price affected when tickets are bought in just 1 or 2 days before departure?
Q.8. How does the ticket price vary between Economy and Business class?
Q.9. What will be the Average Price of Vistara airline for a flight from Delhi to Hyderabad in Business Class ?


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
