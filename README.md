# NYC Bike Rental Analysis 🚴

## Project Overview

Welcome to the NYC Bike Rental Analysis, an exploration of Citi Bike data in the vibrant streets of New York City. This project aimed to answer key business questions to better understand the dynamics of bike rentals in the city.

## Business Questions Explored

1. **Urban Exploration Quest:**
   - What are the most popular pick-up locations across the city for NYC Citi Bike rentals?

2. **Time Traveller's Odyssey:**
   - How does the average trip duration vary across different age groups?
   - Which age group rents the most bikes?

3. **Weekly Wheels Conundrum:**
   - How does bike rental vary across the two user groups (one-time users vs long-term subscribers) on different days of the week?

4. **Ageless Adventures:**
   - Does user age impact the average bike trip duration?

## Analysis Methodology

### Data Sources

The analysis was conducted using Citi Bike rental data obtained from [here](https://docs.google.com/spreadsheets/d/1D7y7LfBG-owIkXOiabRfFG0XcEzQS_8Lz5BsnRkVT3E/edit#gid=845159259). The dataset covers between January and March of 2017 and includes information about pick-up locations, trip duration, user demographics, and user type.

### Tools and Technologies

- MS Excel was the primary tool used for analysis.
- MS Excel was employed for exploratory data analysis (EDA) and visualization.

### Exploratory Data Analysis (EDA)

The analysis involved the following steps:

1. **Data Cleaning:**
   - Handling missing values and outliers.
   - Ensuring consistency in data types.

2. **Exploration:**
   - Visualizing pick-up locations across the city.
   - Grouping data by age for understanding trip duration patterns.
   - Comparing bike rental trends between user groups on different days.

## Results and Insights

### 1. Urban Exploration Quest

- The most popular pick-up locations include Grove St Path, Exchange Place, Sip Avenue and Hamilton Park. Here's a bar chart showing the top 20 pick-up stations.
![Top 20 Pickup Stations](https://github.com/igochesam/Citi_Bike_Rental_Analysis/assets/109409835/641b4c04-a336-4073-9fbf-0bd16117070b)

### 2. Time Traveller's Odyssey

- Average trip duration varies significantly across age groups, with Users aged 75 and above showing a significantly higher average trip duration, potentially indicating a different pattern of usage, very likely because this age group seems to have more time on their hands.
![Average Trip Duration for Each Age Group](https://github.com/igochesam/Citi_Bike_Rental_Analysis/assets/109409835/3316ba17-1bac-4ab5-8ea4-49dd6126f025)

### 3. Weekly Wheels Conundrum

- Bike rental patterns differ between one-time users and long-term subscribers across different days of the week. Most NY Citi Bike subscribers are regular, long-term subscribers. However, one-time users are much more likely to rent a Citi Bike during the weekend than they are during the week.
![Bike Rental by User Type](https://github.com/igochesam/Citi_Bike_Rental_Analysis/assets/109409835/0f717a79-42cf-4640-90f1-8c48393f0bd5)

### 4. Ageless Adventures

- Though we have seen that the average trip duration for users over 75 is longer than for other age groups, however, the individual users who took the longest trips were in the 30-55 age range, as the scatter plot below shows:
![chart](https://github.com/igochesam/Citi_Bike_Rental_Analysis/assets/109409835/8dac4b4e-3408-45a2-bbbb-2dfe1ed69a52)

## Conclusion

In conclusion, the NYC Bike Rental Analysis provides valuable insights into the patterns of Citi Bike rentals across different dimensions. The variation in trip duration across age groups and user types highlights the diverse nature of bike usage in the city. The younger age group may have more subscribers by number, but the oldest group have more time on their hands and that's why they embark on longer trips on average.

## Recommendations

Based on the analysis, we propose the following recommendations:

1. **Targeted Promotions:**
   - Focus promotional campaigns in areas identified as popular pick-up locations to attract more users.

2. **User Engagement Strategies:**
   - Develop engagement strategies tailored to age groups with longer trip durations to enhance user experience.

3. **Subscription Model Optimization:**
   - Adjust subscription models based on the weekly rental patterns to maximize long-term subscriber engagement.

4. **Accessibility Improvements:**
   - Explore options to enhance bike accessibility for users aged 75 and above, considering the longer average trip duration.

## Replicating the Analysis

To replicate the analysis, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/Citi_Bike_Rental_Analysis.git
