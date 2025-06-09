📊 Customer Behavior Analysis using Clustering
This project analyzes customer personality and behavioral patterns using unsupervised machine learning techniques, particularly clustering algorithms. The goal is to segment customers based on their purchasing habits and demographic attributes to derive actionable business insights.

📁 Dataset
The dataset is sourced from Kaggle: Customer Personality Analysis, and contains:

Demographic data (age, income, marital status)

Spending habits across product categories

Campaign acceptance and web usage data

🚀 Features
Data preprocessing and cleaning

Feature scaling using StandardScaler

Customer segmentation using KMeans

Determining optimal number of clusters using the Silhouette Score

Visualization with Seaborn and Matplotlib

🛠️ Tools & Libraries
Python 3.x

Pandas, NumPy

Scikit-learn

Seaborn, Matplotlib

SciPy

KaggleHub

📦 Installation
Clone this repository and install the required packages:

bash
Copy
Edit
git clone https://github.com/yourusername/customer-behavior-clustering.git
cd customer-behavior-clustering
pip install -r requirements.txt
🧠 How it works
Dataset is downloaded via kagglehub.

Data is explored and cleaned.

Features are scaled for clustering.

KMeans is applied with multiple cluster sizes.

The best number of clusters is selected based on silhouette analysis.

The clusters are visualized to interpret customer groups.

📊 Output
Cluster visualizations for better understanding

Customer profiles for each segment

Insights to improve marketing and product strategy

📈 Example Visualization
Add sample plots here (e.g., customer clusters by income and spending)

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

