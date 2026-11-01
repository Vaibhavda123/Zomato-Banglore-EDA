# Zomato Bangalore Restaurants - EDA

## Business Problem
Where, and with what concept, should a new restaurant open in Bangalore? This project analyses Zomato listings to find the best location, restaurant type, cuisine and price range.

## Dataset
Zomato Bangalore Restaurants (Kaggle): https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants

About 51,700 listings, reduced to about 12,000 unique restaurants after cleaning (about 9,000 with ratings).
The CSV is not included here because of its size. Please download it from Kaggle.

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn (Jupyter Notebook)

## Data Cleaning
- Removed unused columns and duplicate rows
- Converted `rate` ("4.1/5") to a number; "NEW" and "-" treated as missing
- Removed commas from `cost` and converted it to a number
- Kept one row per restaurant (name + location) for restaurant-level analysis

## Questions Answered
1. Which locations have the most restaurants?
2. Do restaurants with online ordering get better ratings?
3. Do restaurants offering table booking get better ratings?
4. Which restaurant types are the most common and best rated?
5. What are the most popular cuisines?
6. Does a higher cost mean a better rating?
7. Which price range has the most restaurants?
8. How are votes related to rating?
9. Which locations have the highest-rated restaurants?
10. Where is the best opportunity to open a new restaurant?

## Key Insights
- Table booking marks the premium segment: rating 4.12 vs 3.57, and cost for two about Rs. 1,301 vs Rs. 420.
- Online ordering is only mildly linked to better ratings (3.65 vs 3.59).
- About three quarters of restaurants charge under Rs. 600 for two. Ratings rise with price (about 3.55 under Rs. 300 to about 4.1 above Rs. 1,000).
- Quick Bites is the most common type but rates below Casual Dining, Cafe and Dessert Parlor.
- Lavelle Road, St. Marks Road and Church Street combine high ratings with below-median competition.

## Recommendation
Open a premium sit-down concept (Casual Dining, Cafe or Dessert) with table booking and online ordering, priced above Rs. 1,000 for two, in a high-rating, low-competition location such as Lavelle Road, St. Marks Road or Church Street.

## Limitations
- Snapshot of listings: no sales, revenue, rent or footfall data
- About a quarter of restaurants are unrated and excluded from rating analysis
- Few restaurants in an area may also mean low demand
- Findings show correlation, not causation

## Author
Vaibhav Gupta | LinkedIn: linkedin.com/in/vaibhav-gupta-2b7528161 | GitHub: github.com/Vaibhavda123
