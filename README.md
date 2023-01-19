# 
Professional Portfolio 
This data analytics project include 4 parts:
1. Introduction and Web scraping.ipynb
2. Data Cleaning and Visual Informatics.ipynb
3. Dimensions Reduction by PCA and Classification with KNN Clustering.ipynb
4. Classification with Decision Tree.ipynb

This profolio serves the purpose of showcasing my ability to go through the data science project workflow from data gathering, data Pre-processing and Cleaning, Exploratory Data Anayltics to Training and Testing of ML model.

The project title Study of Awarded Japanese Restaurant Behavior in Hong Kong
and Seeking for Attributes or Tangible Characteristic of a Successful Japanese Restaurant

Methodology and Analytical Tools Use for each stages of the project:

1. Data Gathering through Web Crawling and Parsing

Python code with BeautifulSoup library was developed to crawl and parse the information such as the location, number of good reviews and ratio of positive to negative review, genres of all the Japanese restaurants in Hong Kong from the most prevalent  .

2. Graphical informatics and Data Cleaning

Data cleaning would be conducted from the data crawled from the website with the use of panda and regex libraries. Hence, various graphical illustrations such as histogram and relational plot would be adopted to visualise the distribution of different locations , price range and type of japanes restaurant, as well as inspecting any visable relationship between the data between conducting data analysis.

3. Training and Testing of ML Model : Clustering and Classification

The number of net positive reviews, bookmarks and the price range are plotted on a 2D graph by dimensionality reduction using PCA, followed by knn clustering method to check whether the awarded restaurant can be identified with the grouping on the PCA graph.

4. Training and Testing of ML Model : Decision Tree

With the result from clustering, the dataset of restaurants is partitioned into two groups, namely “Awarded" and ”Normal”. The area and food type data of the restaurants were used as the attribute for the leaf node and develop a decision tree which can help estimating whether it is a restaurant with higher chance of getting awarded.
