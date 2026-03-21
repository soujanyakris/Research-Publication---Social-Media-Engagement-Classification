# Research Publication - Social Media Engagement Classification

## Title - Feature Classification Methods for Measuring User Engagement in Social Media Campaigns
**Published in:** IEEE Transactions on Engineering Management  
**Domain:** Sustainability / Food Waste Reduction / Campaign Analytics / Machine Learning

## 📌 Research Overview
This repository contains the analytical framework and methodology from my published research in **IEEE Transactions on Engineering Management**. The study analyzes user engagement with major UK food waste reduction campaigns on X (formerly Twitter), processing over 50,000 tweets collected over seven years.

The project moves beyond descriptive metrics to provide **predictive insights** into which tweet attributes (content, sentiment, and metadata) most strongly influence user engagement.

## ❓ Research Questions
* **RQ1:** What types of content strategies are organizations employing in food waste campaigns on social media, and how do they affect audience engagement?
* **RQ2:** What factors contribute to audience engagement with food waste campaigns on social media platforms?
* **RQ3:** How can Feature Importance Analysis inform campaign strategies and identify the most impactful predictors of user engagement?

## 🛠 Methodological Framework
The research follows a three-phase structured approach:

### Phase 1: Data Collection & Pre-processing
* **Extraction:** 55,000+ tweets extracted via X API and third-party providers.
* **Cleaning:** Filtered down to **50,820 records** using rigorous inclusion/exclusion criteria (geographic focus: UK/Ireland; relevance: sustainable practices).

### Phase 2: Feature Engineering & Model Construction
* **Sentiment Analysis:** Utilized the **VADER library** in Python to calculate sentiment polarity scores.
* **Topic Modelling:** Employed **Latent Dirichlet Allocation (LDA)** to identify dominant thematic discussions (e.g., Food Sharing, Community Mobilization).
* **Engagement Calculation:** $$Engagement Rate = \frac{(Engagements)}{(Impressions)} \times 100$$

### Phase 3: Model Evaluation & Feature Importance
Implemented and compared four machine learning classifiers:
* **Random Forest (RF)**
* **Support Vector Machines (SVM)**
* **Naïve Bayes**
* **Gradient Boosting**


## 💻 Tech Stack
* **Language:** Python
* **NLP Libraries:** VADER (Sentiment), LDA (Topic Modeling)
* **Machine Learning:** Scikit-learn (Random Forest, SVM, Gradient Boosting)
* **Data Handling:** Pandas, NumPy, SQL
* **Visualization:** Matplotlib, Seaborn

## 📂 Repository Contents
* `Tables for research paper/`: Contains processed statistical tables, including Model Accuracy, Precision, Recall, and F1-score comparisons across Random Forest, SVM, and Naïve Bayes.
* `Figures Generated using Python/`: High-resolution visualizations generated via Matplotlib and Seaborn, including Feature Importance plots, Sentiment Distribution, and LDA Topic clusters.
* `data_sample/`: Anonymized metadata samples (CSV) featuring 15+ attributes used for training the classifiers (e.g., Tweet Type, Retweet Count, Hashtag Density).

## 🎓 Citation
Krishnamurty et. al., "Feature classification methods on measuring user engagement in social media campaigns," *IEEE Transactions on Engineering Management*, [2026] [https://doi.org/10.1109/TEM.2026.3664701].
