---
marp: true
theme: default
style: |
  section {
    background-color: #f9f9f9;
    font-family: 'Arial', sans-serif;
  }
  h1 {
    color: #1E90FF;
    border-bottom: 2px solid #000;
    padding-bottom: 10px;
  }
  h2 {
    color: #333;
    font-size: 1.2em;
  }
  .two-columns {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 20px;
  }
  footer {
    font-size: 12px;
  }
paginate: true
header: "**NYC TLC Taxi Trip Data Analysis**"
footer: "Hans Darmawan (JCDS2602) | April 2025"
---

<!-- Slide 1: Title -->
# 🚖 Analyzing Tipping Behavior in NYC Taxi Trips  
### *Insights from NYC TLC Trip Data*  
###### *Data-Driven Strategies for Drivers & Regulators*  

---

<!-- Slide 2: Overview -->
# **🔍 Overview**  
### **Presentation Structure**  
1. **Context:** Importance of tipping in NYC taxi ecosystem  
2. **Methodology:** Data sources and analytical approach  
3. **Findings:** Key patterns and actionable recommendations  

---

<!-- Slide 3: Background -->
# **📚 Background**  
### **NYC Taxi Industry**  
1. **Regulation:** TLC oversees 100K+ for-hire vehicles  
2. **Economics:** Tips comprise 20-30% of driver income  
3. **Market Shift:** Ride-share apps dominate digital tipping  

---

<!-- Slide 4: Gap Analysis -->
# **🔎 Gap Analysis**  
### **Research Opportunities**  
1. **Data Deficiency:** Limited studies on taxi tipping factors  
2. **Technology Gap:** Taxis lack automated tipping systems  
3. **Practical Need:** Drivers want data to optimize earnings  

---

<!-- Slide 5: Problem Statement -->
# **❓ Problem Statement**  
### **Research Focus**  
1. **Behavior:** How payment methods affect tipping  
2. **Operations:** Impact of trip/time variables  
3. **Geography:** Location-based tipping patterns  

---

<!-- Slide 6: Insight Questions -->
# **💭 Insight Questions**  
<div class="two-columns">

### **Payment & Trip Factors**
1. Cash vs. credit card tipping  
2. Trip distance vs. tip amount  
3. Trip duration vs. tip amount  

### **Temporal Patterns**
4. Daily tipping variations  
5. Hourly tipping trends  

### **Geographic Analysis**
6. Pickup borough influence  
7. Pickup zone differences  

### **Additional Factors**
8. Dropoff location impact  
9. Extra charges effect  
10. Tolls and surcharges  
11. Passenger count role  
</div>

---

<!-- Slide 7: Data Understanding -->
# **📊 Data Understanding**  
### **Dataset Profile**  
1. **Volume:** 68,211 trip records  
2. **Variables:** 20+ columns including fare, tip, location  
3. **Scope:** 2019-2020 yellow taxi trips  

---

<!-- Slide 8: Data Wrangling -->
# **🧹 Data Wrangling**  
### **Processing Steps**  
1. **Cleaning:** Handled missing data, outliers  
2. **Enhancement:** Added trip duration, geospatial features  
3. **Output:** 42,408 cleaned records for analysis  

---

<!-- Slide 9: EDA Framework -->
# **📈 EDA Framework**  
### **Analysis Approach**  
1. **Question:** Specific insight question  
2. **Visualization:** Supporting chart/graph  
3. **Finding:** Statistical result  
4. **Implication:** Practical recommendation  

---

<!-- Slide 10: Conclusion -->
# **🎬 Conclusion**  
### **Key Insights**  
1. **Payment:** Cards yield 100% higher tips  
2. **Timing:** Evenings/weekends most lucrative  
3. **Location:** Manhattan outperforms other boroughs  

---

<!-- Slide 11: Thank You -->
# **🙏 Thank You!**  
**Let's Connect:**  
📧 [hans@example.com] | 🔗 [LinkedIn](#)  
###### *Data Source: NYC TLC Trip Records | 2019-2020*  
