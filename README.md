# 
# Professional Portfolio - Samson CHAN



> **This profolio serves the purpose of showcasing my ability to go through the whole data science project workflow from data gathering, data Pre-processing and Cleaning, Exploratory Data Analytics to Training and Testing of ML model.**

**Project Title :**

**Study of Awarded Japanese Restaurant Behavior in Hong Kong**
**-Seeking for Attributes or Tangible Characteristic of a Successful Japanese Restaurant"**



**_This data analytics project was broken down into 4 notebooks:_**
1. Introduction and Web scraping.ipynb
2. Data Cleaning and Visual Informatics.ipynb
3. Dimensions Reduction by PCA and Classification with KNN Clustering.ipynb
4. Classification with Decision Tree.ipynb

**_Methodology and Analytical Tools Use for each stages of the project:_**

**a. Data Gathering through Web Crawling and Parsing**

Python code using BeautifulSoup and request library was developed to crawl and parse the information such as the location, number of good reviews and ratio of positive to negative review, genres of all the Japanese restaurants in Hong Kong from the most prevalent food review platform "openrice.com".

**b. Data-Preprocesssing and Cleaning, Exploratory Data Analytics**

Data cleaning was then conducted from the data crawled from the website with the use of panda and regex libraries. Hence, various graphical illustrations including histogram and relational plot would be adopted to visualise the distribution of different locations , price range and type of japanes restaurant, as well as inspecting any visable relationship between the data between conducting data analysis.

**c. Training and Testing of ML Model : Clustering and Classification**

The number of net positive reviews, bookmarks and the price range are plotted on a 2D graph by dimensionality reduction using PCA, followed by an unsupervised machine learning framework - knn clustering method to check whether the awarded restaurant can be identified with the grouping on the PCA graph.

**d. Training and Testing of ML Model : Decision Tree**

With the result from clustering, the dataset of restaurants is partitioned into two groups, namely “Awarded" and ”Normal”. The area and food type data of the restaurants were used as the attribute for the leaf node and develop a decision tree which can help estimating whether it is a restaurant with higher chance of getting awarded.
