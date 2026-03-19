# 1. A Comprehensive Tableau Dashboard for British Airways Customer Feedback Analysis. 
An interactive Tableau dashboard designed to visualize and analyze customer satisfaction metrics across British Airways' global operations, enabling data-driven decisions to enhance the passenger experience.

# 2. Short Description / Purpose
The British Airways Review Dashboard is an interactive visualization tool built to provide a holistic view of customer feedback. It aggregates review data across multiple key performance indicators (KPIs) such as Cabin Staff Service, Entertainment, Food & Beverages, and Seat Comfort. The dashboard is intended for airline operations managers, customer experience teams, and strategic planners who need to quickly identify strengths, pinpoint areas for improvement, and understand how satisfaction varies across different aircraft, routes, traveler types, and time periods.

#3. Tech Stack
The dashboard was built using the following tools and technologies:
Tableau Public - The primary data visualization platform used for creating the interactive dashboard and map layers.
Mapbox & OpenStreetMap - Integrated mapping services used to power the geographical visualization of average ratings by country.
Data Aggregation & Calculated Fields - Utilized within Tableau to create average rating metrics (e.g., Avg. Entertainment, Avg. Food Beverages) and to apply filters dynamically.
Interactive Filters - Implemented for seamless data exploration based on Seat Type, Traveler Type, Aircraft Group, Continent, and time period.

# 4. Data Source
Source: Aggregated customer review data for British Airways, likely sourced from a third-party review platform (e.g., Skytrax). The dataset includes reviews spanning from March 2016 to July 2022, covering various aircraft models, routes, and traveler segments.

# 5. Features / Highlights
# Business Problem: 
For a major airline like British Airways, maintaining high customer satisfaction is crucial for brand loyalty and competitive advantage. However, understanding the nuances of customer feedback is challenging. Key strategic questions include:

Which aspects of the flight experience (e.g., cabin staff, entertainment, food) are our strongest performers, and which are our weakest?

How does customer satisfaction vary by aircraft type, and are there specific planes that consistently underperform?

Are there significant geographical differences in how our service is perceived across different countries?

How do the experiences of business travelers differ from those of leisure or family travelers?

Goal of the dashboard: To create a centralized, easy-to-use platform that allows stakeholders to monitor satisfaction trends, identify problem areas quickly, and make informed decisions to improve the overall passenger experience.

# Walk-through of key visuals:

KPI Header: The dashboard opens with a clear summary of key metrics, including the overall average rating (4.4) and specific scores for entertainment (1.4), cabin staff (3.3), and food (2.4), instantly highlighting areas of strength and weakness.

Geographic Performance Map: An interactive map color-codes countries by their average overall rating. This visual immediately reveals regional satisfaction patterns, allowing teams to investigate why certain countries (e.g., United States with 4.7) rate the airline much higher than others.

Trend Analysis by Aircraft: The line chart, "Average Overall Rating By Month," allows users to track performance over time and compare it across different aircraft models (e.g., Boeing 747-400 vs. A320). This helps in identifying if specific fleet types are correlated with changes in customer sentiment.

Dynamic Filtering: A comprehensive set of filters on the right side of the dashboard (Month, Continent, Aircraft, Seat Type, Traveler Type) empowers users to segment the data and answer specific questions, such as "What is the food rating for Business Class passengers on flights to Europe?"

# Business Impact & Insights
Targeted Service Improvements: The dashboard clearly shows that while cabin staff service (3.3) is a relative strength, entertainment (1.4) and food & beverages (2.4) are significant pain points for customers. This provides a clear mandate for operational teams to investigate and improve the in-flight entertainment options and catering services.

Aircraft-Specific Strategies: By tracking ratings by aircraft model (Boeing 747-400, 777-200, A320), the airline can identify if specific planes have consistent issues (e.g., with seat comfort) and prioritize those for refurbishment or allocate them to less quality-sensitive routes.

Regional Marketing & Operations: The map highlights a stark geographical divide in satisfaction. Understanding why ratings are lower in certain European countries versus the US can lead to targeted operational reviews for specific routes or regional marketing campaigns to manage and improve brand perception.

Personalized Customer Experience: The ability to filter by traveler type (Business, Couple Leisure, Family Leisure) allows the airline to tailor its improvements. For example, if Family Leisure travelers rate ground service lower than Business travelers, B.A. can focus on improving family-specific check-in and boarding processes.

# 6. Tableau Link
(https://public.tableau.com/app/profile/ankit.shaw/viz/British_Airways_Reviews_DASHBOARD/Dashboard1)


