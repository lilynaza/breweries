

The data set is in a csv formate I first created a table using the query belowe before loading the data set.


![SQL_create](https://user-images.githubusercontent.com/78624637/179374168-3b03a7e7-ccd4-40f1-9128-d9a4640351fa.PNG)




# Problem Statement
The manager of an international breweries need to make better decision making in order to maximize profit and reduce loss to the lowest minimum. He has asked me to perform various analysis to aid him in his decision making using data from the past three years.


# PROFIT ANALYSIS

1. Within the space of the last three years, what was the profit worth of the breweries, inclusive of the anglophone and the francophone territories?

![1](https://user-images.githubusercontent.com/78624637/179337818-d2b5bcad-af27-4733-b784-0e462b7c0a6d.PNG)

* Result

![1r](https://user-images.githubusercontent.com/78624637/179337827-fdfc21ff-7064-448b-8559-4697f70827f7.PNG)


The breweries made a total of 105587420 profit with in 3 years


2. Compare the total profit between these two territories in order for the territory manager, Mr. Stone to make a strategic decision that will aid profit maximization in 2020.

To group the data into Anglophone and Francophone I wrote a CTE.

![2](https://user-images.githubusercontent.com/78624637/179337842-b4f675dd-0fc5-45ff-91ab-e9cd60ef4fae.PNG)

* Result

![2r](https://user-images.githubusercontent.com/78624637/179337846-903c6a7f-b7ed-4968-b73f-f50ff81bba70.PNG)


Within three years Anglophone made a total of 42389260 profit and Francophone made a profit of 63198160



3. What country generated the highest profit in 2019


![3](https://user-images.githubusercontent.com/78624637/179337848-55bcef66-a931-4af0-b83e-ba89d41d826d.PNG)

* Result


![3r](https://user-images.githubusercontent.com/78624637/179337852-504e102b-f1a2-48af-81bb-5d310239cf22.PNG)

Ghana made a total of 7144070 profit in 2019 making them the highest profit generating country 



4. Help him find the year with the highest profit.

![4](https://user-images.githubusercontent.com/78624637/179337853-632a8ee8-096c-4693-a2e8-eee937847218.PNG)


* Result

![4r](https://user-images.githubusercontent.com/78624637/179337855-012356cd-8fee-4f11-a81c-f311ccfc5a7a.PNG)

The highest profit was made in 2017 with a profit of 38503320


5. Which month in the three years was the least profit generated?

![5](https://user-images.githubusercontent.com/78624637/179337862-cdb7a41b-4a01-4555-a37d-eb9ee4a6217b.PNG)

* Result


![5r](https://user-images.githubusercontent.com/78624637/179337866-a3bcb7c2-f089-4039-926f-8f36f52b8a6c.PNG)

* April made the least profit 


6. What was the minimum profit in the month of December 2018?

![6](https://user-images.githubusercontent.com/78624637/179337873-75b7b2a7-e049-476e-aea2-a1695225a3e9.PNG)

* Result


![6r](https://user-images.githubusercontent.com/78624637/179337880-c96cf0c8-a815-43e0-a44b-0d3ed5c35eab.PNG)

The mininum profit in the month of December was 3902160



7. Compare the profit for each of the months in 2019

![7](https://user-images.githubusercontent.com/78624637/179337884-39dc36be-9b57-447e-87ab-965f9d039e7a.PNG)

* Result 


![7r](https://user-images.githubusercontent.com/78624637/179337891-036b7c02-d8b2-412b-8e96-0a0d4c0c5c06.PNG)

August made a total of 2982800 followed by July which made 2945340 profit.



8. Which particular brand generated the highest profit in Senegal?


![8](https://user-images.githubusercontent.com/78624637/179337897-73c8bbb8-c007-4411-8ce0-35ee2ef93fae.PNG)


* Result


![8r](https://user-images.githubusercontent.com/78624637/179338847-47eadb45-b5e7-4f34-98a2-3018ba148aba.PNG)

Castle lite generated the highest profit in Senegal.




# BRAND ANALYSIS

1. Within the last two years, the brand manager wants to know the top three brands consumed in the francophone countries


![9](https://user-images.githubusercontent.com/78624637/179338859-f916ae3b-595a-45c6-8502-6e314e377f5a.PNG)


* Result

![9r](https://user-images.githubusercontent.com/78624637/179338868-b57dcf18-5e1f-4e20-b21d-433f515fb61e.PNG)

* Budweiser, grand malt and trophy were the top 3 brand


2. Find out the top two choice of consumer brands in Ghana

![10](https://user-images.githubusercontent.com/78624637/179338878-07d4cb54-05b9-4922-8161-e75e7f5d8531.PNG)

* Result


![10r](https://user-images.githubusercontent.com/78624637/179338884-b3ab0140-07b8-4059-8f2a-f76677d56724.PNG)

* hero and beta malt were the top choices made in Ghana.


3. Find out the details of beers consumed in the past three years in the most oil reached country in West Africa.

* Nigeria the the most oil producting country in west Africa

![11](https://user-images.githubusercontent.com/78624637/179338892-baab2237-f802-46fd-86bf-d3a634daccdf.PNG)

* Result


![11r](https://user-images.githubusercontent.com/78624637/179338894-88b04d31-8d2d-486d-8100-702c1d940fbc.PNG)

* Budweiser is the most consumed  beer in Nigeria followed by eagle lager and hero



4. Favorites malt brand in Anglophone region between 2018 and 2019

![12](https://user-images.githubusercontent.com/78624637/179338899-0410f00e-5a15-4d20-b59b-30f369dfeaf6.PNG)

* Result


![12r](https://user-images.githubusercontent.com/78624637/179338906-dc606b10-ae4e-423f-bb9b-8b920bc97b12.PNG)

* grand malt is the most consumed malt in Anglophone between 2018 and 2019.

5. Which brands sold the highest in 2019 in Nigeria?

![13](https://user-images.githubusercontent.com/78624637/179338932-245e147a-ea22-4dc5-9018-b0d3fd6bbe33.PNG)

* Result 

![13r](https://user-images.githubusercontent.com/78624637/179338941-84e7e608-19ce-4d84-ae5b-7114babe7de2.PNG)


* Hero sold a total of 9622 in Nigeria in the year 2019 making the the most consumeed brand.




6. Favorites brand in South_South region in Nigeria

![14](https://user-images.githubusercontent.com/78624637/179338949-01efec54-039f-4286-b177-084b23bf7641.PNG)

* Result  


![14r](https://user-images.githubusercontent.com/78624637/179338951-c775f508-dd3d-4c37-b174-e936d9424561.PNG)

* eagle lager is the most consumed brand in south south region in Nigeria.


7. Bear consumption in Nigeria

![15](https://user-images.githubusercontent.com/78624637/179338959-15176e39-6e73-4d94-a2a3-2966d0e3bbcd.PNG)

* Result

![15r](https://user-images.githubusercontent.com/78624637/179338971-580c14ae-9606-42ec-aca7-985c69b46a46.PNG)


8. Level of consumption of Budweiser in the regions in Nigeria

![16](https://user-images.githubusercontent.com/78624637/179338975-bbb6cf09-11ee-4433-8e4f-76d5ea3ca0de.PNG)

* Result

![16r](https://user-images.githubusercontent.com/78624637/179338984-f19f28a9-190b-4932-9617-5fd745fb0484.PNG)

* 129260 quantity of beer was consumed in Nigerai 


9. Level of consumption of Budweiser in the regions in Nigeria in 2019 (Decision on Promo)

![17](https://user-images.githubusercontent.com/78624637/179338988-1867b3c9-ce59-447f-9642-16de58e42d39.PNG)

* Result


![17r](https://user-images.githubusercontent.com/78624637/179338994-1f326301-0ae6-4f07-b1f7-03fed1916de6.PNG)

* West 4620 followed by north central 4498


# COUNTRIES ANALYSIS

1. Country with the highest consumption of beer.

![18](https://user-images.githubusercontent.com/78624637/179374129-7e9fa8d4-1784-49c1-b8ff-e98c5bf86fcb.PNG)


* Result


![18r](https://user-images.githubusercontent.com/78624637/179374132-d7617f65-b71d-432b-a8cd-a4eb4d0fce56.PNG)

* Senegal consumed a total of 103901 beer followed by Nigeria 103578.


2. Highest sales personnel of Budweiser in Senegal

![19](https://user-images.githubusercontent.com/78624637/179374139-6c0a108d-c1e3-4784-8268-fe936a0eaba3.PNG)


* Result

![19r](https://user-images.githubusercontent.com/78624637/179374143-00ffb5a2-2e26-4e0a-9dee-4d0cf9af58c7.PNG)



3. Country with the highest profit of the fourth quarter in 2019


![20](https://user-images.githubusercontent.com/78624637/179374286-05f64589-2d6c-4ce7-8a4f-852d8a87101a.PNG)


+ Result


![20r](https://user-images.githubusercontent.com/78624637/179374149-edbec5f4-034e-490a-a36f-14171fc5e795.PNG)
