# Network Traffic Data Analysis

## 📖 Overview
This project performs data analysis on network traffic datasets to understand flow behavior and detect potential security threats. The goal is to explore, clean, and visualize network data for further use in intrusion detection systems.

---

## 🎯 Objectives
- Understand network traffic features
- Clean and preprocess raw dataset
- Perform exploratory data analysis (EDA)
- Identify patterns between normal and attack traffic
- Prepare dataset for machine learning models

---

## 📊 Dataset Description
The dataset contains network flow features such as:
- Destination Port
- Flow Duration
- Total Forward/Backward Packets
- Packet Length Statistics
- Flow Bytes/s and Packets/s
- Label (Benign or Attack)

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

---

## ⚙️ Project Workflow

### 1. Data Understanding
- Load dataset
- Explore structure using `.info()`, `.head()`, `.describe()`

### 2. Data Preparation
- Select relevant columns
- Handle missing values
- Remove duplicates
- Rename labels for clarity

### 3. Exploratory Data Analysis (EDA)
- Statistical summaries
- Distribution plots
- Boxplots and comparisons
- Feature relationship analysis

---

## 🧹 Data Cleaning Steps
- Checked for null values
- Removed missing data
- Identified duplicate records
- Cleaned and structured dataset for analysis

---

## 📈 Key Insights
- Differences observed between normal and attack traffic
- Certain features show strong variation across labels
- Clean data improves analysis accuracy

---

## 🚀 Future Work
- Apply machine learning models for intrusion detection
- Feature selection and engineering
- Model evaluation and optimization

---

## 📂 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/network-traffic-data-analysis.git
