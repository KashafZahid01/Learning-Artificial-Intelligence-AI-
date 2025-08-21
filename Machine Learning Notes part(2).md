# **Main Types of Machine Learning:**

## **1. Supervised Machine Learning:**

*"In supervised learning, the machine learns from labeled data (input features + known output/target)."*



* **You train the model with examples (X → Y).**
* **After training, the model can predict outcomes for unseen data.**

##### 

##### **Examples:**

* Spam detection (Email → Spam/Not Spam)
* Predicting house prices (Features → Price)
* Disease diagnosis (Symptoms → Disease/No disease)





#### **Process of Supervised Learning:**

1. Collect data → e.g., patient medical records.
2. Prepare data → clean, handle missing values, encode categorical variables, scale if needed.
3. Split into train \& test → usually 70-80% training, 20-30% testing.
4. Train the model → feed it training data (X\_train, y\_train).
5. Evaluate the model → test on unseen data (X\_test, y\_test) to see accuracy.
6. Predict → use trained model on real-world data.





### **Types of Supervised Learning:**



1. #### **Regression Algorithms:**

* *Regression is a supervised learning technique where the goal is to predict a continuous numeric value.*
* *The model learns the relationship between independent variables (X) and a dependent variable (Y).*



###### **Examples:**

* Predicting house prices.
* Predicting stock market value.
* Predicting temperature.
* Predicting patient’s blood pressure based on age, weight, etc.



##### **Types of Regression Algorithms:**

1. Linear Regression → *simple straight-line relation.*
2. Polynomial Regression → *curves/non-linear.*
3. Decision Tree Regression → *Used to predict continuous values by splitting data into regions based on feature thresholds.*
4. Random Forest Regression → *Used to improve prediction accuracy by averaging results from multiple decision trees.*
5. Support Vector Regression → *Used to predict continuous values while keeping predictions within a defined error margin (robust to outliers).*





#### **2. Classification Algorithms:**

*Classification Algorithms are a group of supervised machine learning algorithms used when the target (dependent variable) is categorical (discrete values) instead of continuous numbers.*



###### **Examples:**

* Email filtering → Spam / Not Spam.
* Medical diagnosis → Malignant / Benign tumor.
* Sentiment analysis → Positive / Negative / Neutral.
* Handwritten digit recognition → Digits 0–9.

##### 

##### **Types of Classification Algorithms:**

1. Logistic Regression → *For simple, linear classification problems.*
2. Neural Networks (Deep Learning) → *Complex data like images, text.*
3. K-Nearest Neighbors (KNN) → *Small datasets, pattern-based grouping.*
4. Decision Trees → *Interpretable, rule-based tabular data.*
5. Random Forest → *Robust predictions on tabular data.*
6. Support Vector Machine (SVM) → *Clear margin, high-dimensional data.*
7. Naive Bayes → *Text classification, spam detection.*





#### **Advantages of Supervised Learning:**

* Predicts outcomes with high accuracy if trained well.
* Easy to understand and evaluate.
* Good for classification and regression problems.

#### 

#### **Disadvantages of Supervised Learning:**

* Requires labeled data, which is expensive and time-consuming.
* Not effective if unseen data differs a lot from training data.
* Training can be computationally expensive for large datasets.







## **2. Unsupervised Machine Learning:**

* *In unsupervised learning, the machine learns from unlabeled data (only input features, no target/output).*
* *The goal is to find patterns, groups, or hidden structures in the data.*



##### <b>Examples:</b>

* Customer segmentation in marketing
* Grouping similar news articles
* Market basket analysis (people who buy bread often buy butter)



#### 

#### **Process of Unsupervised Learning:**

1. Data Collection → Gather data without labels.
2. Data Preprocessing → Handle missing values, normalize, scale data.
3. Model Selection → Choose algorithm (Clustering, Association, PCA, etc.).
4. Training → Feed input features (X) → model groups or reduces dimensions.
5. Pattern Discovery → Algorithm finds structure: 

* Groups (clusters)
* Rules (associations)
* Reduced features (PCA)

6\. Evaluation → Use metrics like silhouette score, inertia (for clustering) or interpret rules.

7\. Application → Use discovered groups/patterns in business or research.





### **Types of Unsupervised Learning:**

1. #### **Clustering Algorithms:**

* *Clustering algorithms group similar data points together based on some measure of similarity (like distance).*
* *Unlike classification, there are no predefined labels — the algorithm discovers the groups by itself.*



###### <b>Example:</b>

* Grouping customers into "high spenders," "average buyers," and "budget customers" without telling the algorithm these labels beforehand.





##### **Types of Clustering Algorithms:**

1. K-Means Clustering → *Groups by nearest centroid distance.*
2. Hierarchical Clustering → *Builds tree of nested clusters.*
3. DBSCAN → *Groups dense points, ignores noise.*
4. Mean-Shift Clustering → *Shifts centroids toward dense regions.*
5. Gaussian Mixture Models (GMM) → *Probabilistic clustering with soft membership.*





#### **2. Association Rule Learning (ARL):**

* Association Rule Learning is an unsupervised machine learning technique used to discover interesting relationships, correlations, or patterns among items in large datasets.
* It does not predict a target variable (like classification or regression), but instead finds “if-then” rules within data.



###### **Example:**

(Market Basket Analysis) In a supermarket dataset

If a customer buys bread, they are likely to buy butter.





##### **Types of Association Rule Learning:**

1. Apriori Algorithm → *Stepwise frequent itemset rule mining.*
2. Eclat Algorithm → *Uses set intersections for efficiency.*
3. FP-Growth Algorithm → *Tree-based fast frequent pattern mining.*

#### 

#### <b>Advantages of Unsupervised Learning:</b>

* Works with unlabeled data (cheaper, widely available).
* Helps discover hidden patterns/relationships.
* Useful for exploratory data analysis.





#### **Disadvantages of Unsupervised Learning:**

* Harder to evaluate results (no labels to compare).
* May produce meaningless clusters if data is noisy.
* Algorithms can be complex and less interpretable.







