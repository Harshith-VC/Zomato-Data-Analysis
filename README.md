
# Zomato Data Analysis Project

## Project Objective

The objective of this project is to perform an in-depth analysis of Zomato restaurant data to uncover patterns in customer behavior, restaurant performance, and market trends. This analysis aims to provide actionable insights that can help Zomato and restaurant owners make data-driven decisions.

## Data Source

The data for this project is sourced from [YouTube-Video-Notes Zomato Python Project](https://github.com/TheiScale/YouTube-Video-Notes/tree/main/Zomato_Python_Project).

## Data Overview

The dataset used in this analysis contains information on various restaurants listed on Zomato. Key variables include:
- **Restaurant Name**: Name of the restaurant.
- **Online Order Availability**: Whether the restaurant accepts online orders (Yes/No).
- **Table Booking**: Whether table booking is available (Yes/No).
- **Rating**: Customer rating for the restaurant.
- **Votes**: Number of votes the restaurant has received.
- **Approximate Cost for Two People**: Estimated cost of dining for two.
- **Listed In (Type)**: Type of restaurant (e.g., Buffet, Café, Dining).

## Analytical Process

### 1. **Data Cleaning and Preprocessing**
   - **Data Import**: Loaded the dataset using Pandas.
   - **Data Cleaning**: Handled missing values, converted data types (e.g., converting ratings from strings to floats), and corrected any inconsistencies in the data.
   - **Feature Engineering**: Created new features where necessary to support the analysis, such as extracting relevant parts of composite data columns.

### 2. **Exploratory Data Analysis (EDA)**
   - **Descriptive Statistics**: Summarized the data to understand its structure and distribution.
   - **Correlation Analysis**: Analyzed relationships between variables to identify key factors influencing customer ratings and votes.
   - **Visualization**: Used bar charts, line graphs, histograms, and heatmaps to visualize patterns in the data.

### 3. **Key Insights and Findings**
   - **Popular Restaurant Types**: Dining restaurants received the highest customer engagement, indicated by the number of votes and ratings.
   - **Customer Spending Behavior**: The most common spending range for two people was around 300 rupees, suggesting that mid-range pricing is attractive to customers.
   - **Impact of Online Orders on Ratings**: Restaurants that offer online ordering tend to have higher ratings, indicating a strong preference among customers for this feature.
   - **Rating Distribution**: Most restaurants fall within the 3.5 to 4.0 rating range, showing general customer satisfaction but also highlighting areas for potential improvement.

### 4. **Conclusion and Recommendations**
   - **Enhance Online Presence**: Restaurants should focus on improving their online ordering systems, as this is positively correlated with higher ratings.
   - **Focus on Mid-Range Pricing**: Given the customer preference for restaurants with approximately 300 rupees for two people, restaurants in this pricing category should be strategically promoted.
   - **Targeted Marketing for Dining**: Since dining restaurants are the most popular, targeted promotions and offers in this segment could drive further customer engagement.

