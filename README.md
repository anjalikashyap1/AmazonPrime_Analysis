# PrimeInsights – Amazon Prime Video Analytics Project

![Dashboard Preview](assets/dashboard_preview.png)

This project looks at Amazon Prime Video from a data and product perspective.  
The idea was to not just do EDA, but also understand how a streaming platform works behind the scenes — from data to business decisions.

It combines:
- exploratory data analysis (Python)
- a Power BI dashboard
- a detailed business case study (product + system design + strategy)

---

## 📁 What’s in this repo

### 1. EDA (Python / Colab)
Notebook where I explored the Prime Video dataset.

Things I looked at:
- content distribution across genres
- trends over the years
- movie vs TV show split
- general patterns in the dataset

File: `eda/prime_eda.ipynb`

---

### 2. Power BI Dashboard
Built a dashboard to make the insights easier to understand.

Includes:
- content trends over time  
- genre distribution  
- release patterns  

File: `dashboard/prime_dashboard.pbix`

---

### 3. Business Case Study
This is the main part of the project.

Covers:
- product analysis (how Prime Video works)
- database schema design (users, content, watch history, etc.)
- guesstimates (market size, growth, and with references)
- cohort analysis (user retention)
- A/B testing (recommendation system example (Heuristic))
- system design scenarios (scalability, caching, transactions, etc.)

File: `business_case/prime_case_study.pdf`

---

## 📊 Some Key Observations

- Content has grown significantly after ~2015  
- Drama and Comedy dominate most of the catalog  
- There’s strong potential in regional/local content  
- Retention tends to drop after the first few months  

---

## 💡 Business Ideas Explored

Some strategies from the case study:

- introduce / expand ad-supported plans  
- invest more in regional content  
- improve recommendation systems  
- optimize pricing across regions  

Estimated combined impact: **~25–30% improvement in profit (theoretical)**

---

## 🛠️ Tools Used

- Python (Pandas, Matplotlib, Seaborn)  
- Power BI  
- SQL concepts (schema design)  
- Google Colab  

---
