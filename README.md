# PROJECT GEVPRO (H&M DATASET) 
RUG Advanced Programming Project


# How to run / install?
To run the file go to a new folder and pull this git repo. Afterwards use the following commands to install requirements: 

		pip install requirements.txt

   

Afterwards start up a jupyter notebook

## Research question
We try to answer the following main research question:“Can we use the H&M dataset to explore data about its latest fashion trends and customer base?” This main research question is devided into 3 sub categories“:

* Sales --> What is popular
* Customer base --> Who is our customer?
* Personalised Fashion reccomendation --> Can we reccomend products based on other customers

## Sales
This section will try to answer the following questions:

What are the most sold articles?
What is the most sold article?
What are the most sold types of articles?
What are the worst selling articles?
What is the least sold article?
What are the worst selling types of articles?
What color is the most popular?
What was the most succesful week in sales?
Do expensive (categories) sell better than cheaper articles?


## Customer base
In the customer section of this project we have explored the following research questions: 
* What is the most frequent age of H&M customers? 
* What is the distribution of the ages of H&M customers? W
* What is the most frequent postal code? 
* How many customers have a club membership?
* What kind of fashion news frequency is most popular with what club membership?
* How many people receive fashion news? 
* What is the spread of fashion news in contrast to club member status? 
* What is the relation between receiving fashion news and the customers age?
* 
We have expressed the data in different ways, varying from plots to tables. With this research, we try to create a better overview of the customers shopping at H&M.

# Personalised Fashion recommendation
In this chapter we will be using an item based collaborative filtering approach to reccomending items to users. The item reccomendations can be used to reccomend other items to users when they are shopping for products. The main idea is to find products that are frequently bought together.

We first start by reducing the dataset even more. The current appoach of using cosine similarity could not be used on the intire dataset since the matrix would become to large to fit into memory. We reduced the dataset to only contain data after 09/01/2020 and selected the first 20 000 items that users bought in h&m stores. This does probably impact accuracy, since a lot of previous transactional data is not taken into account.  
