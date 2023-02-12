# Machine-Learning
Machine learning is an application of artificial intelligence that provides systems the ability to automatically learn and improve from experience without being explicitly programmed.

Machine Learning enables computers to behave like human beings by training them with the help of past experience and predicted data.

![ML](https://user-images.githubusercontent.com/112484744/218328805-2ac5dd3b-6b50-438a-80de-b57fafd5ac05.png)

### Classification of Machine Learning

Machine Learning can be classified into three types:
#### 1. Supervised Learning
#### 2. Unsupervised Learning
#### 3. Reinforcement Learning

### 1. Supervised Learning
In Supervised learning, a model is able to predict with the help of labelled dataset.

![supervised](https://user-images.githubusercontent.com/112484744/218328866-f5cfb373-c935-41b2-b01f-d5e9ab62a55c.png)

Supervised learning can be further divided into two types of problems:
#### 1. Regression: 
It is used to understand the relationship between dependent and independent variables. When the output variable is real or continuous value, we make use of classification.

#### 2. Classification:
When the output variable is categorical i.e. with two or more classes(yes/no, true/false), we make use of classification.

Below are some popular algorithms which come under supervised learning:
### Linear Regression
Linear Regression is used to identify the relationship between a dependent variable and one or more independent variables and is typically used to make predictions about future outcomes.

When there is only one independent variable and one dependent variable, it is known as simple linear regression. As the number of independent variables increases, it is referred to as multiple linear regression.

For each type of linear regression, it seeks to plot a line of best fit. However, unlike other regression models, this line is straight when plotted on a graph.

![linear R](https://user-images.githubusercontent.com/112484744/218328940-c0bc913b-2b0b-4796-9f52-4f79d048356d.png)

### Logistic Regression
While linear regression is used when dependent variables are continuous, logistical regression is selected when the dependent variable is categorical, meaning they have binary outputs, such as "true" and "false" or "yes" and "no." While both regression models seek to understand relationships between data inputs, logistic regression is mainly used to solve binary classification problems, such as spam identification.

![logistic R](https://user-images.githubusercontent.com/112484744/218328973-72bcd80f-97ad-4770-a4d9-4ed15db15b6f.png)

### K-Nearest Neighbor
![knn](https://user-images.githubusercontent.com/112484744/218329000-eebf48c2-75ee-44bb-aaad-b1efd589851c.png)

### Random Forest
![RF](https://user-images.githubusercontent.com/112484744/218329033-4ea9758d-a2fa-410f-804a-9f0cff0f51ac.png)

### Support Vector Machine (SVM) 
![svm](https://user-images.githubusercontent.com/112484744/218329062-abdbe026-5d9b-45ff-af0a-8d504d269fc7.png)

### Naive Bayes

### Advantages of Supervised Learning:
 1. With the help of supervised learning, the model can predict the output on the basis of prior experiences.

 2. In supervised learning, we can have an exact idea about the classes of objects.

 3. Supervised learning model helps us to solve various real-world problems such as fraud detection, spam filtering, etc.

### Disadvantages of Supervised Learning:
 1. Supervised learning models are not suitable for handling the complex tasks.

 2. Supervised learning cannot predict the correct output if the test data is different from the training dataset.

 3. Training required lots of computation times.

### 2. Unsupervised Learning

Unsupervised learning is a type of machine learning in which models are trained using unlabeled dataset

The goal of unsupervised learning is to find the underlying structure of dataset, group that data according to similarities, and represent that dataset in a compressed format.

![unsupervised](https://user-images.githubusercontent.com/112484744/218329130-9cfd9bd3-5acf-430f-a50c-fc53dd716a75.png)

The unsupervised learning algorithm can be further categorized into two types of problems:
#### 1. Clustering
Clustering is a method of grouping the objects into clusters such that objects with most similarities remains into a group and has less or no similarities with the objects of another group. Cluster analysis finds the commonalities between the data objects and categorizes them as per the presence and absence of those commonalities.

#### 2. Dimensionality reduction
The number of input features, variables, or columns present in a given dataset is known as dimensionality, and the process to reduce these features is called dimensionality reduction.

It is a way of converting the higher dimensions dataset into lesser dimensions dataset ensuring that it provides similar information.

There are two ways to apply the dimension reduction technique:
#### 1. Feature selection
#### 2. Feature extraction

Below is the list of some popular unsupervised learning algorithms:
#### 1. K-means clustering
![kmean](https://user-images.githubusercontent.com/112484744/218329174-65109993-efc1-4361-85f5-fd5ad8c05e2a.png)

#### 2. Hierarchal clustering
![h](https://user-images.githubusercontent.com/112484744/218329209-bf82348c-4334-4672-a5d2-677c628b7309.png)

#### 3. DBSCAN
#### 4. Principle Component Analysis

### Advantages of Unsupervised Learning
 1. Unsupervised learning is used for more complex tasks as compared to supervised learning because, in unsupervised learning, we don't have labeled input data.

 2. Unsupervised learning is preferable as it is easy to get unlabeled data in comparison to labeled data.

 ### Disadvantage of Unsupervised Learning
 Unsupervised learning is intrinsically more difficult than supervised learning as it does not have corresponding output.

 ### 3. Reinforcement
