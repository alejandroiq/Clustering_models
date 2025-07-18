# 🧠 Applied Machine Learning Lab — DataVine Analytics

This repository presents three machine learning projects developed as part of a consulting simulation for **DataVine Analytics**, a boutique analytics firm serving clients across various sectors. The objective is to apply classification, recommendation, and clustering techniques to standardized datasets that mirror real-world business problems. The projects follow the **CRISP-DM workflow**: from data cleaning and preprocessing to modeling, evaluation, and interpretation.

## 🧪 Objective

This task aims to demonstrate practical applications of machine learning by developing three prototypes:

1. **Wine Classification** – Using k-NN and PCA for quality control in wine distribution.
2. **Feed Recommendation System** – Recommending agricultural feed using PCA and cosine similarity.
3. **Regional Crime Clustering** – Uncovering crime patterns with K-Means and GMM clustering models.

Each project follows a rigorous data science workflow, including:

- 🔍 **Data Cleaning and Standardization**
- 🧬 **Dimensionality Reduction (PCA)**
- ⚙️ **Model Development and Hyperparameter Tuning**
- 📈 **Evaluation and Visualization**

---

## 🍷 1. Wine Classification (k-NN + PCA)

**Client:** Premium Wine Distributor  
**Goal:** Classify wine varieties based on chemical properties for automated inventory management.

### 🔧 Methodology

- Converted categorical target labels into numeric values.
- Standardized all features.
- Applied **PCA** to retain 95% of variance.
- Tuned `k` and distance metrics using **GridSearchCV**.
- Trained a **k-NN classifier** using the optimal parameters.
- Evaluated with **classification report** and **accuracy score**.

---

## 🐓 2. Agricultural Feed Recommendation (PCA + Cosine Similarity)

**Client:** Agricultural Supply Company  
**Goal:** Recommend similar types of feed that produce comparable chicken growth outcomes.

### 🔧 Methodology

- Loaded and cleaned the `chickwts` dataset.
- Standardized the weight feature.
- Applied **PCA** to reduce data to 1 principal component.
- Computed **cosine similarity** among feed types.
- Recommended feeds with the most similar nutritional impact.

---

## 🔍 3. Regional Crime Clustering (K-Means + GMM)

**Client:** Public Policy Research Firm  
**Goal:** Identify regional patterns in crime rates for policy and resource planning.

### 🔧 Methodology

- Loaded the `USArrests` dataset and standardized features.
- Selected top 3 features for clustering.
- Applied **PCA** for 2D visualization and efficiency.
- Determined optimal number of clusters:
  - **Elbow Method** for K-Means
  - **BIC** for GMM
- Compared **K-Means** (hard clustering) vs **GMM** (probabilistic clustering).
- Visualized cluster assignments with regional context.

---

## 📌 Tools & Libraries

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebooks
- PCA, k-NN, Cosine Similarity, KMeans, GaussianMixture, GridSearchCV

---

## 📈 Results Summary

| Task | Model | Key Metric | Insight |
|------|-------|------------|---------|
| Wine Classification | k-NN + PCA | Accuracy | High classification performance achieved with optimized `k` |
| Feed Recommendation | Cosine Similarity + PCA | Similarity Score | Feeds with similar growth profiles identified for substitution |
| Crime Clustering | K-Means / GMM + PCA | Inertia / BIC | Grouped states into meaningful crime pattern clusters |

---

## 📫 Contact

**Alejandro Silva**  
Feel free to reach out for any questions or suggestions via GitHub Issues.
---

