# British Airways 

## Objective
The goal of this analysis is to explore and visualize customer reviews of airline services and understand how they vary across different countries. Using Tableau, key insights such as average overall ratings, cabin staff service quality, and other metrics are extracted to aid decision-making.

## File Information

### 1. Reviews Dataset

**File Name**: `Reviews`

**Column Descriptions:**
- **Header**: Title or summary of the review.
- **Author**: Name of the reviewer.
- **Date**: Date when the review was posted.
- **Place**: Location of the reviewer.
- **Content**: Detailed review text.
- **Aircraft**: Type of aircraft used.
- **Traveller_Type**: Type of traveler (e.g., solo, family, business).
- **Seat_Type**: Class of the seat (e.g., economy, business).
- **Route**: Route traveled.
- **Date_Flown**: Actual date of the flight.
- **Recommended**: Whether the reviewer recommends the airline (Yes/No).
- **Trip_Verified**: Indicates if the trip was verified (Yes/No).
- **Rating**: Overall rating given by the reviewer (numeric).
- **Seat_Comfort**: Rating of seat comfort.
- **Cabin_Staff_Service**: Rating of cabin staff service.
- **Food_Beverages**: Rating of food and beverages provided.
- **Ground_Service**: Rating of ground services.
- **Value_of_Money**: Rating of the value for money.
- **Entertainment**: Rating of in-flight entertainment.

### 2. Countries Dataset
**File Name**: `Countries`

**Column Descriptions:**
- **Country**: Name of the country.
- **Code**: Country code.
- **Continent**: Continent to which the country belongs.
- **Region**: Region within the continent.


## Technical Insights
1. **Primary Tools**: Tableau was used to visualize and analyze the datasets.
2. **Charts/Visualizations**:
   - Average Overall Rating by Country.
   - Average Cabin Staff Service by Country.
   - Ratings Distribution across Traveller Type and Seat Type.
   - Comparison of Recommended vs Non-Recommended flights.
3. **Data Preparation**:
   - Merged datasets using `Country` column for additional geographic insights.
   - Ensured data cleanliness by handling missing values and verifying column consistency.

---

## Fundamental Data Insights
- **Overall Rating**: Averages calculated by country to highlight regional service differences.
- **Cabin Staff Service**: Identified as a critical factor influencing overall ratings.
- **Seat Comfort and Entertainment**: Evaluated based on traveler type and seat type.
- **Recommendation Trends**: Strong correlation between high ratings and recommendations.

---

## Conclusion
The analysis of the Reviews and Countries datasets provides valuable insights into airline service quality across different regions. Key factors influencing customer satisfaction include cabin staff service, seat comfort, and value for money. These insights can help airlines target specific areas for improvement and enhance customer experiences globally.


