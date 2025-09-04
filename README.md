
# 📊 Funnel Analysis: Understanding User Drop-Offs

## 📌 What is Funnel Analysis?
Funnel analysis is a technique used to understand how users move through a multi-step process (the “funnel”) and where they drop off before completing the desired action.  

Example funnel:  
**Homepage → Product Page → Cart → Checkout → Purchase**  

By measuring conversion at each stage, businesses can:
- Identify bottlenecks in the user journey
- Quantify drop-off rates
- Test and prioritize product improvements to increase conversion

---

## 🎯 Business Problem
Digital products often face **high user drop-offs** before a key conversion (like purchases).  

The goal of this project was to:
1. Measure how many users reached each funnel stage  
2. Identify the biggest drop-off points  
3. Provide actionable product recommendations to improve conversion  

---

## 📊 Dataset
- **Source**: Publicly available *User Funnels Dataset (Kaggle)*  
- **Structure**: Each row represents a user event with:  
  - `user_id` → unique identifier  
  - `stage` → funnel step (`homepage`, `product_page`, `cart`, `checkout`, `purchase`)  
  - `conversion` → whether the user successfully reached that stage  

---

## 🔎 Analysis Approach
1. **Stage Counts** – Counted unique users reaching each funnel step  
2. **Conversion Rates** – Calculated % of homepage users who reached each subsequent stage  
3. **Visualization** – Built funnel charts to highlight drop-offs clearly  
4. **Insights** – Connected findings to product and UX challenges  

---

## 📈 Key Results

| Stage        | Users | Conversion from Homepage |
|--------------|-------|--------------------------|
| Homepage     | 10,000 | 100%   |
| Product Page | 2,515  | 25.15% |
| Cart         | 449    | 4.49%  |
| Checkout     | 36     | 0.36%  |
| Purchase     | 14     | 0.14%  |

---

<img width="1413" height="525" alt="newplot" src="https://github.com/user-attachments/assets/2f0c40df-2339-4d2a-b4ac-e7e86c6cc233" />


## 💡 Insights
- **Homepage → Product Page (25%)**  
  Only 1 in 4 users engaged further — homepage optimization could increase product exploration.  

- **Product Page → Cart (4.49% overall)**  
  Very few users add items to cart after viewing a product. Possible issues: product content, pricing, lack of trust signals.  

- **Cart → Checkout (0.36% overall)**  
  Sharp drop-off suggests cart abandonment — friction or unexpected costs likely.  

- **Checkout → Purchase (0.14% overall)**  
  Very low final conversion, showing users are dropping off before completing payment.  

---

## 🚀 Recommendations
- **Improve homepage engagement**: stronger calls-to-action, personalized product recommendations  
- **Boost add-to-cart rates**: enhance product detail pages with reviews, trust badges, and transparent pricing  
- **Reduce cart abandonment**: enable guest checkout, show shipping costs upfront, add exit-intent offers  
- **Increase purchase completion**: streamline checkout flow, add multiple payment methods, send recovery reminders  

---

## 🛠️ Tools & Stack
- **Python**: pandas, matplotlib, seaborn, plotly  
- **Analysis**: Conversion metrics, drop-off analysis  
- **Visualization**: Funnel plots and bar charts  

---

## 📂 Deliverables
- ✅ Jupyter Notebooks with code for data prep, analysis, and visualization  
- ✅ Funnel conversion metrics table  
- ✅ Visualizations showing user drop-offs  
- ✅ Business recommendations  

---

## ✅ Why This Project Matters
This project demonstrates how **funnel analysis connects raw user events to product strategy**.  

It shows the ability to:
- Identify where users disengage  
- Translate data into clear, actionable recommendations  
- Propose product experiments to improve engagement and conversion  

---
