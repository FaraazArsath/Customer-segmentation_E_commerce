# Project_Customer-segmentation_E_commerce
Customer Segmentation of E commerce purchase database
![Project Customer Segmentation](https://user-images.githubusercontent.com/108978683/213140611-4ae3279d-23ba-40d0-96af-43ca7a39a9d1.png) 


## Problem Statement

As an e-commerce platform, it is very important to profile your customers, dividing your clientele base into groups based on their needs and expectations. Grouping will help us come up with dedicated marketing strategies and will aid us in recommending products to different user bases. In this project, we are interested in analyzing the content of an E-commerce database that lists purchases made by ∼4000 customers over a period of one year (1/12/2010 to 9/12/2011). Based on this analysis, we would like to develop models to group the 4000 customers into different buckets. Such a model must take into account the similarity between the products purchased between the users (i.e. a user might purchase 2 different products which are very similar to each other), the spending patterns of a user, their meta information, etc.

## Minimum Requirements

The end objective of the participant is to come up with customer segmentations that take into account all the information that is presented in the dataset. The participant is expected to use NLP techniques to find similarity between the products.

## Project Summary:

In this project we used NLP (Natural Language Processing) techniques to extract frequent words in the 'Description' column of Products purchased and done Clustering text documents using k-means to obtain Product Categories.

Used Feature Extaction method TfidfVectorizer whch uses an in-memory vocabulary (a Python dict) to map the most frequent words to features indices and hence compute a word occurrence frequency (sparse) matrix. The word frequencies are then reweighted using the Inverse Document Frequency (IDF) vector collected feature-wise over the corpus. Performed dimensionality reduction using LSA (Latent semantic analysis) to this extracted features before fitting into K- means.

Finally with the Product Categories we clustered Customers based on thier purchases and spending pattern.

### EDA
![Top 10 Country by Sales](https://user-images.githubusercontent.com/108978683/213146410-899d3218-9caa-45fc-930f-d5e96312fef3.png)

![Top 15 Product Description by Sales](https://user-images.githubusercontent.com/108978683/213146618-41ec838c-eaae-42cf-98f7-f737b5d65cc3.png)

### Product Category:
![Product Categories word cloud](https://user-images.githubusercontent.com/108978683/213145748-da660108-2ae2-4c40-bbef-adaf1d7446ff.png)
#### Monthly Sales per category
![Monthly Sales - Product Category](https://user-images.githubusercontent.com/108978683/213147893-de96cb76-d3e0-45fa-be8d-93339d0de37c.png)
### Customer Cluster :
![Customer Cluster count](https://user-images.githubusercontent.com/108978683/213148244-488e76c7-b6a8-4d5a-a149-2f3e1edc59b7.png)![Customer Cluster](https://user-images.githubusercontent.com/108978683/213148406-d5bdc973-95de-41cb-9787-2665520d029a.png)


![Customer Cluster based on Product Category sales -](https://user-images.githubusercontent.com/108978683/213148811-fb5d57a5-9dc4-4aa6-98b4-1245882b4d0b.png)

