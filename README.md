# Covid_Vaccinations_Visualizations
Kaggle Dataset. All diagrams are produced using Tableau

Dataset

For this exercise I used the below datasets:

country_vaccinations.csv
country_vaccinations_by_manufacturer.csv

from the COVID-19 World Vaccination Progress of kaggle.

Maps of vaccines per country per month
![maps](https://user-images.githubusercontent.com/22845560/147950915-d8a6d03c-3a8e-46e8-9880-4428427addad.PNG)


In these map we can hover the mouse to the countries and see for each country the number of vaccines that have been done and the number of people that have been fully vaccinated with two doses. The colours of the territories on the map show as more to red as more vaccines have been done to that country. Also in the filters we can see the month, by selecting the month we can see for each country the number of vaccines that have been done and the number of people that have been fully vaccinated with two doses till the month which is selected. I keep the max because in the data in every new line we sum the number of vaccines of this day an all the previous ones. So by getting the max of each month per country we get actually the amount of vaccines that have been done till the last day of the month.

ex.If I have selected from the filter March we will get all the vaccines that have been done till the end of March

Total number of vaccines per company per month

![total_number_of_vaccines_per_month](https://user-images.githubusercontent.com/22845560/147951269-00b4dbc9-63a3-4af4-8ddd-028489fb5b31.PNG)

In this diagram we see the total number of vaccines for each company that has been used till the end of month. We can see that till the end of January 183 doses of AstraZeneka have been done. Also as the colours go to deepen blue as bigger is the amount of the vaccinations. I used also the colour representation and not only the number because it is easier for eye of the person to capture the the data without having to remember the numbers which is something that makes people tired.

Total vaccinations per country per brand
![Total vaccinations per country per brand](https://user-images.githubusercontent.com/22845560/147951244-af4d8d74-174c-4cbf-ac80-6f82ddc05435.PNG)


 In this diagram we can see the total Vaccinations per country per brand . From these diagram we can easily see the preferred and most used vaccin per country. The different colours show the different vaccines brands ,the columns show the countries and  the hight shows the max max number of vaccines that have been used in this country by this brand.
From the filters we can choose which brands and which countries we want to show.


