# **Machine Learning (ML):**





### **Introduction:**

Machine Learning is a branch of Artificial Intelligence that enables computers to learn patterns from data and make predictions or decisions without being explicitly programmed. Instead of writing rules manually, in ML we feed the machine with examples (data) and let it discover rules/patterns automatically.







### **Types of Machine Learning:**

1. **Supervised Learning.**  (Model is trained on labeled data)
2. **Unsupervised Learning.**   (Model is trained on unlabeled data; it tries to find hidden patterns.)
3. **Semi-Supervised Learning.**  (Mix of labeled and unlabeled data.)
4. **Reinforcement Learning.**  (Agent learns by interacting with an environment and receiving rewards/punishments.)





# **Supervised Machine Learning:**

***The model learns from labeled data — meaning, each input has a known correct output (label).***



### **Two Main Problem Types in Supervised Learning:**



1. #### **Regression (Output is continuous):**



* Predicting house prices, predicting temperature, estimating sales.
* Example: 
* Input: size=2000 sq ft, location="city center" 
* Output: price = $250,000.



#### **2. Classification (Output is categorical):**



* Predicting if an email is spam or not, diagnosing disease (yes/no), predicting customer churn.
* Example:
* Input: email text features
* Output: "Spam" or "Not Spam".



### **Components of Supervised Machine Learning:**

1. ##### **Labeled Data:**



* Dataset containing features (X) and labels (y).
* Example:
* Features: age, salary, education level
* Label: whether the person bought a product (yes/no).





##### **2. Hypothesis:**

* A function (or model) that maps inputs to outputs.
* Example: ​y =f(X), where 𝑓 could be a linear function, decision tree, or neural network.





##### **3. Cost Function (Loss Function):**

* Measures how far the model’s predictions are from the actual outputs.
* Goal: Minimize this function.
* Examples:
* Mean Squared Error (MSE) for regression.
* Cross-Entropy Loss for classification.





##### **4. Optimizer:**

* Algorithm to adjust model parameters to minimize the cost function.
* Examples: Gradient Descent, Adam optimizer.
* Works iteratively:
* Predict → Calculate cost → Adjust weights → Repeat.







### **Classical Machine Learning Pipeline:**

### **What is Pipeline?**

*In Machine Learning, a pipeline is like a step-by-step assembly line for building and using models, it organizes all the stages of the ML workflow into a single streamlined process.*



***raw data in → transformations \& modeling → predictions out.***



### **Why Pipelines Exist?**

In real ML projects, you rarely just “train a model” — you also need:

* Data cleaning
* Feature engineering
* Scaling or encoding
* Model training
* Testing \& deployment





* Without a pipeline, you’d have to manually repeat these steps each time new data comes in, which is slow and error-prone.
* Pipelines automate these steps so the exact same transformations happen consistently.





### **Components of a Machine Learning Pipeline:**





1. ##### **Data Collection:**

* Gather data from databases, sensors, web scraping, APIs, etc.
* The quality \& quantity of data is crucial.
* Example: Collect past sales data to predict future sales.





##### **2. Data Preprocessing:**

* Cleaning: Removing duplicates, handling missing values, correcting errors.
* Encoding categorical variables, scaling numerical features.
* Making the data suitable for the model.
* Example: Convert "Male/Female" → 0/1, normalize salaries.





##### **3. Feature Crafting:**

* Selecting important variables (features) or creating new ones from raw data.
* Example: From date of birth → calculate age.





##### **4. Modeling:**

* Choosing a suitable ML algorithm (Linear Regression, Decision Tree, Random Forest, etc.).
* Train the model using training data.





##### **5. Testing and Evaluation:**

* Evaluate performance using metrics (accuracy, precision, recall, RMSE, etc.).
* Use test data that the model has never seen before to check generalization.





##### **6. Deployment:**

* Integrate the model into an application or production environment.
* Example: A recommendation system on an e-commerce site.





| Step                       | Description                                                                   |

| -------------------------- | ----------------------------------------------------------------------------- |

| \*\*1. Data Collection\*\*     | Gather raw data from databases, APIs, sensors, etc.                           |

| \*\*2. Data Preprocessing\*\*  | Handle missing values, remove duplicates, clean text, fix formats.            |

| \*\*3. Feature Engineering\*\* | Create, transform, or select features (e.g., one-hot encoding, scaling, PCA). |

| \*\*4. Model Training\*\*      | Fit the chosen ML model to the processed data.                                |

| \*\*5. Model Evaluation\*\*    | Test the model on unseen data using metrics (accuracy, RMSE, F1-score).       |

| \*\*6. Deployment\*\*          | Make the model available for predictions in a production system.              |


