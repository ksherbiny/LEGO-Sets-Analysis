# LEGO-Sets-Analysis
This Power BI report offers a comprehensive and interactive exploration of LEGO's product evolution from 1970 to 2022. Designed to provide dynamic insights into market trends, pricing strategies, and age targeting, this analysis serves as a powerful analytical tool for understanding how LEGO's product offerings have developed over more than five decades. 


Project Objectives:
To deliver an in-depth analysis of LEGO set characteristics, including set name, theme, number of pieces, age recommendation, retail price, and release year.
To visualize long-term trends in LEGO set releases, identifying growth patterns in the number of sets produced annually.
To explore the prevalence and impact of dominant themes (e.g., Star Wars, Technic) in terms of variety and piece count.
To analyze price-per-piece consistency and identify themes or periods that deviate from the average, potentially indicating collector value or unique product lines.
To track the diversification of age recommendations, shedding light on LEGO's expansion into new demographic markets, including adult consumers.

Key Features & Dashboard Content:
The dashboard is meticulously structured across several interactive pages, allowing for diverse data exploration:
"Set Overview" Page: Provides a concise summary of LEGO set data, showcasing the total number of sets, average pieces per set, and overall price trends.
"Theme Analysis" Page: Focuses on the performance and evolution of different LEGO themes, illustrating their variety, piece counts, and historical presence. This page allows for a deep dive into specific themes like Star Wars and Technic to understand their impact.
"Pricing Trends" Page: Presents an analysis of price-per-piece over time, highlighting its relative consistency and identifying outliers that might represent collector's items or specialized sets.
"Age Demographics" Page: Explores the shift in age recommendations over the years, visualizing how LEGO has broadened its target audience and entered the adult market.
Dynamic Filtering: Utilizes intuitive slicers (by Theme, Year, and Age Range) across pages, enabling users to effortlessly navigate and focus on specific data points or trends relevant to their interests.

Technical Implementation & Overcome Obstacles:
This dashboard was developed using Power BI for robust data visualization and DAX (Data Analysis Expressions) for creating calculated measures and intricate filtering logic. The data model (as shown in the provided "data model.jpg" image) is thoughtfully designed with interconnected tables, including Lego-Sets, Theme, Theme GRP, Category, Year, and Age, ensuring seamless data integration and cross-analysis.
Key technical aspects and considerations during development include:
Data Cleaning and Transformation: The initial dataset of over 18,000 LEGO sets (as shown in the "data file.jpg" image) underwent rigorous cleaning and transformation within Power BI's Power Query Editor to ensure data quality and consistency. This involved handling missing values, standardizing text fields, and converting data types.
Robust Data Model Design: The relational data model was crucial for enabling accurate drill-downs and cross-filtering. Establishing clear relationships between Lego-Sets and dimension tables like Theme, Year, and Age allowed for efficient data aggregation and analysis.
DAX Measures for Key Metrics: Custom DAX measures were created to calculate key metrics such as "Price-per-piece," "Number of Sets Released Annually," and "Average Pieces per Set," providing dynamic and accurate insights.

Key Insights:
This dashboard empowers stakeholders and enthusiasts to gain valuable insights, including:
Identifying periods of significant growth in LEGO's product releases and understanding the drivers behind this expansion.
Recognizing the sustained popularity and dominance of key themes and their contribution to the overall LEGO portfolio.
Analyzing pricing strategies and identifying sets or themes that hold unique value or represent premium offerings.
Understanding LEGO's successful diversification into various age groups, particularly its effective targeting of the adult market.
Providing a visual narrative of LEGO's product strategy and consumer targeting over 50+ years, offering actionable insights for marketing teams, toy collectors, and business analysts interested in product evolution and pricing models.
This project demonstrates the power of data visualization in transforming raw data into actionable insights, offering a deeper understanding of LEGO's enduring legacy in creative play.

