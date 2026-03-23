Customer Personality Analysis & Segmentation
📌 Project Overview
This project focuses on Customer Personality Analysis, which is a detailed analysis of a company’s ideal customers. It helps a business to better understand its customers and makes it easier for them to modify products according to the specific needs, behaviors, and concerns of different types of customers.

Using Unsupervised Machine Learning, I segmented a customer dataset into 5 distinct groups based on their demographics, purchasing behavior, and engagement with marketing campaigns.

🛠️ Tech Stack & Libraries
Language: Python

Environment: Google Colab / Jupyter Notebook

Data Manipulation: Pandas, NumPy

Visualization: Seaborn, Matplotlib

Machine Learning: Scikit-Learn (KMeans, t-SNE, LabelEncoder, StandardScaler)

🚀 Key Features & Workflow
1. Data Cleaning & Preprocessing: * Handled missing values and removed redundant constant features.

     Converted date strings into numerical features (Day, Month, Year).

     Transformed categorical variables using Label Encoding.

2. Exploratory Data Analysis (EDA):  Analyzed distributions of education, marital status, and campaign responses.

     Utilized a Correlation Heatmap to detect and manage multicollinearity.
3. Dimensionality Reduction:
     Implemented t-SNE to project high-dimensional data into a 2D plane, allowing for visual identification of natural clusters.
4.Clustering Model:
     Used the Elbow Method (WCSS) to determine the optimal number of clusters ($K=5$).Applied K-Means++ initialization for stable and faster convergence.
5. Cluster Visualization: Visualized final segments on the t-SNE components to verify cluster separation.

📈 Results & Insights
The model successfully partitioned the customers into 5 groups. These segments allow the marketing team to:

Identify high-spending "VIP" customers.

Target "Deal Seekers" with specific discounts.

Re-engage "Dormant" customers who haven't purchased recently.

📂 How to Run
1. Clone this repository.

2. Ensure you have the data.csv file in the root directory.

3. Install dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn

4. Run the Customer_Segmentation.ipynb notebook.

🎓 Author
Satyajeet M.Tech in Computational and Data Sciences Indian Institute of Science (IISc), Bangalore

