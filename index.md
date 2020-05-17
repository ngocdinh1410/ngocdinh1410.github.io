## NGOC (JANE) DINH'S PORTFOLIO
---

I am currently a Masters in Business Analytics Student at Fordham University. If you're visiting this page you're welcome to look at my work!


---
## ABOUT ME
---


*Hi,*


*I am a student interested in Business Analytics. I came from a Finance job where I worked with various outdated databases that stored a lot of valuable data. I was frustrated with how little there has been done to extract the most out of customer data, but at the same time I was not technical enough to work on any higher-level analytics project. I made the transition to Business Analytics through enrolling at Fordham University. While I've only been studying for a year in Analytics, through my challenging learning curve I have explored many areas of analytics. I created this page to introduce some of the works that I'm proud of in the past two semesters. I had a tough learning curve as I did not know much in R or Python.  By the end of the first semester, I was entrusted by three professors/ faculty to work with them on important research in data visualization and web analytics.*
*If you are interested in learning more about me, shoot me a message at ngocdinh1410@gmail.com or on LinkedIn! You can contact me if you like any of my projects or have any interesting ideas you want my collaboration!*

---
## BIG DATA PROJECTS
---

### Recommendation Systems:

[Movielens recommendation system](https://github.com/ngocdinh1410/Movie-Recommendation-System)


[![](https://img.shields.io/badge/Spark-Big%20Data-red)](https://github.com/ngocdinh1410/Movie-Recommendation-System)


I used the data from movielens dataset and created two recommendation system: popularity-based and user-based collaborative filtering. The CF model was done with ALS Pyspark. 


[Million song recommendation system](https://github.com/ngocdinh1410/Million-Song-Recommendation-System)


[![](https://img.shields.io/badge/Spark-Big%20Data-red)](https://github.com/ngocdinh1410/Million-Song-Recommendation-System)


The models are also popularity-based and user-based collaborative filtering. However, I filtered for songs with individual listen count of more than 1 time. The rationale is that if user only listen to the song once, it suggested that the user might not have liked the song.


*-more to be added-*


---
## WEB ANALYTICS
---


### Web parsing


Web parsing was one of the first thing I learned, thus these tutorials are meant to provide a starting point for beginners in Python.


[Simple web scraping with BeautifulSoup](https://github.com/ngocdinh1410/Web-parsing)


[![](https://img.shields.io/badge/Python-BeautifulSoup-yellowgreen)](https://github.com/ngocdinh1410/Web-parsing)


I attempted to scrape several pages of reviews from rotten tomatoes. Scraping done with Beautiful soup and finding the appropriate tags.


[Web scraping with Selenium](https://github.com/ngocdinh1410/Web-Scraping-with-Selenium-and-BS) 


[![](https://img.shields.io/badge/Python-BeautifulSoup-yellowgreen)](https://github.com/ngocdinh1410/Web-Scraping-with-Selenium-and-BS)


I could not scrape dynamic website without some help from Selenium. The automation of selenium is of great asisstance to scraping dynamic websites.


[Web scraping + Text Analytics](https://github.com/ngocdinh1410/Web-Parsing-and-Text-Analytics-)


[![](https://img.shields.io/badge/Python-BeautifulSoup-yellowgreen)](https://github.com/ngocdinh1410/Web-Parsing-and-Text-Analytics-)


In this repository, I will go through the process of scraping rotten tomato reviews and analyze those text reviews For this project, we utilized a web parser in order to scrape data from 11 movies from the website Rotten Tomatoes. From there, we used this data to build a classifier which we then evaluated. Lastly, we performed exploratory data analysis on our data. For each of the 11 movies we scraped a total of ten pages of reviews from each movie. From this we gathered information on a total of 2,089 reviews. Our data frame consisted of the following columns: Reviewers' Name, Rating (fresh or rotten), Review and Date.

*-more to be added-*


---
## STATISICAL ANALYSIS WITH R
---


[Linear Regression Project](https://github.com/ngocdinh1410/Linear-Regression-Project) 


[![](https://img.shields.io/badge/R-regression-blue)](https://github.com/ngocdinh1410/Linear-Regression-Project)


What we seek to explore with this dataset: Can we predict a movie’s popularity based on type of movie, genre, runtime, imdb rating, imdb number of votes, critics rating, critics score, audience rating, Oscar awards obtained (actor, actress, director and picture)? We hope to find a model with good predicting power to predict the IMDB rate of a movie.


[Exploring BRFSS Data](https://github.com/ngocdinh1410/Exploring-BRFSS-Data)

[![](https://img.shields.io/badge/R-regression-blue)](https://github.com/ngocdinh1410/Exploring-BRFSS-Data)


The Behavioral Risk Factor Surveillance System (BRFSS) is the nation's premier system of health-related telephone surveys that collect state data about U.S. residents regarding their health-related risk behaviors, chronic health conditions, and use of preventive services. We use this dataset to explore correlation between certain risk factors


[March Madness Prediction Competition](https://github.com/ngocdinh1410/March-Madness-2020)


[![](https://img.shields.io/badge/R-regression-blue)](https://github.com/ngocdinh1410/March-Madness-2020)


![alt text](https://i.imgur.com/q7zxeiLl.png)


<li>Logistic regression</li>
<li>Random forest</li>
<li>Linear discriminant analysis (LDA)</li>
<li>Quadratic discriminant analysis (QDA)</li>
<li>Support vector machine (SVM)</li>


**Model Result:**


![alt text](https://i.imgur.com/90B0VFq.png) 


[Housing Price Analysis:](https://github.com/ngocdinh1410/Housing-Price-Prediction) 


[![](https://img.shields.io/badge/R-regression-blue)](https://github.com/ngocdinh1410/Housing-Price-Prediction)


<li>I am trying to predict housing price based on historical information on the house.</li>
<li>The housing market has so much information. For the average buyer/seller, it can be hard to quantify those housing data into “How much is this house worth?”</li>
<li>With data on historical sale of houses, we hope to build a model that can predict the Sale Price of a house based on the house’s quality and characteristics.</li>

**Conclusion:**


<li>Linear regression model without outliers is our robust model.</li>
<li>Kitchen quality, height of the basement, and quality of material on the exterior are prominent variables that contribute to the difference of sale price.</li>


*-more to be added-*


---
## TEXT ANALYTICS
---


[Fashion Text Analytics](https://github.com/ngocdinh1410/Fashion-Text-Analytics) 

[![](https://img.shields.io/badge/Python-NLTK-yellow)](https://github.com/ngocdinh1410/Fashion-Text-Analytics)


The input dataset is a sample of fashion reviews crawled from Vogue during Fashion Week. The main content is the review text. The file also contains meta data such as “year”, “season”, “brand”, “author of review.” The jupyter notebook will scan through the review texts and performed some basic text analytics to identify key trends of fashion in 2016


[Disaster Tweets NLP](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP) 


[![](https://img.shields.io/badge/Python-NLTK-yellow)](https://github.com/ngocdinh1410/Disaster-Tweets-Classification-NLP)


<li>Classified the data with TF-IDF and Word2Vec to identify whether a tweet content is related to a disaster
with accuracy of over 88%.</li>
<li>Analyzed 10,000 tweets for sentiment difference between relevant and irrelevant tweets and concluded
that relevant tweets carried higher negative sentiment. Analysis processsed through NLTK Darth Vader</li>


*-more to be added-*


---
## DATABASE/SQL PROJECT
---


[Art Gallery Retional Database](https://github.com/ngocdinh1410/Art-Gallery-Tracking-System)

[![](https://img.shields.io/badge/SQL-Database-orange)](https://github.com/ngocdinh1410/Art-Gallery-Tracking-System)


Generated a relational database that fits the 3 normal form requirements and the business objectives of the art gallery.


![alt text](https://i.imgur.com/cjd3EnK.png)


*-more to be added-*


---
## OTHER PROJECTS
---


[Health Awareness SPSS Modeler Project](https://github.com/ngocdinh1410/Health-Awareness-SPSS-Modeler-Project): Analyzing CDC data on behavioral risk with SPSS Modeler with clustering, neural networks and naive bayes.


[IBM Capstone Project - NYC Neighborhood Clustering](https://github.com/ngocdinh1410/IBM-Capstone-Project): I attempted to cluster NYC neighborhood according to crime stats for my last IBM Data Science Project.


*-more to be added-*
