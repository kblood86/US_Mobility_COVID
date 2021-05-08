## Mobility Changes in the U.S during the COVID-19 Pandemic 2020-2021

TEAM MATPLOTLIB.PYPLOT: Lucas Munson, Katie  Blood, Gloria Evans

Data Source: https://www.google.com/covid19/mobility/ 

These Community Mobility Reports aim to provide insights into what has changed in response to policies aimed at combating COVID-19. The reports chart movement trends over time by geography, across different categories of places such as retail and recreation, groceries and pharmacies, parks, transit stations, workplaces, and residential.

The Community Mobility Reports were developed to be helpful while adhering to our stringent privacy protocols and protecting people’s privacy. No personally identifiable information, such as an individual’s location, contacts or movement, will be made available at any point.

Data Limitations:  
-The data used only goes back to the beginning of the pandemic, roughly February 2020.  
-The baseline used is five weeks from the beginning of the year 2020. There is no way to determine if the baseline is a representative week.   
-Parks also are a place that fluctuates based on the time of year. Visitation will be higher during the warmer months.   
-This dataset also includes weekends and holidays leading to some decreases in data. 


Hypotheses:  
-Grocery stores and pharmacies were still essential outings during the pandemic and therefore did not experience as great of a decrease in movement in comparison to other outings (retail and recreation).
-We believe that all categories analyzed will have a decrease of some magnitude except for parks due to their ability for safe social distancing.  
-There is a statistical difference in the data depending on which state it was collected in.


The data is categorized as the following: Retail/Recreation, Grocery/Pharmacy, Parks, Transit, Residential, and Workplaces.    
All data is a percent change from the baseline (average during January and February 2020)

United States Mobility during the COVID-19 Pandemic
![United States Mobility](https://user-images.githubusercontent.com/77282780/117511350-8e58c880-af5b-11eb-9073-aea5a3b83a7e.png)

Graph comparing visits to grocery and pharmacy stores during March 2020 and March 2021:
![Grocery and Pharmacy for March 2020   March 2021](https://user-images.githubusercontent.com/77282780/117511323-81d47000-af5b-11eb-895c-216274ba3e0e.png)

Graph comparing visits to grocery and pharmacy stores during April 2020 and April 2021.
![Grocery and Pharmacy for April 2020   April 2021](https://user-images.githubusercontent.com/77282780/117511217-59e50c80-af5b-11eb-89ce-6438bb985162.png)

Graph comparing visits to retail and recreation stores during March 2020 and March 2021.
![Retail and Recreation for March 2020   March 2021](https://user-images.githubusercontent.com/77282780/117511398-a4ff1f80-af5b-11eb-80ce-74c1d589f5aa.png)

Graph comparing visits to retail and recreation stores during April 2020 and April 2021.
![Retail and Recreation for April 2020   April 2021](https://user-images.githubusercontent.com/77282780/117511408-a92b3d00-af5b-11eb-92d4-5d22b1698429.png)

Graph comparing visits to transit stations during March 2020 and March 2021.
![Transit Stations for March 2020   March 2021](https://user-images.githubusercontent.com/77282780/117511441-b9dbb300-af5b-11eb-80d8-6bca8cefb5ce.png)

Graph comparing visits to transit stations during April 2020 and April 2021.
![Transit Stations for April 2020   April 2021](https://user-images.githubusercontent.com/77282780/117511449-bd6f3a00-af5b-11eb-8a28-503bd28eada1.png)

Graph comparing visits to workplaces during March 2020 and March 2021.
![Workplaces for March 2020   March 2021](https://user-images.githubusercontent.com/77282780/117511466-c102c100-af5b-11eb-9319-0349f964eb93.png)

Graph comparing visits to workplaces during April 2020 and April 2021.
![Workplaces for April 2020   April 2021](https://user-images.githubusercontent.com/77282780/117511483-c5c77500-af5b-11eb-927c-ad256b40b05d.png)

Graph comparing visits to grocery stores and pharmacies in different states (urban vs. rural)
![state_Grocery And Pharmacy Percent Change From Baseline](https://user-images.githubusercontent.com/77282780/117512146-0a074500-af5d-11eb-9502-8058ad8b8e92.png)

Graph comparing visits to retail and recreation stores in different states (urban vs. rural)
![state_Retail And Recreation Percent Change From Baseline](https://user-images.githubusercontent.com/77282780/117512180-1ab7bb00-af5d-11eb-90bf-5c31a72b384a.png)

Heat Map showing the average percent change for visits to retail stores during the pandemic:
![Heat Map](https://user-images.githubusercontent.com/77282780/117512232-3ae77a00-af5d-11eb-815c-60684d4cbf6c.png)


Summary:  
-There is a statistically significant relationship between states and movement data.   
-Grocery stores and pharmacies showed a smaller retraction in number of visitors during the pandemic.   
-The pandemic had a significant effect on all types of movement data except parks, which saw a large upswing. This upswing can be explained by a seasonal swing, and by people’s willingness to engage in outdoor activities compared to indoor activities during the pandemic.   


Further Considerations:  
-Adding a multi-variable linear regression using case data would be interesting. That way we could make a predictive model that would project future cases based on movement data.   
-Finding additional data sources to provide 2019 data for a more realistic baseline and further year comparisons.   
-Drilling down into county-level data for a more complete look at the rural/urban divide that exists during the pandemic.   

