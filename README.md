
# Hotel Revenue & Occupancy Insights

A **Hotel Revenue and Occupancy Analysis Project built using Python**, analyzing booking and revenue data from **AtliQ Grands, a 25-property hotel chain across 4 Indian cities**, to uncover occupancy trends, revenue performance, booking patterns, and business insights.

## 📊 Project Overview

This project analyzes hotel booking data to understand business performance, evaluate occupancy rates, identify revenue trends, and uncover patterns across different properties, cities, and room categories.

### 🔍 Project Highlights

* 🏨 Analysis of **25 hotel properties across 4 Indian cities**
* 📂 Cleaning and preprocessing of multiple hotel booking datasets
* 📈 Calculation and analysis of **hotel occupancy percentages**
* 💰 Analysis of **revenue generated vs. revenue realized**
* 🌆 City-wise and property-wise occupancy and revenue analysis
* 🛏️ Room category-wise booking and revenue performance
* 📅 Comparison of **weekday vs. weekend occupancy trends**
* ❌ Analysis of booking cancellations and no-show rates
* 🔄 Integration of additional monthly booking data
* 📊 Identification of key business trends and actionable insights

## 🗂️ Dataset Overview

The project uses multiple CSV files containing booking transactions, hotel details, room categories, and calendar information.

| Dataset | Description |
|---|---|
| `fact_bookings.csv` | Booking transactions, guest details, revenue, booking platform, and status |
| `fact_aggregated_bookings.csv` | Daily bookings and room capacity across properties |
| `dim_hotels.csv` | Hotel property details, city, and category |
| `dim_rooms.csv` | Room categories and class information |
| `dim_date.csv` | Calendar details, including month and weekday information |
| `new_data_august.csv` | Additional monthly booking data |

## 🛠️ Tools & Technologies

* **Python** – Programming and data analysis
* **Pandas** – Data cleaning, manipulation, and aggregation
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Jupyter Notebook** – Interactive analysis

## ⚙️ Key Steps Performed

* **Data Exploration:** Examined dataset structure, dimensions, data types, unique values, and distributions.
* **Data Cleaning:** Handled missing values, invalid records, inconsistencies, and revenue outliers.
* **Data Transformation:** Merged multiple datasets, standardized date formats, and prepared data for analysis.
* **Feature Engineering:** Created occupancy percentage metrics using successful bookings and available room capacity.
* **Data Analysis:** Analyzed revenue, occupancy, booking trends, cancellations, and property performance.
* **Business Insights:** Identified patterns and trends to understand hotel performance and potential business opportunities.

## 📌 Key Business Insights

* 📅 **Weekend vs. Weekday Occupancy:** Weekend occupancy (72.4%) is approximately 21 percentage points higher than weekday occupancy (50.9%). This suggests that weekday-specific promotions and dynamic pricing strategies could be more effective than uniform discounting.

* 🌆 **City-wise Revenue & Occupancy:** Delhi records the highest occupancy (60.4%) but the lowest revenue realized (₹29.5 Cr), while Mumbai has a moderate occupancy rate (56.8%) but the highest revenue (₹66.9 Cr). This highlights that higher occupancy does not necessarily translate into higher revenue, indicating potential pricing or room-mix optimization opportunities in Delhi.

* 🛏️ **Room Category Performance:** Occupancy rates remain relatively consistent across room categories, with Presidential rooms at 58.1% and Standard rooms at 56.8% — a difference of just 1.3 percentage points. This indicates that premium room occupancy is not a major bottleneck, while revenue differences are more likely influenced by room pricing.

* 💰 **Revenue Leakage:** Approximately 17.4% of generated revenue is not realized, with revenue generated at ₹206.9 Cr compared to ₹170.9 Cr realized. A cancellation rate of 24.8% and a no-show rate of 5.0% contribute to this revenue gap.

* ⭐ **Customer Ratings:** Approximately 57.9% of bookings have no rating submitted, highlighting a significant gap in customer feedback collection and limiting the ability to evaluate guest satisfaction effectively.

## 🚀 How to Run

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib
```

3. Open `hotels_analysis.ipynb` in Jupyter Notebook and run the cells.

## 🎯 Skills Demonstrated

* Python Programming
* Data Cleaning & Preprocessing
* Data Manipulation using Pandas
* Feature Engineering
* Data Analysis & Visualization
* Business Metrics Analysis
* Analytical Thinking
* Business Insight Generation

## 📌 Conclusion

This project demonstrates the use of Python and data analysis techniques to transform raw hotel booking data into meaningful business insights. It highlights the importance of occupancy, revenue, and booking pattern analysis in understanding hospitality business performance and supporting data-driven decision-making.
