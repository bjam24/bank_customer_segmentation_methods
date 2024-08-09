# Bank Customer Segmentation Methods
![image](https://github.com/user-attachments/assets/730df1ec-1882-46ab-962e-ed8ce2d38c9c)
Yes, after many attempts, I created this picture using Generative AI. ;)
## Description
This project focuses on **Clustering Bank Customers** using various methods available in the **scikit-learn** library. My goal was to gain insights 
into the nature of clustering methods and learn how to use **scikit-learn** to implement these techniques in practical problems. A relevant 
business sector for this application is Finance and Banking, where understanding different customer segments is crucial for the survival 
of any institution providing financial services. This project was also created for a **Kaggle** challenge called **Credit Card Dataset for Clustering**.
The link to this event can be found in the repository description.

# Table of Contents
* [1. Introduction](#chapter1)
* [2. Used Libraries](#chapter2)
* [3. Data in the Project](#chapter3)
    * [3.1 Description of Variables](#section_3_1)
    * [3.2 Reading the Dataset](#section_3_2)
    * [3.3 Data Preprocessing](#section_3_3)
        * [3.3.1 Checking Data Types of Variables](#sub_section_3_3_1)
        * [3.3.2 Searching for Duplicates](#sub_section_3_3_2)
        * [3.3.3 Missing Values Calculation and Removal](#sub_section_3_3_3)
        * [3.3.4 Renaming Columns](#sub_section_3_3_4)
        * [3.3.5 Handling Inconsistent Data](#sub_section_3_3_5)
        * [3.3.6 Feature Engineering](#sub_section_3_3_6)
        * [3.3.7 Data Cleaning](#sub_section_3_3_7)
* [4. Exploratory Data Analysis (EDA)](#chapter4)
    * [4.1 Statistics Summary](#section_4_1)
    * [4.2 Univariate Analysis](#section_4_2)
* [5. Data Transformation](#chapter5)
    * [5.1 Handling Skewness](#section_5_1)
        * [5.1.1 Quantile Transformation](#sub_section_5_1_1)
        * [5.1.2 Yeo-Johnson Transformation](#sub_section_5_1_2)
    * [5.2 Data Scaling](#section_5_2)
* [6. Data Reduction](#chapter6)
    * [6.1 Searching Highly Correlated Variables](#section_6_1)
    * [6.2 Principal Component Analysis (PCA)](#section_6_2)
* [7. Clustering methods](#chapter7)
    * [7.1 K-Means](#section_7_1)
        * [7.1.1 Silhouette Score Plot](#sub_section_7_1_1)
        * [7.1.2 Silhouette Diagram](#sub_section_7_1_2)
        * [7.1.3 Algorithm](#sub_section_7_1_3)  
    * [7.2 DBSCAN](#section_7_2)
        * [7.2.1 k-NN Distance Plot](#sub_section_7_2_1)
        * [7.2.2 Searching optimal min_samples](#sub_section_7_2_2)
        * [7.2.3 Algorithm](#sub_section_7_2_3)
    * [7.3 Agglomerative Clustering](#section_7_3)
        * [7.3.1 Denrogram](#sub_section_7_3_1)
        * [7.3.2 Algorithm](#sub_section_7_3_2)
    * [7.4 Affinity Propagation](#section_7_4)
    * [7.5 Spectral Clustering](#section_7_5)
        * [7.5.1 Silhouette Score Plot](#sub_section_7_5_1)
        * [7.5.2 Algorithm](#sub_section_7_5_2)
    * [7.6 Gaussian Mixture Model](#section_7_6)
        * [7.6.1 BIC / AIC Criterion](#sub_section_7_6_1)
        * [7.6.2 Algorithm](#sub_section_7_6_2)
* [8. Summary](#chapter8)

## Installation
To run this notebook, you'll need to have Jupyter Notebook and an Anaconda environment set up on your system.

#### 1. Clone the repository <br>
Open your terminal or command prompt and run: <br>
```bash
git clone https://github.com/bjam24/bank_customer_segmentation_methods.git
cd bank_customer_segmentation_methods
```
#### 2. Create and activate a new Anaconda environment <br>
```bash
conda create --name myenv python=3.8
conda activate myenv
```
#### 3. Install required packages <br>
```bash
pip install -r requirements.txt
```
#### 4. Launch Jupyter Notebook
```bash
jupyter notebook
```
#### 5. Navigate to the notebook and run it

## Technology stack
- Python programming language
- Jupyter Notebook

## Data source
- Kaggle: Your Machine Learning and Data Science Community https://www.kaggle.com/datasets/arjunbhasin2013/ccdata?resource=download
