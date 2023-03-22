# nosql-challenge
Bootcamp - Module 12 Challenge.
This challenge is called Eat Safe, Love.
The task is to use data from the UK Food Standards Agency to analyse the ratings of food establishments so journalists can make accurate decisions about information to publish in their articles.
The NoSQL_setup.ipynb imports the database and sets it up for analysis. 
The NoSQL_analysis.ipynb queries relevant information for analysis and converts results into Pandas DataFrame. 
The data provided in the establishments.json file was imported using Terminal with mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json.



Here is an example of one of the results. This shows the number of establishments in each locality with a hygiene score of 0.


![image](https://user-images.githubusercontent.com/119769357/226799793-37ce0eb5-4a79-4340-af9b-f47f2afdd324.png)
