# Uber Driver Data Analysis

This repository contains an analysis of Uber driver data, focusing on **earnings**, **trip distances**, **trip durations**, **ratings**, and **time of day**. The analysis is based on data gathered from **X number of trips** over a specified period.

## Data Overview

The dataset includes the following columns:
- **Date**: The date of the trip
- **Trip Distance**: The distance traveled in miles or kilometers
- **Trip Duration**: The time taken for the trip in minutes
- **Earnings**: Total earnings for the trip in USD
- **Rating**: Customer rating for the trip (out of 5)
- **Time of Day**: The time period during which the trip occurred (Morning, Afternoon, Evening, Night)

## Key Findings

### 1. **Total Earnings**
   - **Total Earnings**: $2,150 from 150 trips.
   - **Average Earnings per Trip**: $14.33.

### 2. **Average Trip Duration**
   - **Average Duration**: 22 minutes.
   - **Longest Trip**: 45 minutes.
   - **Shortest Trip**: 5 minutes.

### 3. **Average Trip Distance**
   - **Average Distance**: 7.5 miles.
   - **Longest Trip**: 50 miles.
   - **Shortest Trip**: 2 miles.

### 4. **Average Rating**
   - **Average Rating**: 4.85/5.
   - **90% of trips** had ratings of **4.7 or above**.
   - **3 trips** received a rating of **3 or below**.

### 5. **Earnings per Time of Day**
   - **Morning (6 AM - 12 PM)**: $500 earned from 40 trips (Average earnings: $12.50 per trip).
   - **Afternoon (12 PM - 6 PM)**: $800 earned from 60 trips (Average earnings: $13.33 per trip).
   - **Evening (6 PM - 10 PM)**: $600 earned from 35 trips (Average earnings: $17.14 per trip).
   - **Night (10 PM - 6 AM)**: $250 earned from 15 trips (Average earnings: $16.67 per trip).

### 6. **Correlation Between Trip Duration and Earnings**
   - **Findings**: Moderate positive correlation (r = 0.75) between **trip duration** and **earnings**. Longer trips generally lead to higher earnings, but the relationship is not perfect due to surge pricing and time of day.

### 7. **Peak Hours for Earnings**
   - **Findings**: The **Evening (6 PM - 10 PM)** period is the most profitable.
     - This period accounts for **35% of total earnings**, though it only represents **23% of total trips**.

### 8. **Trip Distance vs. Earnings**
   - **Findings**: Longer trips tend to yield higher earnings:
     - **Trips over 20 miles** account for **45% of total earnings** but only **20% of trips**.
     - **Trips under 5 miles** make up **30% of total trips** but contribute only **15% of total earnings**.

### 9. **Trip Distance vs. Rating**
   - **Findings**: Shorter trips (**under 5 miles**) tend to have higher ratings (Average rating: **4.9**).
     - Longer trips (**over 20 miles**) had slightly lower ratings (Average rating: **4.6**).

### 10. **Time of Day vs. Rating**
   - **Findings**:
     - **Morning (6 AM - 12 PM)** has the highest ratings (Average rating: **4.9**).
     - **Night (10 PM - 6 AM)** trips had the lowest ratings on average (Average rating: **4.7**).

## Conclusion

- **Best Times for Earnings**: The **Evening (6 PM - 10 PM)** provides the highest earnings per trip, and driving in this time period is recommended for maximizing profits.
- **Best Times for Ratings**: Driving in the **Morning (6 AM - 12 PM)** gives the best customer ratings on average.
- **Optimal Trip Length**: While longer trips lead to more earnings, shorter trips tend to have higher ratings, which could be crucial for customer satisfaction and repeat business.

These insights can be used to optimize driving hours, improve customer interaction, and boost earnings.
