# Web Scraping and Data Vizualization Project
**Overview**
This project focuses on web scraping data from the Wikipedia page listing the largest companies in the United States by revenue (2024). The aim is to extract valuable insights from the Fortune 500 list for the fiscal year 2024, perform detailed analysis, and visualize key findings.
**Steps Involved**
1. Web Scraping: Utilized the BeautifulSoup library to parse the HTML content from the Wikipedia page.
2. DataFrame Creation: Organized and manipulated the extracted data using the pandas library.
3. CSV Conversion: Saved the data into a CSV file named Companies.csv for future reference and analysis.
4. Data Analysis: Conducted in-depth analysis of revenue, employee metrics, and industry performance from the extracted data.
5. Vizualization: Used Matplotlib to create insightful visualizations for better understanding of trends and comparisons.
**Project Details**
Language Used: Python
Libraries Used: BeautifulSoup, requests, pandas, matplotlib
Wikipedia URL: [List of largest companies in the United States by revenue](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)
**Insights**
Top 5 Performing Companies By Revenue Growth : Nvidia (125.9), Goldman Sachs (57.8), Citigroup (55.1), JPMorgan Chase (54.7), Bank of America (49.4)
Bottom 5 Performing Companies by Revenue Growth : Valero Energy (-18.8), World Kinect Corporation (-19.2), Dow Chemical Company (-21.6), ConocoPhillips (-28.7), Pfizer (-41.7)
Top 5 Companies by Revenue per Employee : Fannie Mae, StoneX Group, Valero Energy, Freddie Mac, Plains All American Pipeline
Popular Headquarters of Companies: New York City, New York, hosts the highest concentration of these companies, reflecting its role as a financial and corporate hub.
Industry Trends: Industries like retail and finance show high growth rates.
**Challenges Encountered**
Data Cleaning: Handling inconsistent data formats such as commas in numbers and percentage signs required careful preprocessing.
Metric Selection: Deciding on meaningful metrics like Revenue per Employee to measure efficiency involved thoughtful consideration.
Visualization Choices: Balancing clarity and depth of insights in visualizations was a challenging but rewarding process.
**Conclusion**
This project demonstrates the power of web scraping and data visualization in extracting meaningful insights from publicly available data. By analyzing Fortune 500 companies, we highlighted trends, identified key performers, and offered actionable recommendations for various stakeholders. This analysis can serve as a foundation for future projects exploring broader datasets and more nuanced financial metrics.


