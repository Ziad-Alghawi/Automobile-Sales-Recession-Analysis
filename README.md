#  Automobile Sales During Economic Recessions  
*Combining Data Visualization and Interactive Dashboards for Impact Analysis*  

![Dashboard Preview](assets/YearlyReportgraphs.png)  
![Dashboard Preview](assets/RecessionReportgraphs.png) 

---

## 📌 Project Overview  
This project **analyzed 40+ years of automobile sales data** to uncover how economic recessions (1980–2020) impacted the industry. Implemented in **two key phases**:  

### **Phase 1: Advanced Data Visualizations**  
*Tools: Python (Pandas, Matplotlib, Seaborn)*  
- Created **10+ interactive plots** to identify trends:  
  - 📉 Line charts: Yearly sales fluctuations during recessions.  
  - 🍏 Bubble plots: Impact of seasonality on sales.  
  - 📊 Bar/pie charts: Advertising spend by vehicle type.  
- **Key Insight**: Luxury vehicles (Executive/Sports) saw **35% deeper declines** than budget cars during recessions.  

### **Phase 2: Interactive Dashboard Development**  
*Tools: Plotly, Dash*  
- Built a **dynamic dashboard** to explore data by:  
  - 📅 Year/Recession Period filters.  
  - 🚙 Vehicle Type comparisons.  
  - 📈 GDP vs. Unemployment Rate correlations.  
- **Feature**: Directors can drill into specific crises (e.g., 2008 financial crash).  

---

## 🔍 Key Insights  
- **2008 Recession**: Sales dropped **30% YoY** (worst since 1980).  
- **Consumer Behavior**: Confidence index strongly correlated (*r = 0.72*) with sales volume.  
- **Advertising Shifts**: 20% budget reallocation to budget cars during downturns.  

---

## 🛠️ Tech Stack  
- **Data Analysis**: Python (Pandas, NumPy)  
- **Visualization**: Matplotlib, Seaborn, Plotly  
- **Dashboard**: Dash, HTML/CSS  
- **Data**: Synthetic dataset (1980–2023) with `GDP`, `Unemployment_Rate`, etc.  


 **✨ Implementation Details:**  
- **Data Pipeline:** Automated cleaning with `Pandas` (handled 12% missing values in `Consumer_Confidence`)  
- **Dashboard Architecture:**  
  ```mermaid
  graph LR
    A[User Input] --> B(Dash Callbacks)
    B --> C[Plotly Graphs]
    C --> D[HTML/CSS Layout]
