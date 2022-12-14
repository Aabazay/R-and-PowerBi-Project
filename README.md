# R-and-PowerBi-Project
![alt text](https://github.com/Aabazay/R-and-PowerBi-Project/blob/2ceac94b99bef906c968306584d98bfa71985115/Dashboard.png)
[Link to dashboard]( https://app.powerbi.com/groups/me/reports/4a6116c0-624d-46f4-adb4-a18859bd0f5f?ctid=6efd0f20-57c8-4447-b53f-00d4992ca50b&pbi_source=linkShare)

-------------------------------------
Aim: To analyze the performance of Hollywood movies 

Data: Title, genre, studio, profitability and ratings for movies released 2007-2012.
Source: [InformationIsBeautiful.net](https://user-images.githubusercontent.com/119430189/205911960-6e7f4f4a-c1ac-4f36-842b-3c4957df68b6.png)

-------------------------------------

As my first task, I was given a data set about Performance of Hollywood Movies. I have uploaded that data set into PositCloud where I have analysed and cleansed it. Please see cleansed R Script below. During my annalysis, I've experienced that the original code to missing values didn't work I have then explored and found a code that did work.  "df <- df[rowSums(is.na(df)) == 0, ]"

![alt text](https://github.com/Aabazay/R-and-PowerBi-Project/blob/9f7003f3dd27da8501a3410c1ecf7cd21748ce44/R%20script.png)

--------------------------------------

After extracting my clean data set from R, I have uploaded it into PowerBi to create an easy to read visual for the client to see. The client requested to see:

•	The average ratings of each genre
•	The number of movies produced per year 
•	The audience scores for each film  
•	The profitability per studio 
•	The worldwide gross per genre 

I have also included:

•	The sum of worst movies per genre
•	The number of years in every genre
The client request the use of their brand colours which is blue, brown and green. 
