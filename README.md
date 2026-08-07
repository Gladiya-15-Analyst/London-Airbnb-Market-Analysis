# Data-Driven Airbnb Market Intelligence & Revenue Optimization
An end-to-end Data Analytics and Machine Learning project analyzing Airbnb listings in London using Python, statistical analysis, and predictive modeling.
<div align="center">

*Uncovering pricing patterns, host performance, and demand trends across 92,000+ London Airbnb listings*

<div align="center">

**Analyzing 92,000+ Airbnb listings to uncover pricing trends, market patterns, and business insights across London.**

Project Overview

The Airbnb marketplace has transformed the short-term accommodation industry by connecting millions of travelers with property owners worldwide. Understanding how listing characteristics, pricing, host attributes, guest reviews, and geographical location influence the marketplace is essential for both business decision-making and customer experience.

This project presents a comprehensive Exploratory Data Analysis (EDA) of Airbnb listings in London. Using Python and advanced visualization libraries, the analysis investigates pricing behavior, market composition, geographical trends, host characteristics, and customer engagement while following a complete professional data analysis workflow.

The project demonstrates the practical application of data cleaning, feature engineering, statistical analysis, and business intelligence visualization techniques to transform raw data into meaningful insights.

Project Objectives

The primary objectives of this project are to:

Perform comprehensive data cleaning and preprocessing to improve data quality and analytical reliability.
Explore the statistical characteristics of Airbnb listings using descriptive and inferential analysis.
Examine pricing distributions and identify significant outliers within the London Airbnb market.
Analyze relationships between listing price, guest ratings, reviews, room types, and property types.
Investigate the geographical distribution of listings across London using interactive mapping.
Identify dominant accommodation categories and market composition.
Generate business-oriented insights that can support pricing strategies, investment decisions, and customer understanding.
Demonstrate an end-to-end professional data analysis workflow suitable for portfolio and industry applications.
 Dataset Information
Attribute	Details
Dataset	Airbnb London Listings
Records	92,638 Listings
Features	70+ Variables
Data Type	Structured Tabular Data
Tools Used	Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly
Environment	Google Colab
🛠 Project Workflow
Raw Dataset
      │
      ▼
Initial Exploration (EDA)
      │
      ▼
Data Cleaning & Transformation
      │
      ▼
Feature Engineering
      │
      ▼
Statistical Analysis
      │
      ▼
Business Visualizations
      │
      ▼
Insights & Recommendations
 Data Cleaning & Transformation

A comprehensive data cleaning pipeline was implemented to improve data quality and ensure reliable analysis.

Cleaning Steps
Removed duplicate observations.
Identified and handled missing values.
Eliminated columns with nearly 100% missing data.
Converted data types into appropriate formats.
Standardized categorical values.
Cleaned monetary variables by removing currency symbols.
Parsed date columns into datetime format.
Removed unnecessary URL and metadata columns.
Verified data consistency across numerical and categorical variables.
Prepared the dataset for feature engineering.
⚙️ Feature Engineering

Several new analytical features were created to enhance the dataset and support deeper business analysis.

Engineered variables include:

Amenity Count
Bathrooms Count
Price per Guest
Price Category
Availability Category
Host Experience Metrics

These engineered variables enabled richer visualizations and more meaningful insights than the original dataset alone.

 Statistical Analysis

The statistical analysis examined the distribution, variability, and relationships among numerical variables.

Analyses Performed
Descriptive Statistics
Distribution Analysis
Price Distribution
Boxplot Analysis
Variance Analysis
Standard Deviation Analysis
Deviation from Mean
Correlation Matrix

These analyses provided a strong statistical foundation before moving into business-focused visualization.

 Business Visualizations

The project incorporates advanced interactive visualizations designed to answer practical business questions.

Visualization	Business Question
KPI Dashboard	What is the overall state of the Airbnb market?
Treemap	Which property types dominate the market?
Interactive Plotly Map	Where are listings concentrated geographically?
Donut Chart	What is the market share of each room type?
Horizontal Bar Chart     Which London boroughs have the highest average Airbnb listing prices?
Bubble Chart	How are price, ratings, and reviews related?
Funnel Chart	How do listings progress across price categories?
 Key Insights
 1. Entire Home accommodations dominate the London Airbnb market.

The Treemap and Donut Chart revealed that Entire Home/Apartments account for the largest proportion of Airbnb listings, highlighting strong traveler preference for private accommodations over shared spaces.

 Airbnb prices are highly right-skewed.

Statistical analysis showed that most listings fall within lower and moderate price ranges, while a relatively small number of premium properties significantly increase the overall average price.

This indicates that the median price provides a more representative measure of central tendency than the mean.

 3. Listing prices exhibit substantial variability.

Variance, Standard Deviation, and Boxplot analyses identified considerable dispersion in prices along with numerous legitimate luxury-property outliers.

These outliers reflect actual market behavior rather than data quality issues.

4. High guest ratings are consistent across price ranges.

The Bubble Chart demonstrated that most listings maintain ratings above 4.5, regardless of price.

