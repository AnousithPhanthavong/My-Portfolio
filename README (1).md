# Telecom Data Portfolio

**Anousith Phanthavong** -- Data Analyst Intern | Final-Year CS @ National University of Laos

Turning raw telecom subscriber data into retention strategies and marketing actions. This repo contains analytical projects built during my internship at a telecom operator in Laos.

---

## Projects

### Telco Customer Churn Prediction

Predicting which subscribers are about to leave so the business can intervene before they do.

- Trained a Random Forest classifier on billing, usage, and contract data
- Achieved **85% Recall** -- catching most at-risk customers before they churn
- Key finding: month-to-month contract holders are **3x more likely to churn**
- Business value: targeted retention SMS campaigns instead of blanket promotions, reducing acquisition costs

**Tech:** Python, Pandas, Scikit-Learn, Matplotlib

[View Notebook](Telco_Churn_Prediction.ipynb)

---

### Customer Segmentation (RFM + K-Means)

Segmenting the subscriber base so marketing sends the right offer to the right person.

- Built RFM scores (Recency, Frequency, Monetary) with quintile binning
- Applied K-Means clustering with Elbow Method to find 4 distinct personas
- Segments: **High-Value**, **Data Power Users**, **Voice-First**, **At-Risk**
- Business value: 5G upgrade offers go only to data-heavy users, voice bundles go to voice-first users -- higher conversion, lower waste

**Tech:** Python, Scikit-Learn, K-Means, StandardScaler, Seaborn

[View Notebook](Customer_Segmentation_RFM.ipynb)

---

### Other Internship Work

**Sentiment Analysis (NLP)** -- Classified customer feedback using transformers and VADER to surface complaint patterns and reduce service issues.

**Looker Dashboards** -- Built interactive dashboards tracking network KPIs, ARPU trends, and churn indicators for daily operations decisions.

**AI Chatbot Prototype** -- Automated responses to common customer service queries to free up agent capacity.

---

## Skills

| Category | Tools |
|----------|-------|
| Languages | Python, SQL |
| ML | Scikit-Learn, Random Forest, K-Means, NLP |
| Visualization | Looker, Matplotlib, Seaborn |
| Tools | Jupyter, Google Sheets, Git |

---

## Contact

anousithphanthavng@gmail.com | Vientiane, Laos
