Intro:

For my personal project, I decided to examine United States government data on the number of weapons sold in 2024 under Title 22, Foreign Military Sales, and the amount of foreign aid these countries received in the same year. I have always been interested in modern military politics, and after discussing this project with Professor DeFord, I decided to pursue this route. My goal was to determine whether there were any correlations in the data and whether they changed when the data were sorted by region or when specific parameters were added. My data comes from the Department of Defence's fiscal year (FY) 2024 edition of the Historical Sales Book, as well as from ForeignAssistance.gov, which provides a CSV file of a country-by-country summary of foreign aid.  



Data Processing:

To begin, I had to fix many errors that occurred during data copying. For example, many of the country names did not match, i.e., Saint Vincent vs St. Vincent. I also had to group all these countries by region myself later, since I initially did not know I wanted to do a region-by-region analysis. I also had to remove countries that did not appear on the military sales list, as that meant they had not traded officially under Title 22 since 1950, and since I was examining 2024, this was not necessary. Additionally, the Historical Sales Book contained countries that no longer exist (Yugoslavia) or entities that were not countries at all (NATO). Once I began processing my data, I found it crucial to remove certain outliers so I could get a clearer picture after my preliminary research. I then examined correlations in both country groups as well as the overall whole.  



<img width="671" height="397" alt="Screenshot 2025-11-29 at 1 40 20 PM" src="https://github.com/user-attachments/assets/b0d9c1dc-c0d9-47dc-989e-feecc50c7c99" />

This is one of my overall graphs, after I had removed those values in the top and bottom 5th percentiles. It colors each area according to the regions used by USAID. AFR indicates Sub-Saharan Africa, MENA is the Middle East and North Africa, E&E is Europe and Eurasia, EAP is East Asia and the Pacific, LAC is Latin America and the Caribbean, and other is not country organizations like NATO, which were nevertheless in the data set. It then compares the amount of foreign aid received in 2024, the x variable, to the response, the amount of money spent on weapons in 2024. I chose to do a correlation as my data set contains 2 continuous variables, and it was a simple way to evaluate them. I did some analysis by checking the correlation, which returned a -.1659, a very weak negative correlation. This is what prompted me to delve deeper into each region to see if this general correlation was carried about between the groups and to see if changing the parameters, i.e., only including values that were under $50,000,000 in weapons spent, would change the correlation and the overall graph. 

