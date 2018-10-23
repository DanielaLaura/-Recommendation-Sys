## Recommendation-Sys - Work in Progress

One common characteristic of Pandora, Netflix, Youtube, Amazon is that they personalize what each user experience based 
on their or/and others user preferences. This is what recommendation systems are about and they improve upon this approach by 
adding the product characteristics in their algorithms. Recommendation systems have become increasingly more popular in recent 
years as a way for companies to provide better service and increase profit. In a broad sense, recommendation systems predict the
level of interest a user has in a new item.

### Recommender System
- Popularity Based Recommender Make the same recommendation to every user, based on the popularity of an item.
- Content-Based Recommender focus on properties of items. Similarity of items is determined by measuring the similarity in their properties

### Data Pipeline Breakdown

The data is  scraped from Metacritic website with Selenium and BeautifulSoup can be transformed into two matrices. One matrix is completely about fragrance game, which includes these features:

•	Game Title

•	Platform

•	Genre(s)

•	Developer/Publisher

•	Number of Players allowed in the game

Another matrix is composed of both user and game information, which includes these features:

•	Game Title

•	Platform

•	Username

•	User Score

•	Review Text

### Tools Consider Using

•	Data processing and EDA: Pandas, Numpy, Matplotlib, Seaborn

•	Machine learning and stats: Scikit-learn, Scipy, PySpark

•	Web Scaping: BeautifulSoup, Selenium

•	Data Storage: pymongo, MongoDB

•	AWS: S3, EC2 

•	Web app: HTML, CSS, Flask

