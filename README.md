# Bank Customers Clustering

## Introduction 
In today’s competitive financial landscape, understanding customer behavior is more important than ever. Banks and financial institutions gather massive amounts of transactional data from customers. This project aims to leverage this data to classify and cluster customers, enabling banks to make data-driven decisions for targeted campaigns, personalized offerings, and improved customer satisfaction.

---

## Problem Statement
Banks deal with enormous amounts of transactional data from their customers. Mass campaigns targeting all customers are costly and inefficient. The project addresses this issue by aiming to segment customers into distinct groups based on their transaction behavior and other key attributes. This segmentation will enhance the efficiency of targeting campaigns and making personalized deals or offers.

---

## Objectives
The primary goal of this project is to:
1. Identify distinct segments of credit card users based on their transaction behavior and other key attributes.
2. Leverage these segments to enable targeted marketing and improved customer engagement.
3. Provide insights that banks can use to tailor their marketing strategies and product offerings.

---

## [Dataset](https://www.kaggle.com/datasets/shivamb/bank-customer-segmentation/data)
This project involves working with raw transactional data. The dataset contains the following attributes:
- **TransactionID**: Unique Transaction ID
- **CustomerID**: Unique Customer ID
- **CustomerDOB**: Date of Birth
- **CustGender**: Gender
- **CustLocation**: Location
- **CustAccountBalance**: Account Balance
- **TransactionDate**: Transaction date
- **TransactionTime**: Transaction Time (Unix timestamp)
- **TransactionAmount (INR)**: Amount in INR
- **OwnedProducts**: Products owned by the customer

### Data Preparation Steps
- Study the shared data carefully as it is raw and at the transaction level.
- Generate and build the dataset based on the problem understanding.
- Add as many features as possible and validate their logical correctness.
- Aggregate data at the customer level to ensure uniqueness.

---

## Deliverables
The project deliverables include:
1. Performing **Exploratory Data Analysis (EDA)** to understand key variables and data patterns.
2. **Preprocessing** the data to handle missing, incorrect, or inconsistent values.
3. Applying suitable **unsupervised learning techniques** (e.g., clustering algorithms) to group customers based on their features.

---

## Skills Practiced
- Dataset creation and data wrangling techniques
- Data cleaning and preprocessing
- Feature selection and scaling
- Application of clustering algorithms
- Visualization and interpretation of clustered data

---

## Steps in the Notebook
1. **Data Loading and Exploration**:
   - Load raw data and resolve issues like inconsistent columns or missing values.
   - Understand the distribution of variables and identify anomalies.

2. **Data Cleaning**:
   - Handle incorrect dates (e.g., future dates or unrealistic birth years).
   - Address missing or inconsistent gender data.

3. **Feature Engineering**:
   - Aggregate transaction-level data to customer-level data.
   - Generate meaningful features to improve clustering accuracy.

4. **Clustering**:
   - Apply clustering algorithms such as K-means or DBSCAN to group customers.
   - Analyze and interpret the resulting clusters.

5. **Visualization**:
   - Use visualizations (e.g., scatter plots, heatmaps) to interpret the clusters and patterns.

6. **Model Trials**:
   - Maintain a log of clustering trials, including hyperparameters and evaluation metrics.

---

## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/Amadoabad/Bank-Cutomers-Clustering.git
   ```
2. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore and analyze the data:
   ```bash
   jupyter notebook playground.ipynb
   ```
---
## Future Work
* Enhance the clustering model by incorporating advanced techniques like hierarchical clustering or Gaussian Mixture Models.
* Automate the recommendation system for real-time product suggestions.
* Expand the dataset to include more customer attributes for deeper insights.

---
## Acknowledgments
Thank you for exploring this project! We hope it provides valuable insights and aids in improving customer-centric banking strategies.
