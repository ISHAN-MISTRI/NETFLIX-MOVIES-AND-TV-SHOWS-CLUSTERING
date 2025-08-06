# 🎬 Netflix Movies & TV Shows Clustering – Unsupervised ML Project

## 📌 Project Overview  
This project applies **Exploratory Data Analysis (EDA)** and **Unsupervised Machine Learning** to the Netflix dataset to identify trends, patterns, and clusters in Movies and TV Shows.  
We aim to group similar content based on textual and numerical features, providing business insights that can enhance recommendation systems and strategic content planning.

---

## 🔍 Key Steps in the Project
### 1. Data Understanding & Cleaning
- Loaded and inspected the Netflix dataset.
- Removed duplicates, handled missing values, and fixed inconsistent data.
- Created new features: `description_length`, `year_added`, `month_added`.

### 2. Exploratory Data Analysis (EDA)
- Followed the **UBM rule** (Univariate, Bivariate, Multivariate analysis).
- Created **15 meaningful charts** showing:
  - Content type distribution (Movies vs TV Shows)
  - Top-producing countries
  - Ratings distribution
  - Trends in content addition
  - Seasonal and genre analysis
- Extracted **actionable business insights**.

### 3. Feature Engineering & Preprocessing
- Text preprocessing:
  - Lowercasing, removing punctuation, digits, URLs, stopwords.
  - Applied **TF-IDF Vectorization** for textual descriptions.
- Numerical features scaled using **StandardScaler**.
- Dimensionality reduced using **TruncatedSVD** for sparse data efficiency.

### 4. Model Implementation
Implemented and compared **five clustering algorithms**:
1. **KMeans**
2. **Agglomerative Clustering**
3. **DBSCAN**
4. **MeanShift**
5. **OPTICS**

**Evaluation Metric:** Silhouette Score  
**Best Model:** DBSCAN (Score: **0.8446**) – best at detecting arbitrary-shaped clusters.

### 5. Deployment Preparation
- Saved the final model using `joblib`.
- Tested on unseen sample data to verify predictions.

---

## 📊 Results
- **Movies** dominate Netflix’s library, though **TV Shows** have grown significantly in recent years.
- **United States, India, and UK** are top content producers.
- Most common rating: **TV-MA** (Mature Audience).
- DBSCAN selected as the **final clustering model**.

---

## 🚀 Technologies Used
- **Languages & Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, NLTK
- **ML Techniques:** TF-IDF, Dimensionality Reduction (TruncatedSVD), Clustering Algorithms
- **Tools:** Google Colab, Joblib

---

## 📌 Business Impact
This clustering project can help Netflix:
- Improve **personalized recommendations** by grouping similar titles.
- Plan **content acquisition strategies** based on trends.
- Understand **viewer preferences** by country, rating, and genre.

---

## 📂 Dataset
The dataset was obtained from public Netflix data available on Kaggle.

---

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👤 Author
**Ishan Mistri**   
