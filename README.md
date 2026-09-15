<div align="center">

# 🌾 Direct Market Access for Farmers

### Machine Learning-Based Bidirectional Recommendation System

Bridging the gap between **farmers** and **vendors** through intelligent recommendations powered by **K-Means Clustering**.

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-success)

</div>

---

## 📖 Project Overview

The agricultural supply chain often involves multiple intermediaries, reducing farmers' profits while increasing costs for buyers. This project proposes a **Machine Learning-based Bidirectional Recommendation System** that directly connects **farmers** with **vendors**, improving transparency, efficiency, and profitability.

Using **K-Means Clustering**, the system groups farmers and vendors based on their **location, product type, reliability score, and pricing**, then generates **Top-5 recommendations** for both parties.

This project was developed as a research-oriented solution at **Manav Rachna University** and demonstrates how machine learning can solve real-world agricultural challenges.

---

## ✨ Key Features

- 🔄 Bidirectional recommendation system for farmers and vendors
- 📍 Location-aware matching
- 🌱 Product-based recommendations
- 🤖 K-Means clustering for intelligent grouping
- ⭐ Vendor reliability prioritization
- 📊 Data preprocessing with Label Encoding and StandardScaler
- 📈 Elbow Method for selecting optimal clusters
- 💻 Interactive HTML-based project interface
- 📄 Research paper and presentation included

---

## 🎯 Problem Statement

Farmers often struggle to find suitable vendors willing to purchase their products at fair prices, while vendors face difficulty identifying reliable suppliers offering the required products. These challenges create inefficiencies throughout the agricultural supply chain. <FileCite ref_id=turn1file0 line_range_start=8 line_range_end=21/>

### Challenges

- Limited direct access between farmers and vendors.
- Difficulty finding suitable product matches.
- Lack of pricing transparency.
- Vendor reliability concerns. <FileCite ref_id=turn1file0 line_range_start=8 line_range_end=21/>

---

## 🎯 Project Objectives

The primary objective is to develop a machine learning-based recommendation system that connects farmers with suitable vendors based on shared preferences and market characteristics.

### Specific Goals

- Group similar farmers and vendors using clustering.
- Match users based on **product type** and **location**.
- Recommend the **Top 5 vendors** for each farmer.
- Improve agricultural market accessibility. <FileCite ref_id=turn1file0 line_range_start=24 line_range_end=37/>

---

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Language | Python |
| Machine Learning | Scikit-learn |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib |
| Notebook | Jupyter |
| Frontend | HTML, CSS, JavaScript |
| Dataset | CSV |

---

## 📂 Project Structure

```text
direct-market-access-for-farmers-ml/
│
├── data/
│   ├── farmers_extended.csv
│   └── vendors_extended.csv
│
├── notebooks/
│   └── Untitled7.ipynb
│
├── src/
│   └── (ML implementation files)
│
├── web/
│   └── project code in HTML format.html
│
├── images/
│   ├── banner.png
│   ├── architecture.png
│   ├── workflow.png
│   ├── elbow_method.png
│   └── cluster_visualization.png
│
├── docs/
│   ├── Direct Market Access for Farmers Research Paper.pdf
│   └── Direct Market Farmers Project Presentation.pdf
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 📊 Dataset

The recommendation system uses two structured datasets.

| Dataset | Purpose |
|----------|---------|
| `farmers_extended.csv` | Farmer information including location, product type, and land size |
| `vendors_extended.csv` | Vendor information including reliability score, pricing, and location |

These datasets provide the foundation for clustering and recommendation generation. <FileCite ref_id=turn1file0 line_range_start=39 line_range_end=109/>

---

## ⚙️ Methodology

The project follows a structured machine learning pipeline.

<AsyncImage query="simple machine learning workflow diagram farmer vendor data preprocessing feature engineering k-means clustering recommendation system" aspectRatio="16:9" width="100%" maxHeight=420/>

### 1. Data Collection

Data was collected from:

- Farmer datasets
- Vendor datasets
- Agricultural market information

The collected features include:

- Location
- Product Type
- Reliability Score
- Average Price
- Land Size <FileCite ref_id=turn0file0 line_range_start=170 line_range_end=188/>

---

### 2. Data Preprocessing

The datasets were cleaned and standardized before training.

#### Data Cleaning

- Removed duplicate records.
- Filled missing values.
- Standardized essential fields.
- Cleaned categorical text values. <FileCite ref_id=turn1file0 line_range_start=165 line_range_end=178/>

#### Feature Engineering

- Label Encoding for categorical variables.
- StandardScaler for numerical features. <FileCite ref_id=turn1file0 line_range_start=175 line_range_end=178/>

---

### 3. Model Selection

The project uses **K-Means Clustering** because it effectively groups similar farmers and vendors based on shared characteristics.

<AsyncImage query="K-Means clustering agriculture machine learning illustration" aspectRatio="16:9" width="100%" maxHeight=420/>

The clustering considers:

- Product Type
- Location
- Reliability
- Pricing

to create meaningful recommendation groups. <FileCite ref_id=turn1file0 line_range_start=184 line_range_end=196/>

---

### 4. Recommendation Engine

After clustering, the system generates:

- Top 5 Vendors for each Farmer
- Top 5 Farmers for each Vendor

This creates a **bidirectional recommendation system** that benefits both sides of the marketplace. <FileCite ref_id=turn0file0 line_range_start=222 line_range_end=253/>

---

## 🏗️ System Architecture

<AsyncImage query="machine learning system architecture diagram farmer vendor preprocessing feature engineering k-means clustering recommendation engine web interface" aspectRatio="16:9" width="100%" maxHeight=420/>

The architecture follows this flow:

1. Farmer Input
2. Vendor Input
3. Data Preprocessing
4. Feature Engineering
5. K-Means Clustering
6. Farmer-Vendor Matching
7. Web Platform Interface

This workflow is also reflected in the project presentation. <FileCite ref_id=turn1file0 line_range_start=110 line_range_end=163/>

---

## 📈 Results

The research demonstrates strong recommendation performance.

| Metric | Score |
|--------|------:|
| Precision | **0.85** |
| Recall | **0.82** |
| F1 Score | **0.83** |

The model successfully grouped farmers and vendors into meaningful clusters and improved recommendation accuracy. <FileCite ref_id=turn0file0 line_range_start=254 line_range_end=312/>

---

## 🌍 Project Impact

This solution aims to:

- Increase farmers' profitability.
- Reduce dependency on middlemen.
- Improve vendor discovery.
- Enhance market transparency.
- Build a more efficient agricultural supply chain.

The case studies in the research paper indicate measurable improvements in operational efficiency and farmer outcomes. <FileCite ref_id=turn0file0 line_range_start=286 line_range_end=312/>

---

## 💻 Web Interface

In addition to the machine learning implementation, the project includes an **HTML-based interface** demonstrating how users can interact with the recommendation system.

### Interface Features

- Farmer and Vendor input flow
- Simple web-based layout
- Project demonstration interface

This makes the project easier to present during demonstrations and placements.

---

## 🚀 Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/direct-market-access-for-farmers-ml.git
cd direct-market-access-for-farmers-ml
