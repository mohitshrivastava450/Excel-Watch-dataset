# 📊 Flipkart Watch Dataset Analysis

## 📌 Project Overview
This project analyzes a dataset of watches scraped from **Flipkart** using a Chrome web scraper. The goal is to identify suitable brands, price ranges, and discount patterns that can help a watch shop make informed stocking and pricing decisions.

---

## 🎯 Mission & Vision
- Provide summarized insights from the Flipkart watch dataset.  
- Recommend suitable brands and price ranges for maximizing sales.  
- Highlight customer preferences based on ratings and discounts.  

---

## 📂 Dataset Description
The dataset includes the following attributes:
- **Name** – Watch name  
- **Brand** – Manufacturer/brand  
- **Original Price** – Listed price  
- **Discount** – Percentage discount offered  
- **Special Price** – Final selling price after discount  
- **Rating** – Average customer rating  
- **Rating Count** – Number of ratings received  

---

## 🛠️ Data Preprocessing
- Dropped unnecessary columns (e.g., scraper metadata, URLs).  
- Cleaned discount column (removed "off" and converted to percentage).  
- Cleaned rating count column (removed text like "Ratings and Reviews").  

---

## 🔄 Data Transformation
- Converted discount values into numeric percentages.  
- Split and cleaned rating count values for analysis.  

---

## 📊 Key Visualizations & Insights
### ⭐ Top 5 Brands (by Rating)
- Allen Solly (4.35)  
- MATRIX (4.14)  
- LOIS CARON (4.04)  
- PROVOGUE (3.97)  
- RUSTET (3.95)  

**Recommendation:** Keep these brands in stock for higher customer satisfaction.

---

### 💰 Preferred Price Range
- Most watches (271) fall between **₹169 – ₹669**.  
- **Recommendation:** Maintain stock in the **₹150 – ₹700** range.  

---

### 🏆 Highest Rated Watches
- Analog Watch - Men’s Luxury Stainless Steel (Rating: 5.0)  
- Waterproof Kids Digital Watch (Rating: 4.7)  
- Elliot Analog Watch - Women (Rating: 4.6)  
- Vyb Diva Analog Watch - Women (Rating: 4.6)  

---

### 💵 Average Price of Top Brands
| Brand       | Avg. Special Price (₹) |
|-------------|-------------------------|
| Allen Solly | 1398                   |
| LOIS CARON  | 299                    |
| MATRIX      | 295                    |
| PROVOGUE    | 307                    |
| RUSTET      | 388                    |

---

### ⚠️ Lowest Rated Brands
- Forum (3.2)  
- SABR (3.6)  
- RLS (3.6)  
- Shafs (3.7)  
- KILLER (3.77)  

**Recommendation:** Avoid stocking these brands due to poor customer feedback.

---

### 🎁 Top Discounts Offered
- 82% – 88% off (most frequent discount range).  
- **Recommendation:** Highlight watches with **80–90% discounts** to attract customers.  

---

## 📈 Summary of Results
- **Total Watches:** 371  
- **Total Brands:** 64  
- **Highest Priced Watch:** ₹8219  
- **Lowest Priced Watch:** ₹169  
- **Best Price Range:** ₹150 – ₹700  
- **Best Brands:** Allen Solly, MATRIX, LOIS CARON, PROVOGUE, RUSTET  
- **Worst Brands:** Forum, SABR, RLS, Shafs, KILLER  

---

## ✅ Recommendations
- Stock watches from **top-rated brands**.  
- Focus inventory in the **₹150 – ₹700** price range.  
- Promote **highest-rated watches** for better sales.  
- Avoid stocking **lowest-rated brands**.  
- Leverage **80–90% discount offers** to attract buyers.  

---

## 📌 How to Use
1. Clone the repository.  
2. Review the dataset and preprocessing steps.  
3. Explore the visualizations for insights.  
4. Apply recommendations to guide stocking and pricing strategies.  

---

## 🙏 Acknowledgements
- Data scraped from **Flipkart** using Chrome Web Scraper.  
- Analysis inspired by retail decision-making needs.  
