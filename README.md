# MyOnlineShop Market Demand Analysis


## 📌 Introduction  
In today’s competitive e-commerce and retail environment, understanding **market demand, customer engagement, and satisfaction** is essential for making data-driven decisions.  
This project analyzes **1,000 products across 10 categories** scraped from the Jumia online store. The analysis focuses on:  

- **Reviews** → as a proxy for customer engagement/demand.  
- **Ratings** → as a measure of customer satisfaction.  
- **Discounts** → to understand pricing strategies.  

The goal is to uncover actionable insights that guide **marketing, pricing, and category management strategies** for improved profitability and customer loyalty.

---

## ❓ Problem Statements  
1. Which product categories attract the most customer engagement in terms of reviews?  
2. Do higher engagement levels translate to higher satisfaction, or are there trade-offs?  
3. How widespread is discounting, and does heavy discounting signal reliance on price?  
4. Which categories perform best and worst in terms of customer satisfaction?  

---

## 🎯 Objectives  
- Measure **market demand** using reviews as a proxy.  
- Assess **customer satisfaction** through ratings.  
- Evaluate the **prevalence and role of discounts**.  
- Generate **strategic insights** for category growth, pricing, and retention.  

---

## 🔑 Key Questions  
- Which categories generate the most engagement and demand?  
- Which categories are highly popular but poorly rated (and vice versa)?  
- What % of products are rated by customers, and how many receive discounts?  
- Which categories rely most heavily on discounting?  
- What overall patterns emerge when combining engagement, satisfaction, and pricing?  

---

## 📂 Data Overview  
**Dataset:** 1,000 products scraped from Jumia (10 categories × 100 products each).  

**Data Dictionary:**  
- `Product Name` → Product title.  
- `Current Price` → Selling price after discount.  
- `Original Price` → Listed price before discount.  
- `Review Count` → Number of customer reviews.  
- `Rating` → Avg. customer rating (out of 5).  
- `Discount` → % reduction from original to current price.  
- `Brand` → Product brand/manufacturer.  
- `Category` → Product category.  

---

## 🧹 Data Cleaning & Preparation  
1. **Price Fix** → Standardized prices when ranges were listed.  
2. **Missing Discounts/Prices** → Replaced missing `Discount` with `0` and `Original Price` with `Current Price`.  
3. **Brand** → Missing brands replaced with `"Unknown Brand"`.  
4. **Review Count** → Missing values treated as `0`.  
5. **Rating** → Kept missing ratings as `Null` to distinguish rated vs. unrated products.  

---

## 📊 Key Insights  
- **Engagement:** 607,000 reviews total; avg. 606 reviews per product.  
- **Satisfaction:** 88.1% of products rated; avg. rating **4.06** (65% ≥ 4 stars).  
- **Discounts:** Avg. discount **30%**; 83% of products discounted.  

**Category Highlights:**  
- **High Engagement:** Phones & Tablets (2,095 reviews), Health & Beauty (1,231 reviews).  
- **High Satisfaction:** Supermarket (4.43), Gaming (4.28), Baby Products (4.12).  
- **Struggling Category:** Fashion → low reviews & low ratings (3.75).  
- **Discount-Heavy:** Computing (40%), Fashion (40%).  
- **Stable Pricing:** Supermarket (14%), Appliances (22%).  

---

## 📝 Recommendations  
1. **Boost low-engagement categories** (Gaming, Baby Products, Supermarket) with promotions.  
2. **Investigate unrated products (12%)** → improve or phase out.  
3. **Improve low-rated categories** (Phones & Tablets, Fashion) via quality/vendor checks.  
4. **Reduce reliance on discounts** → use bundles, warranties, loyalty perks.  
5. **Balance pricing strategies** → avoid customer over-reliance on discounts.  
6. **Category-Specific Actions:**  
   - **Scale up**: Supermarket, Gaming, Baby Products.  
   - **Fix quality gaps**: Phones & Tablets, Health & Beauty.  
   - **Reassess**: Fashion (reposition or cut).  
   - **Upsell**: Appliances, Computing (loyal niche audience).  

---

## ✅ Conclusion  
The analysis shows that:  
- **Demand is strong but uneven** → concentrated in Phones & Tablets and Health & Beauty.  
- **Satisfaction varies** → Some popular categories struggle with ratings, while smaller categories excel.  
- **Discounting dominates** (83% of products) → but risks eroding long-term brand value.  

📌 To sustain growth, businesses should **improve customer experience in high-demand but low-rated categories** and **amplify visibility of smaller, high-rated categories**, while **reducing over-reliance on discounting strategies**.  

---

## 💬 Got Feedback or Questions?  
I’d love to hear your thoughts.  
Feel free to open an issue or fork the repo and build on it.

## 📲 Want to reach out?

📬 Let’s connect on [LinkedIn](https://www.linkedin.com/in/enobong-umanah/)

🧠 Follow my learning process on [my blog](https://medium.com/@Sophieumanah)
