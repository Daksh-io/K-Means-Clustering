# 📊 Customer Segmentation using K-Means Clustering

## 🧠 Project Overview

This project is about understanding customer behavior using data.

Instead of predicting churn directly, the goal is to **group similar customers together** and find patterns in their usage. This helps businesses take smarter decisions like improving retention or creating better plans.

---

## 📁 Dataset

The dataset contains telecom customer information such as:

* Call usage (day, evening, night)
* Charges
* Customer service calls
* International & voicemail plans
* Churn (whether the customer left or not)

---

## ⚙️ What I Did

### 1. Data Preprocessing

* Loaded the dataset using pandas
* Checked missing values (no major issues found)
* Converted Yes/No values into 0/1
* Removed unnecessary columns (State, Area code, Churn for clustering)

### 2. Feature Scaling

* Used StandardScaler to normalize the data
* This ensures all features contribute equally

### 3. Finding Optimal Clusters

* Used the **Elbow Method**
* Tested values of K from 1 to 10
* Selected **K = 4** as the best number of clusters

### 4. Applying K-Means

* Trained the model using K-Means
* Assigned each customer to a cluster

### 5. Visualization

* Used scatter plots to visualize clusters
* Compared features like:

  * Day minutes
  * Evening minutes

### 6. Cluster Analysis

Analyzed each cluster to understand:

* Usage behavior
* Churn patterns
* Plan adoption

---

## 🔑 Key Insights

* Some clusters have **higher churn risk**
* Loyal customers tend to use **voicemail services more**
* International plan usage is surprisingly low
* Certain customers have high usage but still churn → possible dissatisfaction

---

## 💼 Business Impact

* 🎯 Focus retention strategies on high-risk clusters
* 💰 Upsell premium services to loyal users
* 📦 Create targeted plans (like night-time or international packages)

---

## 🛠️ Tech Stack

* Python
* NumPy & Pandas
* Scikit-learn
* Matplotlib & Seaborn

---

## 🚀 How to Run

1. Open the notebook in Google Colab or Jupyter
2. Upload the dataset (`churn-bigml-20.csv`)
3. Run all cells step by step

---

## 📌 Conclusion

This project shows how unsupervised learning can be used to **discover hidden patterns in data** and turn them into real business decisions.

---

## 🙌 Author

Daksh Sharma Data Science & ML Enthusiast
