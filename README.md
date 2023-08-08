# tourism_database_ETL


50 Most Visited Countries Database

Purpose: 1) Elaborate a database that 
2) Serves as a guide for those wanting to choose a tourism destination based on specific characteristics (such as natural resources, affordability, region,etc.)

1. I gathered data from the most visited countries of 2022 from Kaggle ('most_visited.csv')
2. I did web scraping with BeautifulSoup to gather raw data on safety and the number of UNESCO Heritage Sites from two websites: UNESCO and Travelsafe-abroad.com
3. I accesed the Travel & Tourism Development Index of 2021 publsihed by the World Travel Organization. Extracted certain columns on: region, affordability, natural_resources, ict_access, infraestrucutre,etc.
4. I created a table for each of the three previous extractions, then merged them together into the 'tourism_database'.
5. I uploaded it to SQL from Python.


