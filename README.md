<b>***Customer segmentation using their spending personality***</b>
  
<b>Reem Ghabayen, Nidhi Bodar, Foram Shah</b>


• ***Problem description***:
Therefore, it is essential to understand the interaction patterns between online companies and their
customers is important in the face of this online market growth. To develop personalized products and
services, it is important to differentiate between different types of customers. However, we have found
that the clusters formed based on only their age, gender, location, etc. are not sufficiently discriminatory
for micro-segmentation. The problem intends to develop segments that match individual customers'
personalities based on their spending amount for each product in a particular period, whether promotion
changes their purchasing power or not and the ease of their mode to purchase the product are also being
considered.


• ***Algorithms***:
As the dataset consists of 29 features, dimensionality reduction techniques such as PCA will be used to
reduce dimensionality. Clustering algorithms such as Kmeans, Hierarchical clustering will be used to
make segments of customers. DBSCAN will be used for detecting outliers in the data. Also, We are
considering both temporal and non-sequential models, using long short-term memory (LSTM) and
feed-forward neural networks, respectively to check whether they can better learn and distinguish
segments or not. As we found that recurrent neural networks produce micro-segments whereas
feed-forward networks produce only coarse segments.


• ***Data sets***:
We will be using the company’s dataset fetched from the Kaggle website. It has 2240 rows and 29
different features which can be generalized into four categories i.e. People, Product, Promotion, Place
which further have different features. High dimensionality is present in the dataset thus the amount of
memory that it uses will be reduced. Some features have high cardinality which will be removed. Also,
we will detect missing values if there are any. Categorical features will be converted before feeding into
the models.

• ***Libraries and tools***:
The code will be executed with Jupyter notebook and Google collab(if it is needed for running algorithms
related to neural networks). Pandas and Numpy for common mathematical and data frame operations.
Sklearn library will be used for preprocessing of the data such as scaling and also for importing trained
clustering algorithms. For exploratory data analysis, to show relations between features Matplotlib, and
Seaborn will be used. For implementing neural network models, Keras and TensorFlow libraries will be
incorporated.

• ***Results***:
The project should yield different groups of customers who have similar interests falling into the same
clusters. If there are outliers, then we will detect whether they are making their cluster as it can produce
valuable insight for a company. We will also show the behavior and patterns of customers for an
individual feature and how some of the features are together affecting customers' purchases. For this
purpose, we are planning to use different clustering algorithms and compare their result using evaluation
metrics. Neural network models are expected to perform better because of their hold on detecting
complex patterns and relationships.


• ***Dataset***:
https://www.kaggle.com/code/sonalisingh1411/customer-personality-analysis-segmentation/data
