# Wait-time-in-coffee-Stores-in-downtown-toronto-datasets
This dataset gives information about the wait time in Tim Hortons stores in downtown Toronto during working hours. It contains 72 records for Tim Hortons stores in down two Toronto areas. The data is scraped from google maps using the selenium python package. The dataset size is 72 X 10. The raws' names are as follows:
1. GoogleMaps Entity unique ID
2. Store Name
3. Address
4. Sunday 
5. Monday 
6. Tuesday 
7. Wednesday 
8. Thursday 
9. Friday 
10. Saturday
 
The type stored in weekday columns is a JSON object. Its keys are hours in 12-hour clock formats, and its values are the scraped popular times values from google maps.
