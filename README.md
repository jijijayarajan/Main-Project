📄 Project Report
Analysis of Commodity Prices Across Indian Markets
________________________________________
1. Introduction
Agricultural commodity prices vary across regions, markets and quality grades.
Understanding these variations is essential for farmers, traders, policy makers and market planners to take informed decisions.
This project focuses on analysing agricultural commodity market data to identify:
•	price behaviour across regions, states, districts and markets,
•	the impact of commodity type and grade on prices, and
•	market activity patterns through descriptive and visual analytics.

 This project focuses on the exploratory analysis of commodity price data collected from various markets across India. Using Python and data analysis techniques, the study examines price patterns across states, districts and commodities, and explores the relationships between minimum, maximum and modal prices. Through data cleaning, exploratory data analysis and visualisation, the project aims to identify meaningful trends, regional differences and important insights that can help in understanding the overall behaviour of commodity prices in Indian markets.

________________________________________
2. Objective of the Study
The main objectives of this project are:
•	To analyse how commodity prices differ across markets and regions.
•	To understand the influence of grades on commodity prices.
•	To identify high-value and high-volume commodities.
•	To detect markets with high price volatility.
•	To support decision making through interactive visual analytics.
________________________________________
3. Dataset Description
The dataset contains agricultural market records with the following major attributes:
•	State
•	District
•	Market
•	Commodity
•	Grade
•	Minimum price
•	Maximum price
•	Modal price
•	Arrival date
•	Commodity code
The modal price is used as the primary indicator for market price analysis.
________________________________________
4. Methodology
The project follows a structured data analytics workflow:
 Imported libraries to read data, clean data and draw graphs.
 Pandas,Numpy,Matplotlib,Seaborn,Plotly
1.	Data cleaning and formatting
2.	Conversion of arrival dates to proper datetime format
3.	Grouping and aggregation by commodity, market, grade and commodity type
4.	Descriptive statistics and distribution analysis
5.	Creation of multiple univariate, bivariate and multivariate visualisations
6.	Visual analysis using:
o	bar charts
o	box plots
o	count plots
o	heatmaps
o	line charts
o	pair plots
o	Strip plots
o	interactive Plotly charts
7.	Insight extraction and reporting
________________________________________
5. Key Insights from Visual Analysis
Insight 1 – Grade has a strong influence on price
Across all visualisations, higher quality grades such as FAQ and grade-range categories consistently achieve higher modal prices than Local and Non-FAQ grades.
This confirms that grading directly affects price realisation in Indian markets.
________________________________________
Insight 2 – Flowers and spices form the high-value segment
In grade-wise and commodity-wise price charts, flowers and spices repeatedly appear at the top of the price scale.
They behave as premium commodities with high average modal prices.
________________________________________
Insight 3 – Vegetables and cereals are low-price but high-volume commodities
Count-based charts and distribution plots clearly show that vegetables and cereals appear most frequently in the dataset.
However, their prices remain relatively lower compared to other commodity categories.
This indicates volume-driven markets with relatively smaller margins.
________________________________________
Insight 4 – Significant interstate and inter-market price variation exists
The state-level and market-level average price charts show large differences in modal prices between states and markets.
Some states and markets consistently show much higher prices than others.
This reflects strong regional market behaviour and demand–supply differences.
________________________________________
Insight 5 – Certain markets show very high price volatility
From the market-wise variation analysis, a small number of markets show exceptionally large price fluctuations.
These markets act as high-risk trading zones.
________________________________________
Insight 6 – District-wise heatmap highlights premium commodity influence
The district versus commodity-type heatmap shows that most high-price concentration is driven by:
•	flower commodities,
•	spice commodities, and
•	selected speciality items.
Vegetables remain comparatively stable across districts.
________________________________________
Insight 7 – Wheat and paddy dominate cereal trading
In the “Top 5 commodities in each commodity type” visualisation, wheat and common paddy dominate the cereal and millet group by record count.
They form the core of cereal-based market activity.
________________________________________
Insight 8 – Soyabean dominates the oilseed segment
Oilseed analysis clearly shows soyabean contributing the highest number of market records.
This implies that overall oilseed price trends are largely influenced by soyabean.
________________________________________
Insight 9 – Livestock and pulse commodities have limited representation
The livestock and pulse categories appear with very small counts compared to vegetables, cereals and fruits.
This limits the reliability of conclusions for these two categories.
________________________________________
Insight 10 – High price does not mean high market participation
The combined count versus price visualisation shows that many high-priced commodities have very low market activity, while frequently traded commodities usually have lower prices.
This demonstrates a clear separation between high-value and high-volume commodities.
________________________________________
Insight 11 – Modal price distribution is right-skewed
The histogram of modal prices shows that most records lie in the lower price range, with a small number of very high-priced observations forming a long tail.
This indicates that a small set of premium commodities strongly influences the overall price range.
________________________________________
Insight 12 – Short-term price movements are volatile
The average modal price over time plot shows frequent rises and falls rather than a stable trend.
Short-term arrivals and market conditions strongly affect daily prices.
________________________________________
6. Overall Conclusion
The analysis reveals a clear structural separation in Indian agricultural markets:
•	High-volume and relatively low-price commodities
such as vegetables and cereals dominate market activity.
•	Low-volume but high-price commodities
such as flowers and spices form a premium segment.
Commodity grade plays a crucial role in price formation.
Regional and market-level differences significantly influence price behaviour, and a small number of markets exhibit high volatility.
The study demonstrates that descriptive and interactive visual analytics can effectively support market intelligence and operational decisions.
________________________________________
7. Limitations and Demerits of the Dataset
•	Arrival quantity or traded volume is not available, limiting demand–supply analysis.
•	Livestock and pulse categories have very limited data coverage.
•	The time span is short, which restricts long-term trend and seasonality analysis.
•	External influencing factors such as weather, transport cost and production volume are not included.
•	Grade definitions are categorical and lack standard quality measurements.
________________________________________
8.	Future Recommendations Based on Findings


1. Include arrival quantity and volume for demand–supply analysis.

2. Add multi-year data to enable seasonal and trend modelling.

3. Standardise commodity grade categories.

4. Integrate market arrival and stock information.

5. Build forecasting models for major commodities and markets


________________________________________
9. Final Remark
This project demonstrates how structured visual analytics and interactive dashboards can transform agricultural market data into actionable insights.
With the integration of quantity data, forecasting models and broader market coverage, the system can evolve into a practical decision-support tool for farmers, traders and policy planners.

