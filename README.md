# 🏙️ Airbnb NYC 2024 – In-Depth EDA Project 📊

This project delivers an in-depth exploratory data analysis (EDA) of ~20,000 Airbnb listings across New York City to uncover patterns in pricing, availability, review behavior, and room type performance.

---

## 📁 Dataset
- ~20,700 rows × 22 columns  
- Listings include borough, price, availability, number of reviews, and review scores  
- Source: Kaggle (open dataset)

---

## 🎯 Project Goals
- Understand how listing performance varies across NYC boroughs
- Reveal high-revenue zones and low-converting listings
- Analyze pricing trends and affordability by room type
- Provide actionable insights for hosts and platform-level optimization

---

## 💡 Key Achievements 
- ✅ Cleaned and analyzed **20,724 Airbnb listings** across NYC (100% missing values and duplicates removed)
- ✅ Reduced dataset from **22 columns to 17**, focusing only on business-relevant variables
- ✅ Grouped and compared **3 room types** across **5 boroughs** by price, reviews, and availability
- ✅ Revealed that **Entire home/apt listings** had **18–25% higher review scores** on average
- ✅ Identified boroughs with **highest ROI listings** (Queens, Brooklyn) based on price-to-rating ratio
- ✅ Found that listings with **>300 days availability** received **35–50% fewer reviews** than those with <150 days (demand saturation insight)
- ✅ Visualized 8+ charts including bar plots, box plots, heatmaps, and scatter plots to back findings
- ✅ Developed 11+ derived features such as price per guest, review month, and host type to uncover hidden patterns and support decision-making
---

## 📊 Visual Insights Included
- Bar plots: Room type vs borough, price distributions  
- Box plots: Review scores, price spread by category  
- Heatmaps: Feature correlation (price, reviews, availability)  
- Scatter plots: Price vs location, review vs availability  
- Pie charts: Room type share, listing counts per borough  

---

## 📌 Business Insights
- 💰 **Manhattan** has the highest price range but uneven satisfaction scores  
- 🛏️ **Private rooms** are most affordable in **Queens** and **Bronx**, with above-average review consistency  
- 🔁 Listings with **higher availability (>300 days)** tend to have **lower review activity**, signaling potential oversupply  
- 📉 **Listings with few reviews & low scores** cluster in low-demand neighborhoods like Staten Island

---

## 🛠️ Tools Used
- Python (Jupyter Notebook)  
- Pandas, NumPy  
- Seaborn, Matplotlib  
