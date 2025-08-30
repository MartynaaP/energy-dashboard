# Energy Consumption Dashboard (Power BI)

This dashboard consists of two report pages:

- **Global Overview** – presenting energy consumption and production data across all countries.  
- **Poland Focus** – providing a detailed analysis of Poland’s energy mix and trends.  

---

## Data Sources
The fact table was built from a consolidated dataset:
- [World Energy Consumption (Kaggle)](https://www.kaggle.com/datasets/pralabhpoudel/world-energy-consumption/data)  
- [Electricity Mix (Our World in Data)](https://ourworldindata.org/electricity-mix)  

The original dataset contained a wide range of variables, but for this project it was reduced and transformed to allow clear and focused analysis.

---

## Data Preparation & Modeling
- Used **Power Query** to clean and transform data, create new calculated columns, and prepare measures.  
- Designed measures to extract additional insights, such as:  
  - **Emission measure** – displays total global CO₂ emissions regardless of user filters, highlighting worldwide trends.  
  - **SortOrder** – ensures correct chronological ordering of categorical values on visualizations.  
- Applied conditional formatting, slicers, and filters to enhance interactivity and usability.  

---

## Key Insights
- In **2018**, the average **global per capita energy consumption** was **25.91 MWh**, while production reached **28.72 TWh**.  
- Users can explore specific countries and years using slicers, maps, or selection lists, dynamically updating the charts.  
- In the **Poland-focused report**, the dashboard highlights:  
  - A noticeable increase in renewable energy share after Poland joined the EU (**+3.4% in total**).  
  - The strongest reductions in energy consumption occurred during the **PRL (communist) period**.  
