# 🔍 Product Recommendation System: Text-Based Suggestions with Sentence Transformers

This project aims to **analyze product descriptions and develop a recommendation system that identifies similar products**. Using the **Sentence Transformers model**, product descriptions were vectorized, and **cosine similarity** was applied to calculate similarities between products.

**Dataset:** Product descriptions from three different categories were used:
- **All Beauty**: Beauty products
- **Digital Music**: Digital music albums
- **Health and Personal Care**: Health and personal care products

---

## 🔍 Data Preprocessing

### 📌 Text Cleaning and Preparation
- **Removed unnecessary characters, punctuation, and inconsistencies in letter casing.**
- **Combined product titles and descriptions into unified text summaries.**
- **Handled missing values by applying appropriate techniques.**

### 🏗️ Text Vectorization
- **Sentence Transformers (all-MiniLM-L6-v2) was used to convert text into numerical vectors.**
- **Each product was represented as a 384-dimensional vector.**

---

## 🤖 Similarity Calculation & Recommendation System

### 📊 Applied Methods
- **Cosine Similarity** was used to calculate similarity scores between products.
- **For each product, the top 5 most similar products were identified.**

### 📈 Example Outputs
| Product | Most Similar Product | Similarity Score |
|---------|----------------------|------------------|
| Leather Care Spray | Leather Cleaning Foam | 0.88 |
| Classical Music Album | Similar Classical Album | 0.75 |
| Silicone Bath Brush | Similar Bath Product | 0.89 |

- **The recommendation system performed well within the same category.**
- **Some mismatches were observed when different categories were mixed (e.g., recommending soap instead of a music album).**

---

## 🛠️ Technologies Used

- **Python (Pandas, NumPy, Scikit-Learn, Sentence Transformers)**
- **Data Visualization (Matplotlib, Seaborn, WordCloud)**
- **Natural Language Processing (NLP) Techniques**
- **Recommendation Systems & Similarity Analysis**

---

## 📊 Visualization
- **Similarity scores of recommended products were visualized.**
- **Cosine Similarity matrix was used to analyze relationships between products.**

### 🚀 Key Insights
- **Text-based recommendation systems can be effectively implemented using Sentence Transformers.**
- **Memory optimization is necessary for large datasets.**
- **Filtering recommendations by category can improve accuracy.**

---

This project serves as a great reference for those interested in **Natural Language Processing (NLP) and recommendation systems**. Open to feedback and discussions! 🚀

