# E-commerce-customer-segmentation
A key challenge for e-commerce businesses is to analyze the trend in the market to increase their sales. The trend can be easily observed if the  companies can group the customers; based on their activity on the e- commerce site. This grouping can be done by applying different criteria like  previous orders, mostly searched brands and so on.

# Problem Statement:
Given the e-commerce data, use k-means clustering algorithm to cluster
customers with similar interest.

Dataset Information:
The data was collected from a well known e-commerce website over a
period of time based on the customer’s search profile.

### Variable Description:
| Column | Description                            |
|--------|----------------------------------------|
| Cust_ID| Unique Numbering of Customers          |
| Gender | Gender of Customer                     |
| Orders | No. of Past orders placed by the customers    |


Remaining 35 features (brands) contains the number of times
customers have searched them

Scope:

### Problem Statement – K means
#### ● Analyzing the existing customer data and getting valuable insights
about the purchase pattern
#### ● Data pre-processing including missing value treatment
#### ● Segmenting customer based on the optimum number of clusters (‘k’)
with the help of silhouette score

### Learning Outcome:
The students will get a better understanding of how the variables are
linked to each other and will be able to apply cluster analysis to business
problem such as customer segmentation.

## Steps involved to segment customers using kmeans
### 1. Importing required libraries
2. Importing data from local
3. Cleaning data involved substituting null values in Gender with original probability to contain the probability.
4. Female and Male shoppers distribution of 80.7% and 19.3% resp.
5. Average Orders made by Male and Female is almost same with ~5.5 Orders per customer
6. Average Searches per brand
7. Data has 4 categories in itself
8. Who made more searches, male or female?
9. Correlation among features is none considered
10. Top 10 valuable customers
11. Min Max Scaling for data normalisation
12. K value and Silhouette score finder
13. Fitting the model with k=4 as optimal values
14. Cluster Analysis and desired information can be drawn

###  Project explanation video tagged below
Quality is not good considering github restrictions of 10MB max file (let me know if there is another way)

https://github.com/user-attachments/assets/c92a4e25-3e3c-4ae8-bd02-6678525b060f


