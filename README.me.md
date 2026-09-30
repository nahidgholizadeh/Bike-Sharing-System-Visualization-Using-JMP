# Bike Sharing Data Visualization

## 📌 Project Overview
This project focuses on visualizing and analyzing bike-sharing data using **JMP software**. The objective is to uncover patterns and relationships between bike rental demand (from both casual and registered users) and various environmental and temporal factors, such as weather conditions, temperature, seasons, and time of day. 

The analysis aims to provide actionable insights into user behavior and help understand the dynamics of bike-sharing systems, which play a crucial role in promoting sustainable urban transportation.

## 🛠️ Tools & Technologies
- **JMP Software:** Used for data exploration, statistical analysis, and creating insightful visualizations.
- **Data Visualization Techniques:** Scatter plots, line charts, bar charts, and comparative histograms.

## 📂 Dataset
The dataset contains daily and hourly records of a bike-sharing system, including the following key features:
- **Temporal Data:** Year (`yr`), Season (`season`), Month (`mnth`), Hour (`hr`), Day of the week (`weekday`).
- **Environmental Factors:** Weather situation (`weathersit`), Temperature (`temp`), Feeling temperature (`atemp`), Humidity (`hum`), Windspeed (`windspeed`).
- **User Types & Demand (KPIs):** 
  - `casual`: Count of casual (non-registered) users.
  - `registered`: Count of registered users.
  - `cnt`: Total count of rented bikes.

## 📊 Results & Insights
Through comprehensive visualizations, several key behavioral patterns were identified:

1. **Overall Growth:** Bike usage significantly increased in 2012 compared to 2011 for both casual and registered users. Registered users consistently rent far more bikes than casual users overall.
2. **Seasonal & Monthly Trends:** Demand peaks during warmer months (seasons 2 and 3) and drops significantly in winter (season 1).
3. **Weekly Patterns:** 
   - **Registered Users:** Usage peaks on **working days**, aligning with commuting patterns.
   - **Casual Users:** Usage peaks on **weekends and holidays**, indicating recreational use.
4. **Hourly Commuting vs. Leisure:**
   - **Registered Users:** Show distinct spikes at **7-8 AM and 5-6 PM** on weekdays, confirming their use of bikes for commuting to and from work/school.
   - **Casual Users:** Show a gradual increase peaking between **12 PM and 5 PM**, typical of leisure activities.
5. **Weather & Temperature Impact:** 
   - Clear weather (`weathersit = 1`) accounts for the majority of rentals. Bad weather (rain/snow) causes a sharp decline in usage, even on working days.
   - There is a positive correlation between temperature and bike rentals up to a certain point (moderate temperatures). However, extremely high temperatures cause demand to plateau or decrease.
   - Interestingly, registered users show higher tolerance for less ideal temperatures on working days compared to casual users on non-working days.

## 📁 Repository Structure
- `day.csv`: The daily aggregated dataset.
- `hour.csv`: The hourly aggregated dataset.
- `Bike Sharing Data Visualization.pdf`: The complete visualization report containing all generated charts and detailed analysis.

```text
Bike-Sharing-System-Visualization-Using-JMP/
│
├── data/
│   ├── day.xlsx
│   └── hour.xlsx
│
├── JMP/
│   └── day-Visualization.jmp
│
├── Report/
│   └── Bike Sharing Data Visualization.pdf
│
└── README.md
```

## 💻 How to Use
1. Clone this repository.
2. Open the `day.csv` and `hour.csv` files using **JMP** (or any other data analysis tool like Python/R/Excel).
3. Refer to the `Bike Sharing Data Visualization.pdf` report to view the visualizations and detailed analytical findings.