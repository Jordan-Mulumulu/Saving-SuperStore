# 📊 Saving Superstore – A Tableau BI Analysis Project

**Author:** Jordan Mulumulu  

**Tools Used:** Tableau Desktop, Excel  

## 🧠 Project Objective

The goal of this project was to help a struggling retail superstore identify **where it loses and makes money**, **how to optimize its advertising**, and **which products and customers are affecting profitability** through returns.

This was completed as part of my Business Intelligence training with TripleTen, using **real-world retail data** and Tableau.

---

## 🔍 Analysis Breakdown

### 📌 Part 1: Profits & Losses

**Questions Answered:**

1. **What are the top 2 profit centers and 2 biggest loss-makers by dimension pair?**  

    ➤ Identified **Sub-Category + Region** combinations using a heatmap.  

    ✅ Most profitable: *Copiers in the West, Phones in the East*  

    ❌ Biggest losses: *Binders in Central, Tables in East*

3. **Which products should be dropped?**  

    ➤ Products with the **lowest total profits** were flagged, like the *GBC DocuBind P400* and *Cubify CubeX 3D Printer*.

5. **Which sub-categories to keep vs cut?**  
 
   ➤ Based on profit performance:

    - **Keep:** Copiers, Phones, Accessories  

    - **Cut:** Tables, Bookcases, Supplies  

---

### 📌 Part 2: Advertising Strategy

**Questions Answered:**

1. **Where and when should we advertise?**  
 
   ➤ Selected **Top 10 State-Month pairs** based on profit trends.  

   ✅ New York (Sept), California (Dec), Washington (March) were standouts.

3. **How much should we spend?**  
 
   ➤ Calculated **ad budgets** using Return on Ad Spend logic  
 
   ➤ Willing to spend **up to 20% of average profit** in target months  

   ➤ Budgets created for each top location-month combination.

---

### 📌 Part 3: Returned Items

**Questions Answered:**

1. **Which products are returned the most?**  

   ➤ Created a calculated field for binary return values.  

   ❗ Products like *Zebra GK420d Printer* had **100% return rates**.

3. **Which customers have high return rates?**  

   ➤ Customers like *Roland Murray* and *Hilary Holden* had **100% of their orders returned**.

5. **Does return rate affect profitability?**  

   ➤ Built a scatterplot comparing **return rate vs average profit by sub-category**.  

   - **Copiers:** High profit, low returns = 🔥  

   - **Machines/Supplies:** Low profit, high returns = 🚫

---

## ✅ Key Takeaways

- **Focus growth** on profitable, stable categories like *Copiers* and *Phones*.  

- **Cut losses** by dropping subcategories like *Tables* and *Bookcases*.  

- **Invest wisely** in advertising — target high-profit state-months like *NY in Sept*.  

- **Mitigate returns** by identifying high-return products/customers early.

---

## 🌐 Tableau Public Dashboard - Project Link! 

> 📍 https://public.tableau.com/views/JordanMulumuluTableauSuperstore/SavingSuperStoreWhattoCutKeepandAdvertise?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
---

## 💡 Skills Demonstrated

- Data Cleaning & Joining  

- Calculated Fields & Logical Expressions  

- ROI & Profitability Analysis  

- Dynamic Filtering & Color Encoding  

- Data Storytelling with Tableau Story Points

---

## 📫 Let's Connect

**LinkedIn:** www.linkedin.com/in/jordan-mulumulu
**Email:** JMulumulu@gmail.com






