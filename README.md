# World-Cup-Prediction---Project_1
A ML model that will help predict the winning country of the 2022 World Cup that took place in Qatar


Phase 1: Web Scraping 
  - In this initial phase, the goal was to gather relavant details such as the fixtures, the home and away teams as well as the results of the previous fixtures
  - The main library used for this phase would be the BeautifulSoup Library. This library helped in gathering the raw HTML content and using various methods the needful content was extracted. 
  - A single function was used to gather the details and store in the data frame(using Pandas Library Functions)
  
  
  
Phase 2: Data Cleaning and Transformation
 - The primary aim of this process was to eradicate any missing values or incorrect values that may have been scraped from the web.
 - The Pandas Data Frame was used excessivley to perform the various operations
 - The data types were also modified and using regex the redundant data were removed. The clean data types were then added and exported
 
 
Phas 3: Model Building
- Using Poisson Distribuition the probablity were calculated. The parameters that were included were the goals scored and goals conceded. 
- Two functions were created to update the table with the winner and to find the respective winners. There functions were used iteratively to find the winner 
