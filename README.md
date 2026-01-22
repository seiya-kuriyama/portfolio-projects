# Portfolio Projects

This repository contains the implementation codes for my research and personal projects, demonstrating my expertise in **Mathematical Physics**, **Algorithm Design**, and **Machine Learning**.

## 1. Topological Data Analysis & Knot Theory (Vogel's Algorithm)
**File:** `vogel_algorithm_implementation.ipynb` (or the actual filename you used)

### Description
This project implements **Vogel's algorithm** to computationally analyze braid group representations. It bridges abstract knot theory with algorithmic implementation to automate the calculation of topological invariants.

### Key Features
* **Algorithm Implementation:** Built Vogel's algorithm from scratch using Python.
* **Topological Invariants:** Automated the computation of **Jones polynomials** for complex knot structures.
* **Optimization:** Reduced manual calculation time for analyzing braid representations.

### Tech Stack
* **Language:** Python
* **Libraries:** NetworkX, SymPy, NumPy

---

## 2. Uncertainty-Aware Recommendation System (HCM Clustering)
**File:** `hcm_recommendation.ipynb`

### Description
This project engineers a flexible collaborative filtering recommendation system that accounts for user preference uncertainty. It utilizes **Hard C-Means (HCM)** clustering to resolve data sparsity issues inherent in personalized recommendations.

### Key Features
* **Clustering Algorithm:** Implemented HCM-based collaborative filtering to group users with similar probabilistic behaviors.
* **Performance Evaluation:** Quantified system accuracy using **ROC-AUC**, confirming effectiveness in predicting purchase behavior under uncertainty.
* **Data Handling:** Designed to process large-scale consumer panel data (binary purchase history).

### Tech Stack
* **Language:** Python
* **Libraries:** NumPy, Pandas, Scikit-learn, SciPy

### Note on Dataset
The model was validated using the **Nikkei NEEDS-SCAN/PANEL** dataset. Due to licensing and confidentiality agreements, the raw dataset is **not included** in this repository. The code demonstrates the algorithmic logic and evaluation pipeline.

---

## 3. Market Basket Analysis & Product Recommendation (SQL)
**File:** `Market_Basket_Analysis.ipynb`

### Description
This project implements a **Market Basket Analysis (Association Rule Learning)** engine using advanced SQL techniques to discover hidden purchasing patterns in e-commerce transaction data. It focuses on identifying high-frequency co-occurrence relationships to drive cross-selling strategies and improve User Experience (UX).

### Key Features
* **Advanced SQL Querying:** Utilized **Self-Join** and conditional logic (`o1.id < o2.id`) to efficiently generate unique product combinations without permutation redundancy.
* **Behavioral Insight Extraction:** Detected specific user contexts (e.g., the "Study Companion" pattern between textbooks and coffee) to propose solutions for reducing customer friction.
* **Scalable Architecture Design:** Structured the query logic to be compatible with cloud-native distributed SQL engines (e.g., Amazon Athena) for processing large-scale datasets.

### Tech Stack
* **Language:** Python, SQL
* **Libraries:** SQLite3, Pandas
