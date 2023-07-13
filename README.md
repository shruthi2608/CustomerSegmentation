# Customer Segmentation
Leveraging the power of machine learning and the K-means clustering algorithm, this project aims to perform customer segmentation. By analyzing patterns in customer data, such as demographics, purchase history, and behavior, we group customers into distinct segments. 

# Problem Statement
Customer Segmentation is a popular application of unsupervised learning. Using clustering, identify  segments of customers to target the potential user base. They divide customers into groups according  to common characteristics like gender, age, interests, and spending habits so they can market to each  group effectively.
Use K-means clustering and also visualize the gender and age distributions. Then analyze their annual  incomes and spending scores.To make predictions and ﬁnd the clusters of potential customers of the mall and thus ﬁnd appropriate  measures to increase the revenue of the mall is one of the prevailing applications of unsupervised  learning.
For example, a group of customers have high income but their spending score (amount spent in the  mall) is low so from the analysis we can convert such type of customers into potential customers (whose  spending score is high) by using strategies like better advertising, accepting feedback and improving the  quality of products.To identify such customers, this project analyses and forms clusters based on different criteria which are
discussed in the further sections.

# Dataset
The dataset name is Mall_Customers.csv  consists of 5 columns which are  CustomerID, Gender, Age, Annual Income  (k$), Spending Score (1-100) where  Gender is a categorical value and rest all  features are numeric.
The size of the dataset is (200, 5) which  is 200 rows and 5 columns.
<img width="454" alt="image" src="https://github.com/shruthi2608/CustomerSegmentation/assets/99944438/7f036cd2-ef75-4ad1-a992-8fec52fc1f9c">


# Methodology
1. Creating an approach to solve the given problem statement
2. Exploring the dataset and obtaining useful insight from the same
3. Cleaning the dataset by handling nan values, remove duplicate records, etc.
4. Data Visualization used to obtain important information from the data
5. Data Preprocessing is performed to make the data ready to ﬁt the model this includes feature scaling, splitting the dataset into features and labels, etc.
6. Model Building

# Implementation and Analysis
*Gender Plot Analysis:*
From the Count plot, it is observed that the number of Female customers is more  than the total number of Male customers.

*Age Plot Analysis:*
Using BarPlot, we have grouped the customers into five groups in which it is evident that more number of customers are present  at the age group of 26-35.

*Age Vs Spending Score Analysis:*
From the Age Vs Spending Score plot  we observe that customers whose  spending score is more than 65 have their  Age in the range of 15-40 years.The customers having average spending  score ie: in the range of 40-60 consists of  the age group of the range 15-75 years.

*Annual Income Vs Spending Score Analysis:*
We observe that there are 5 clusters and  can be categorized as:
High Income, High Spending Score (Top  Right Cluster)
High	Income,	Low	Spending	Score
(Bottom Right Cluster)
Average Income, Average Spending Score
(Center Cluster)
Low Income, High Spending Score (Top
Left Cluster)
Low	Income,	Low	Spending	Score
(Bottom Left Cluster)

*Clustering Analysis:*
High Income, High Spending Score (Cluster 5) - Target these  customers by sending new product alerts which would lead to an  increase in the revenue collected by the mall as they are loyal  customers.
High Income, Low Spending Score (Cluster 2) - Target these  customers by asking the feedback and advertising the product in a  better way to convert them into Cluster 5 customers.
Average Income, Average Spending Score (Cluster 1) - May or  may not target these groups of customers based on the policy of  the mall.
Low Income, High Spending Score (Cluster 4) - Can target  these set of customers by providing them with Low-cost EMI's, etc.
Low Income, Low Spending Score (Cluster 3) - Don't target  these customers since they have less income and need to save  money.






