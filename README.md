# tourism_database_ETL


50 Most Visited Countries Database

Purpose: 1) Elaborate a database that allows users to understand what is behind the top 50 most visited countries, with data such as affordability, number of unesco sites, safety, infraestructure,income group, etc. Identify pattterns! 
2) Serves as a guide for those wanting to choose a tourism destination based on specific characteristics (such as natural resources, affordability, region,etc.)

1. I gathered data from the most visited countries of 2022 from Kaggle ('most_visited.csv')
2. I did web scraping with BeautifulSoup to gather raw data on safety and the number of UNESCO Heritage Sites from two websites: UNESCO and Travelsafe-abroad.com
3. I accesed the Travel & Tourism Development Index of 2021 publsihed by the World Travel Organization. Extracted certain columns on: region, affordability, natural_resources, ict_access, infraestrucutre,etc.
4. I created a table for each of the three previous extractions, then merged them together into the 'tourism_database'.
5. I uploaded it to SQL from Python.

![graph1](https://github.com/rodrigogtz99/tourism_database_ETL/assets/139127453/bbf3f7e7-a176-4923-9984-0c5ff6f8beb8)

![graph2](https://github.com/rodrigogtz99/tourism_database_ETL/assets/139127453/2b6b584f-0f6b-4a4a-a9b8-9154966fa3b8)

![graph3](https://github.com/rodrigogtz99/tourism_database_ETL/assets/139127453/1a5a3a9d-0f07-4962-99bd-6f85b4bd0732)

![graph4](https://github.com/rodrigogtz99/tourism_database_ETL/assets/139127453/dca55f0e-f4ef-41d8-86d6-fd561ab57eb5)

![graph5](https://github.com/rodrigogtz99/tourism_database_ETL/assets/139127453/46a09c78-b3e0-45ee-adfa-28072982e9af)

![graph6](https://github.com/rodrigogtz99/tourism_database_ETL/assets/139127453/18cc37ae-29d6-4e61-929d-60f153dcb0d6)
