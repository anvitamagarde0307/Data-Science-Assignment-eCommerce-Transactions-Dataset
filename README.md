# Data-Science-Assignment-eCommerce-Transactions-Dataset

This repository contains the deliverables for the Data Science Intern assignment, focusing on analyzing eCommerce transaction data. The assignment is divided into three key tasks: Exploratory Data Analysis (EDA), Lookalike Model development, and Customer Segmentation using clustering techniques. Each task aims to derive insights and provide actionable recommendations for business improvement.

---

## Overview of the Assignment

The eCommerce Transactions dataset consists of three files:
- **Customers.csv**: Contains customer profiles, including ID, name, region, and signup date.
- **Products.csv**: Lists product details such as ID, name, category, and price.
- **Transactions.csv**: Contains transaction data, including transaction ID, customer ID, product ID, date, quantity, and total value.

### Objectives:
1. Perform EDA to uncover insights about customers, products, and sales trends.
2. Develop a Lookalike Model to identify similar customers based on profile and transaction data.
3. Use clustering techniques for customer segmentation and derive actionable insights.

---

## Task Descriptions

### 1. Exploratory Data Analysis (EDA)
- **Objective**: Analyze the dataset to uncover key business insights, such as customer distribution, sales trends, and top-performing products.
- **Deliverables**:
  - `Anvita_Magarde_EDA.ipynb`: Jupyter Notebook containing the EDA process.
  - `Anvita_Magarde_EDA.pdf`: PDF report summarizing insights (maximum 500 words).

### 2. Lookalike Model
- **Objective**: Build a model to recommend the top 3 most similar customers for a given customer based on their profile and transaction history.
- **Deliverables**:
  - `Anvita_Magarde_Lookalike.ipynb`: Notebook explaining the model development.
  - `Anvita_Magarde_Lookalike.csv`: CSV file containing lookalike recommendations and similarity scores.

### 3. Customer Segmentation (Clustering)
- **Objective**: Use clustering algorithms to group customers into segments based on profile and transaction data. Evaluate clusters using metrics like the Davies-Bouldin Index.
- **Deliverables**:
  - `Anvita_Magarde_Clustering.ipynb`: Notebook containing clustering analysis and visualization.
  - `Anvita_Magarde_Clustering.pdf`: PDF report summarizing clustering results.

---

## Instructions to Run Each Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/eCommerce-Transactions-Analysis.git
   cd eCommerce-Transactions-Analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and execute the Jupyter Notebooks:
   ```bash
   jupyter notebook
   ```

4. Run each notebook in the following order:
   - `Anvita_Magarde_EDA.ipynb`
   - `Anvita_Magarde_Lookalike.ipynb`
   - `Anvita_Magarde_Clustering.ipynb`

5. Review the generated outputs in the `Outputs` folder.

---

## Prerequisites and Dependencies

- **Python 3.8+**
- **Libraries**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - jupyter
