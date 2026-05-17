# 💊 Pharmacity Product Recommendation System

> A Data Science and NLP project for recommending pharmaceutical products using product information collected from Pharmacity website data.

---

## 📌 Overview

This project builds a recommendation system capable of suggesting similar pharmaceutical products based on product descriptions, categories, and textual features.

The system applies Natural Language Processing (NLP) and similarity-based recommendation techniques to improve product discovery and recommendation quality.

---

## 🎯 Objectives

- Analyze pharmaceutical product data
- Preprocess product text information
- Build a recommendation engine
- Suggest similar products automatically
- Improve recommendation relevance using NLP techniques

---

## 📊 Dataset

The dataset contains product information collected from Pharmacity website data, including:

- Product Name
- Category
- Brand
- Description
- Usage
- Price

---

## 🧹 Data Preprocessing

Preprocessing steps included:

- Removing missing values
- Text normalization
- Lowercasing
- Removing stopwords
- Tokenization
- Feature extraction

---

## 🧠 Recommendation System Workflow

```text
Product Data
      ↓
Text Cleaning
      ↓
TF-IDF Vectorization
      ↓
Cosine Similarity
      ↓
Recommendation Output
```

---

## 🤖 Techniques Used

### TF-IDF Vectorization

Used to convert textual product descriptions into numerical feature vectors.

### Cosine Similarity

Used to measure similarity between products and generate recommendations.

---

## 📈 Recommendation Example

### Input Product

```text
Vitamin C 500mg
```

### Recommended Products

- Vitamin C Plus
- Multivitamin C
- Immune Support Capsules
- Zinc + Vitamin C

---

## 📊 Visualization

### Product Category Distribution

![Category Distribution](images/category_distribution.png)

### Similarity Matrix Visualization

![Similarity Matrix](images/similarity_matrix.png)

---

## 🛠 Technologies Used

- Python
- Pandas
- Scikit-learn
- NLP
- TF-IDF
- Cosine Similarity
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

```bash
pharmacity-recommendation-system/
│
├── data/
├── notebooks/
├── images/
├── report/
├── README.md
```

---

## 👨‍💻 My Contributions

Responsibilities:

- Data preprocessing
- NLP text processing
- Recommendation model development
- Similarity analysis
- Visualization and reporting

---

## 🚀 Future Improvements

Potential improvements include:

- Deep Learning recommendation models
- User-based collaborative filtering
- Real-time recommendation API
- Web deployment

---

## 📄 Report

Detailed report available in:

```bash
report/report.pdf
```
