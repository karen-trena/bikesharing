# Citi Bike Sharing

Resources:
new_201908-citibike-tripdata, 201908-citibike-tripdata

[Module 14 Tableau](https://public.tableau.com/views/Module14-/Historia1?:language=en-US&:display_count=n&:origin=viz_share_link)

[Module 14 Challenge Tableau](https://public.tableau.com/views/Module14-Challenge_16598459433340/Historia1?:language=en-US&:display_count=n&:origin=viz_share_link)

Software:
Python, Jupyter notebook, Tableau

## 1. Overview of the statistical analysis:
Convince investors that the bike sharing is a solid proposal by checking August bike trips in NYC.
For this,we needed to make an adjustment to the original data where we convert the "tripduration" column from integer to datatime datatype. This let us have the data converted into hours for the analysis.

## 2. Results:
First, we can see with Viz1 that there are around 2.3 million rides for Aug and most of the clients are men:
![Viz1](https://github.com/karen-trena/bikesharing/blob/main/Pictures/Viz1.png)


Secondly, we can see that younger users have longer rides:
![Viz2](https://github.com/karen-trena/bikesharing/blob/main/Pictures/Viz2.png)


Then, we can see top starting locations and top ending locations are similar. We can see that the most popular ones are around the middle of the city:
![Viz3](https://github.com/karen-trena/bikesharing/blob/main/Pictures/Viz3.png)


Then, all genders have a similar behaviour where they all use the bike in for less than 30 minutes:
![Viz4](https://github.com/karen-trena/bikesharing/blob/main/Pictures/Viz4.png)


Another important thing to mention is that most rides during weekdays are at the beggining of check in for office hours and check out:
![Viz5](https://github.com/karen-trena/bikesharing/blob/main/Pictures/Viz5.png)


Also important to mention that most customers are males suscribers:
![Viz6](https://github.com/karen-trena/bikesharing/blob/main/Pictures/Viz6.png)


Finally, there are hours where demand won´t be affected and can be use to repair bikes. That time of the day is between 3am to 4am:
![Viz7](https://github.com/karen-trena/bikesharing/blob/main/Pictures/Viz7.png)

## 3. Summary:
Bike sharing is an important transportation channel mainly used by males during weekdays. Specially to get to the office and back home from the office. These are used by suscribers that live near their office as their rides tend to be for less than 30 minutes.

To make the analysis more robust, we would recommend 2 more visualizations:
1. Data per month, so we could see data from other months and check if there´s any stationality
2. Check if we have the same suscribers using the service over and over or if we have a robust portfolio of clients. These could help the marketing team to better understand the clients that are driving profit.