This suggests that exceptional guest experiences are not limited to luxury accommodations.

 5. Moderately priced listings receive the greatest guest engagement.

Listings within moderate pricing tiers generally accumulated larger numbers of reviews than premium listings, indicating stronger booking frequency and broader customer appeal.

 6. Airbnb listings are geographically concentrated.

The Interactive Plotly Map revealed that listings are densely clustered around central London, with premium-priced accommodations concentrated near major tourist and commercial districts.

 7. Property type significantly influences pricing.

Different property types command distinct pricing levels, with larger and more private accommodations generally associated with higher average prices.

 8. Price categories reveal market segmentation.

The Funnel Chart illustrated the distribution of listings across pricing tiers, highlighting that the majority of listings belong to affordable and mid-range segments, while premium listings represent a comparatively smaller share of the market.

 9. Numerical variables exhibit mostly weak-to-moderate correlations.

The Correlation Matrix indicated that Airbnb pricing is influenced by multiple interacting factors rather than a single dominant variable.

This suggests that pricing decisions depend on a combination of property characteristics, location, host attributes, and guest engagement.

 10. Feature engineering enhanced analytical depth.

Creating variables such as Amenity Count, Price Category, and Price per Guest enabled more sophisticated analysis and richer business insights than the raw dataset alone.

Conclusion

This project successfully demonstrates a complete end-to-end exploratory data analysis of Airbnb listings in London by integrating rigorous data preprocessing, feature engineering, statistical analysis, and advanced interactive visualization techniques.

The analysis revealed that London's Airbnb market is largely driven by entire-home accommodations, with prices displaying significant variability and a positively skewed distribution. Premium listings are concentrated in central areas of London, while moderately priced properties generate higher levels of guest engagement. Furthermore, consistently high review ratings across all price ranges indicate that service quality is maintained regardless of pricing tier.

By combining statistical techniques with interactive business visualizations—including KPI dashboards, Treemaps, Interactive Maps, Donut Charts, Bubble Charts, and Funnel Charts—the project provides a comprehensive understanding of London's short-term rental marketplace.

Overall, this analysis showcases the ability to transform raw data into actionable business insights using Python and modern data visualization techniques, reflecting the complete analytical workflow expected in real-world data analytics projects.

Tools & Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Google Colab
Jupyter Notebook
 Repository Structure
 
Airbnb-London-EDA/

│
├── Project Overview
├── Objectives
├── Dataset Information
├── Project Workflow
├── Data Cleaning
├── Feature Engineering
├── Statistical Analysis (brief description only)
├── Business Dashboard (Images)
│      ├── KPI Dashboard
│      ├── Treemap
│      ├── Plotly Map
│      ├── Donut Chart
│      ├── Bubble Chart
│      ├── Borough Price Chart
│      └── Funnel Chart
├── Key Insights
├── Conclusion
├── Tools Used
└── Repository Structure

Dashboard	Preview

KPI Dashboard	<img width="1653" height="712" alt="Screenshot 2026-08-05 202748" src="https://github.com/user-attachments/assets/9f5d3f93-a585-405c-a369-6f0dc551382f" />

Treemap	<img width="1704" height="627" alt="Screenshot 2026-08-05 202841" src="https://github.com/user-attachments/assets/62d676e2-4ce1-42b3-92c7-d61eebf157fb" />

Interactive Map	<img width="1711" height="726" alt="Screenshot 2026-08-05 202958" src="https://github.com/user-attachments/assets/26449dfc-0ad3-4aed-89d3-e582c4df2a33" />

Donut Chart	<img width="1618" height="598" alt="Screenshot 2026-08-05 203025" src="https://github.com/user-attachments/assets/f2cb7ba8-126f-467b-951b-ef52eed70cbc" />

Horizontal Bar Chart (Top 15 Boroughs by Average Price)        <img width="1672" height="703" alt="Screenshot 2026-08-05 203131" src="https://github.com/user-attachments/assets/e3393b1f-3666-4295-980e-081f14cd92aa" />

Bubble Chart	<img width="1498" height="655" alt="Screenshot 2026-08-05 203058" src="https://github.com/user-attachments/assets/e1f12ff1-a8ed-4de0-9dda-d6b078a410d6" />

Funnel Chart	<img width="1680" height="678" alt="Screenshot 2026-08-05 203201" src="https://github.com/user-attachments/assets/8d868ba4-bc46-4208-8a7e-14310f2aec4d" />


# 👨‍💻 Author

## Gladiya Francline

**Aspiring Data Analyst**

### Skills

- Python
- SQL
- Excel
- Power BI
- Data Analytics
- Data Visualization
- Exploratory Data Analysis

📌 **GitHub:**https://github.com/Gladiya-15-Analyst
📌 **LinkedIn:**www.linkedin.com/in/gladiya-francline
---

## ⭐ Support

If you found this project useful, consider giving it a **⭐ Star** on GitHub!


The dataset is provided by **Inside Airbnb** under their published terms of use.

---

