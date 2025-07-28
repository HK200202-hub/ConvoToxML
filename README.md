# ConvoToxML


# 🐦 Twitter Conversation Toxicity Analysis 🔎

Welcome to the **Twitter Conversation Toxicity Analysis** project! 🎉  
This repository walks through an end-to-end data science process on a large dataset of Twitter conversations—covering everything from data cleaning and exploratory visualization to advanced machine learning, regularization, and unsupervised learning.  
If you love data, social media analysis, or want to learn hands-on applied machine learning in Python, you’re in the right place! 🌟

## 📂 Project Overview

This project is divided into four major parts:
1. **Exploratory Data Analysis (EDA)**  
   - Data cleaning, visualization, hypothesis testing
2. **Linear & Logistic Regression**
   - Foundational predictive modeling
3. **Model Selection & Regularization**  
   - Comparing major ML models, feature engineering, cross-validation, and advanced regularization (Lasso, Ridge, Elastic Net)
4. **Unsupervised Learning**  
   - Principal Component Analysis (PCA) and K-Means clustering to unlock deeper insights

## 🗃️ Dataset

- **Source:** Random sample of ~80,000 Twitter conversations (Aug 14 – Sep 28, 2021)
- **Features:** User engagement, profile details, toxicity measures, and conversation structure  
- **Key Variables:**  
  - `Followers, Friends, Num_tweets, Verified, Listed_count, Location, Age`
  - `Length, Num_users, Num_author_replies, Toxicity`
  - `Num_toxic_direct_replies, Num_toxic_nested_replies, Num_author_toxic_replies`

## 🚦 File Structure

| File Name                           | Description                                                |
|--------------------------------------|------------------------------------------------------------|
| `project-part1_39127595.pdf`         | 📊 Detailed EDA and data prep instructions                 |
| `project-part2_39127676.docx`        | 💡 Linear Regression and additional analysis tasks         |
| `Project_part3_39702120.docx`        | 🤖 Model selection, cross-validation, and regularization   |
| `Project_part4_39702139.docx`        | 🧩 Unsupervised analysis with PCA and Clustering           |
| `data/twitter_conversations.csv`     |  Large CSV dataset                                          |
| `notebooks/.ipynb`    | 💻 Main project notebook with code, output, interpretations|

## 🛠️ How to Run

1. **Clone this repo:**  
   ```bash
   git clone https://github.com/yourusername/twitter-toxicity-analysis.git
   cd twitter-toxicity-analysis
   ```
2. **Install requirements** (via pip or conda):  
   ```bash
   pip install -r requirements.txt
   ```
   *(Typical libraries: pandas, seaborn, matplotlib, scikit-learn, scipy, jupyter)*

3. **Download the dataset** (as directed - not included here for size/privacy).
4. **Open the Jupyter notebook** and follow each section cell-by-cell!

## 🧑‍🔬 Features & Methods

- **Data Wrangling:** Handling missing/duplicate data, feature creation (toxic conversation labeling)
- **EDA:** Histograms, boxplots, value counts, and descriptive stats
- **Statistical Testing:** T-test, Mann-Whitney U, Chi-Square—*with interpretations!*
- **Machine Learning:**  
  - Logistic Regression, SVM, Random Forest (with 5-fold CV)
  - L1 (Lasso), L2 (Ridge), Elastic Net regularization
- **Unsupervised Learning:**  
  - PCA (with explained variance plots)
  - K-Means (with cluster analysis)

## 📊 Example Visualizations

- Boxplots and histograms of engagement metrics  
- Bar charts by account age  
- PCA explained variance plots and 2D scatter visuals  
- Cluster centroid visual analysis

## ❓ How to Contribute

Want to extend the project or run your own experiments?  
Feel free to fork, create pull requests, or open issues!

1. Fork this repo
2. Make improvements or add analyses 📈
3. Open a PR and let’s discuss!

## 🙌 Credits

 - Dataset: Proprietary Twitter sample (2021)  
- Developed by: Hari Krishna*

## 💬 Contact

Questions? Suggestions?  
Open an issue in this repo or connect via [LinkedIn](https://www.linkedin.com/in/hk200202)!

## ⭐ Star this repo if you found it useful, and happy analyzing! 🚀

🌈 **Let’s build a safer, more informed social media landscape together!**

