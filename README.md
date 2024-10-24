# Customer Segmentation Using K-Means Clustering

**Overview**

This project implements K-Means Clustering to group customers into distinct segments based on their Age, Annual Income, and Spending Score. This analysis helps businesses better understand customer demographics and purchasing behavior, enabling targeted marketing strategies.

**Dataset**

The dataset used in this project contains customer information, including:

* Age
* Gender
* Annual Income (in thousands)
* Spending Score (a value between 1-100)

You can access the customer dataset used in this project from the following link:

[Mall Customers Segmentation](https://www.kaggle.com/datasets/abdallahwagih/mall-customers-segmentation)

**Project Steps**

1. **Data Loading:**
   * Load the dataset and explore for missing values, basic statistics, and feature distributions (age, income, spending score).

2. **Data Visualization:**
   * Create histograms and countplots to visualize the distribution of age, income, spending score, and gender.

3. **Data Preprocessing:**
   * Standardize features using StandardScaler to improve clustering performance.

4. **K-Means Clustering:**
   * Use the Elbow Method to determine the optimal number of clusters (K).
   * Apply the K-Means algorithm to group customers into segments.

5. **Visualizations:**
   * Create distributions for Age, Annual Income, and Spending Score.
   * Generate an Elbow Plot to identify the optimal number of clusters.

**Technologies Used**

* Python
* pandas
* matplotlib
* seaborn
* scikit-learn

**How to Run the Project**

1. **Clone this repository**
   ```bash
   git clone https://github.com/yourusername/customer-segmentation-kmeans.git

2. **Install required libraries:**
   ```bash
   pip install pandas matplotlib seaborn scikit-learn
   
3. **Run the Python script:**

**Conclusion**

This project clusters customers into meaningful segments, providing valuable insights for targeted marketing strategies based on demographics and purchasing behaviors.
   
