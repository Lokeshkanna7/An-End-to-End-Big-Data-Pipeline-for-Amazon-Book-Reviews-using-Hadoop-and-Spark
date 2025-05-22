 # 📚 SparkShelf: An End-to-End Big Data Pipeline for Amazon Book Reviews

This project implements an end-to-end big data pipeline for analyzing Amazon book reviews using Hadoop and Apache Spark. It combines scalable storage, distributed processing, and machine learning techniques to extract insights such as sentiment trends, rating predictions, and fake review detection.

## 🚀 Project Overview

We built this pipeline as part of CSE587 - Data Intensive Computing at the University at Buffalo. The project spans two major phases:

- **Phase 1:** Data cleaning, Hadoop cluster setup via Docker, HDFS integration
- **Phase 2:** PySpark-based EDA and ML model development for classification, regression, and fake review detection

## 📊 Objectives

1. **Sentiment Analysis** – Classify reviews as positive or negative
2. **Rating Prediction** – Predict review ratings based on text
3. **Fake Review Detection** – Detect fraudulent or low-helpfulness reviews
4. **Trend Analysis** – Explore temporal patterns in review behavior
5. **Verified vs. Unverified Review Analysis**

## 🛠️ Technologies Used

- **Hadoop** for distributed storage (HDFS)
- **Apache Spark (PySpark)** for distributed computation
- **Docker & Docker Compose** for cluster deployment
- **Seaborn / Matplotlib / Pandas** for data visualization
- **ML Models**: Logistic Regression, Linear Regression, Random Forest

## 🗃️ Dataset

We used the [Amazon Books Reviews dataset](https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews) from Kaggle.

## 📁 Folder Structure

| Folder | Description |
|--------|-------------|
| `report/` | Final project PDF report |
| `data/` | Sample CSVs from the dataset |
| `notebooks/` | Jupyter Notebooks for EDA and modeling |
| `hadoop/` | Scripts and YAML for Hadoop setup via Docker |
| `scripts/` | Python scripts for ML tasks |
| `requirements.txt` | Python package dependencies |

## 🧠 Key Learnings

- Deploying a local Hadoop cluster using Docker
- Ingesting and managing data in HDFS
- Scaling ML models with PySpark MLlib
- Data preprocessing, tokenization, and feature extraction
- Evaluation metrics: Accuracy, RMSE, MAE, R²

## 👥 Authors

- **Lokesh Kanna Rajaram** ([@lrajaram@buffalo.edu](mailto:lrajaram@buffalo.edu))
- **Neha Mahesh** ([@nehamahe@buffalo.edu](mailto:nehamahe@buffalo.edu))

## 📜 License

This project is for academic purposes as part of CSE587 at University at Buffalo.

---





