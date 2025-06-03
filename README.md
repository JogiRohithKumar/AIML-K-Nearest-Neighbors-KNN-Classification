# AIML-K-Nearest-Neighbors-KNN-Classification

This project dives into the world of **K-Nearest Neighbors (KNN)** to classify the famous **Iris dataset** .  
The goal? Understand KNN, find the best number of neighbors (K), and evaluate how well the model performs 🎯.

---

## 🚀 What I Did

-  Loaded and explored the Iris dataset  
-  Encoded categorical target labels into numeric form  
-  Normalized feature data to make distance calculations fair  
-  Split data into training and testing sets  
-  Trained KNN models with different values of K (1 to 15)  
-  Evaluated model accuracy for each K on the test set  
-  Selected the best K based on highest accuracy  
-  Generated confusion matrix and classification report for the final model  
-  Visualized decision boundaries using two key features  

---

## 🧹 Data Preprocessing

-  Label encoded the target variable (`Species`)  
-  Scaled features using StandardScaler for normalization  

---

## 🤖 Model Training and Tuning

-  Used `KNeighborsClassifier` from **scikit-learn**  
-  Experimented with K values from 1 to 15  
-  Trained and tested models on training and testing data  

---

## 📊 Evaluation Results

-  Plotted accuracy vs. K to find the optimal number of neighbors  
-  Produced confusion matrix and detailed classification report  
-  Visualized decision boundaries to understand how the model separates classes  

---

## 🧰 Tools Used

-  Python 3.x  
-  Pandas for data manipulation  
-  scikit-learn for machine learning and evaluation  
-  Matplotlib for data visualization
