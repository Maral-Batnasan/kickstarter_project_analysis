# 🚀 Kickstarter Project Analysis

## 📊 Project Objective
Develop a classification model to predict whether a Kickstarter project will be **"successful"** or **"failed"** at launch and create a clustering model to group similar projects for meaningful business insights.

---

## 🧠 Key Components

### 1️⃣ Classification Model
- **Goal:** Predict project success at launch using key predictors.
- **Steps Taken:**
  - Preprocessed data with outlier handling (log transformations, anomaly detection).
  - Engineered features like campaign duration, launch timing, and categorical indicators.
  - Explored multiple models, with **Lasso-Regularized Logistic Regression** achieving the best accuracy (80.16%).
  - Tuned hyperparameters using GridSearchCV for optimal performance.

- **Business Impact:**
  - **Predictive Insights:** Identify high-potential projects for strategic focus.
  - **Optimized Backer Engagement:** Highlight promising projects to boost credibility.
  - **Operational Efficiency:** Streamline promotional efforts for Kickstarter.

---

### 2️⃣ Clustering Model
- **Goal:** Group projects into clusters based on similarities and analyze their characteristics.
- **Steps Taken:**
  - Used **K-Means Clustering** with PCA (retaining 95% variance) for dimensionality reduction.
  - Explored DBSCAN for anomaly detection, improving overall cluster quality.
  - Segmented projects into clusters with unique patterns of success.

- **Insights from Clusters:**
  - **High-Success Clusters (4, 6, 3):** Campaigns with realistic goals, niche focus, or strong engagement.
  - **Low-Success Clusters (1, 2):** Projects needing strategic improvements in goals and marketing.
  - **Average-Success Clusters (0, 5):** Mid-performing campaigns that benefit from refined messaging.

- **Business Impact:**
  - **For Kickstarter:** Allocate resources effectively, promoting high-potential campaigns and supporting weaker ones.
  - **For Creators:** Provide tailored guidance on goals, messaging, and launch strategies.
  - **For Backers:** Enhance project discovery and improve user satisfaction.

---

## ⚙️ Technical Tools
- **Languages:** Python
- **Techniques:** Logistic Regression, Lasso Regularization, K-Means Clustering, PCA, Isolation Forest
- **Libraries:** Scikit-learn, Pandas, Matplotlib

---

## 📈 Results
- **Classification Model Accuracy:** 80.16%
- **Clusters Identified:** 7, each with distinct characteristics contributing to platform insights.

---

## 🌟 How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/username/kickstarter-project-analysis
