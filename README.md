<div align="center">

# Hey, I'm Vansh 👋

### Data Analyst · ML Practitioner · Builder of Things That Actually Work

*I don't just train models — I build systems that answer real questions, handle messy data, and ship to production.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vansh-chandan-875a373a3)
[![X](https://img.shields.io/badge/X-black.svg?logo=X&logoColor=white)](https://x.com/Vansh_7206)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:vchanan0702@gmail.com)

</div>

---

## 🧠 How I Think About ML

Most ML projects stop at accuracy. Mine don't.

- **Threshold tuning > chasing +1% accuracy** — a model optimized for business cost beats a model optimized for a leaderboard
- **Deployability is part of the definition of "done"** — if it can't be used, it isn't finished
- **Explainability is a feature** — a simple model that decision-makers understand beats a black box every time
- **EDA is where real insights live** — I don't skip it to get to modeling faster

---

## 🚀 What I Build

```
Raw Data  →  EDA  →  Feature Engineering  →  Modeling  →  Evaluation  →  Streamlit App  →  Insights
```

- End-to-end ML pipelines with deliberate design decisions at every step
- NLP systems: text preprocessing, vectorization, classification
- Business intelligence tools: RFM segmentation, customer analytics, AI query engines
- Deployed web apps with real prediction interfaces (not just notebooks)
- Power BI dashboards that tell stories, not just show numbers

---

## 📌 Featured Projects

### 🛒 [AI-Powered E-Commerce BI System](https://github.com/Vansh7206/ecommerce-rfm-analysis)
> *Ask business questions in plain English. Get instant, AI-explained data insights.*

Built on the 99K-order Olist Brazilian E-Commerce dataset. Combines RFM customer segmentation with a natural language query engine — no SQL required.

- **AI Query Engine:** intent parsing → Pandas execution → LLM-style business explanation
- **RFM Segmentation:** Champion / Loyal / Regular / Lost customer tiers
- **Key finding:** Loyal customers drive majority of revenue, yet most customers buy only once — retention is the #1 growth lever
- **Stack:** Python · Pandas · Streamlit · Power BI · Modular architecture (6 decoupled components)

---

### 🎓 [Instructor Effectiveness Modeling](https://github.com/Vansh7206/instructor-effectiveness-modeling)
> *Predict instructor performance tiers using engagement and learning metrics — live on Streamlit.*

Instead of using raw columns, I designed a **custom 3-pillar scoring system** (Learning Outcome 40% · Engagement 35% · Instructor Quality 25%), justified with EDA findings (dropout rate had -0.95 correlation with completion rate).

- **Random Forest: 96% accuracy** — zero critical misclassifications (no Low predicted as High)
- Aggregated 2,000 batch rows → 120 instructor-level records with balanced tier assignment
- Feature importance aligned with EDA findings (dropout_rate_inv = top predictor at 0.283)
- **Stack:** Python · Scikit-learn · Streamlit · Power BI · Jupyter

🔗 [**Live App →**](https://instructor-effectiveness-modeling.streamlit.app/)

---

### 📧 [Email Spam Classifier](https://github.com/Vansh7206/email-spam-classifier)
> *End-to-end NLP pipeline from raw text to deployed web app.*

A clean demonstration of ML pipeline discipline: preprocessing → vectorization → training → persistence → inference, with a strict separation between training and inference logic.

- NLP pipeline: lowercasing → punctuation removal → stopword removal → stemming
- Bag-of-Words feature extraction with `CountVectorizer`
- Random Forest classifier with `joblib` model persistence
- **Stack:** Python · NLTK · Scikit-learn · Streamlit

🔗 [**Live App →**](https://email-spam-classifier-aiyczappnnkdsdp5hi574jv.streamlit.app/)

---

### 📉 [Telco Customer Churn Prediction](https://github.com/Vansh7206/Telco-Customer-Churn-ML)
> *Where threshold tuning matters more than raw accuracy.*

End-to-end churn prediction with a deliberate focus on **business cost asymmetry** — missing a churning customer (FN) is far more expensive than flagging a loyal one (FP).

- Threshold set to **0.3** (not default 0.5) to reduce false negatives
- Extensive EDA, feature engineering, and preprocessing
- Logistic Regression with interpretable coefficients
- Deployed as an interactive Streamlit web app

---

## 🛠 Tech Stack

**Core ML & Data**

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/NumPy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/Scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

**NLP**

![NLTK](https://img.shields.io/badge/NLTK-4EA94B?style=for-the-badge&logo=python&logoColor=white)

**Visualization & BI**

![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

**Deployment**

![Streamlit](https://img.shields.io/badge/Streamlit-%23FE4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)

---

## 📂 How to Navigate My GitHub

Every project follows the same philosophy:

| What you'll find | Why it's there |
|---|---|
| A clear problem statement | So the code has context, not just syntax |
| EDA before modeling | Because data shapes decisions |
| Intentional model choices | Simple with justification beats complex without |
| Deployed apps | Because notebooks aren't products |
| Documented trade-offs | FP vs FN, threshold choices, architecture decisions |

Simple choices are intentional. If I used Logistic Regression, there's a reason it beat the alternatives for that problem.

---

## 🤝 Open To

- Data analytics & ML collaborations (beginner → intermediate)
- Feedback on real-world ML projects
- Discussions around model evaluation, threshold tuning, and business trade-offs

---

<div align="center">

*Building ML systems that are useful, explainable, and actually deployed.*

</div>
