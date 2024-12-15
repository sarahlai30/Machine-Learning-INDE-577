# Unsupervised Learning
Unsupervised learning is a subset of machine learning that focuses on working with data that has no predefined labels or categories. Unlike supervised learning, where the outcomes or classifications are explicitly provided, unsupervised learning algorithms aim to uncover patterns, structures, and relationships within the data independently. This makes it a powerful approach for exploratory data analysis, where the primary objective is to understand the intrinsic structure of the dataset.
![image](https://github.com/user-attachments/assets/77eed916-bfc6-43d6-8a38-35cf780e4a2a)

In artificial intelligence, unsupervised learning refers to a machine learning paradigm that operates without human-provided labels or supervision. Unlike supervised learning models, which rely on labeled data for training, unsupervised learning models are provided with raw, unlabeled data and tasked with discovering meaningful patterns and insights autonomously, without explicit guidance.

These algorithms analyze and group data by identifying hidden patterns or relationships. The process involves using only the input features of the dataset, allowing the model to independently discover clusters or structures within the data, without being influenced by predefined outcomes or categories.

---
## **📊 Algorithms Implemented**
The following algorithms are implemented in this directory:

1. **K-Means Clustering** - A centroid-based algorithm that partitions data into clusters based on feature similarity.
2. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** - A density-based clustering algorithm for identifying clusters of varying shapes and detecting noise.
3. **Principal Component Analysis (PCA)** - A dimensionality reduction technique used to transform high-dimensional data into a lower-dimensional space while preserving variance.
4. **Image Compression with Singular Value Decomposition (SVD)** - A technique to compress image data by retaining only the most significant singular values.

---

## **📂 Datasets Summary**
The following datasets are used for the above algorithms:

### **1. Mall Customers Dataset**
- **Description:** The Mall Customers dataset contains data on customer spending behavior in a shopping mall. It includes demographic information and spending patterns.

### **2. Wine Dataset**
- **Description:** The Wine dataset contains 13 chemical properties of wines derived from the same Italian region. Wines are categorized into three classes based on grape varieties.

---

## 📊 Instructions for Reproduction

---

### **1. Open a Notebook in Google Colab**
- Upload the relevant `.ipynb` file to your Google Drive.
- Open [Google Colab](https://colab.research.google.com/).
- Click **File > Open Notebook**, then **Upload** your `.ipynb` file or load it from Google Drive.

---

### **2. Set Up the Environment**
- Install any missing packages using the following command:
```python
!pip install -r requirements.txt
```

### **3. Upload or Mount Datasets**
Upload files directly in Colab:

```python
from google.colab import files
uploaded = files.upload()
```

### **4. Run the Model Notebooks**
