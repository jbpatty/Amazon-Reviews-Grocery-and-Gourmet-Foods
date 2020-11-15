Metis Data Science Bootcamp Project 4

Project Title: Amazon Reviews: Grocery and Gourmet Foods

On project two I analyzed consumer oriented food products that were imported to Central America from the US. For this project, I am continuing down the path of retail foods, but shifting focus to grocery and gourmet food reviews to better understand:

	- what food products and categories people are talking about
	- are they talking negatively or positively about these products and categories, and
	- what exactly are they saying 

I collected my data from the University of California San Diego’s data science repository. This dataset had over five million Amazon grocery and gourmet reviews of which I pulled in a million before cleaning. For Preprocessing, I analyzed my data using both CountVectorization and TFIDF, with CountVectorization providing better results. For Topic Modeling, I started with NMF to find my topics and then dug deeper into them using Spacy. For data visualizations, I used Tableau.

TOPIC 1 - CHOCOLATE  
Topic one is ‘chocolate’ some of the adjectives used to describe this topic were sweet, bitter, rich, sugary, dark, and white

TOPIC 2 - SHIPPING 
My second topic is “shipping” which has descriptive words such as arrived, service, fast, works, and time 

TOPIC 3 - STORE 
The third topic is “store” and it included words such as Amazon, order, shop, and product

TOPIC 4 - TEA
My second to last topic is “tea”. The hot beverage had the following descriptors: leaves, black, steep, and aromatic

TOPIC 5 - COFFEE 
My fifth and final topic is “coffee” which had the following identifiers:  cup, Keurig, and morning as well as the adjectives: smooth, bold, strong, roast, and decaf  

These features created in topic modeling were used along with other product information in Tableau.

### Files
amazon_modeling_final.ipynb shows the use of TF-IDF and NMF topic modeling to break down and analyze Amazon reviews for Grocery and Gourmet Foods.
