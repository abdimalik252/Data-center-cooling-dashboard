# Data Center Cooling Dashboard

This project is a simple decision-support dashboard for choosing efficient cooling methods in data centers based on environmental conditions.

The goal is to explore how factors like temperature, humidity, water availability, and energy cost affect cooling strategies in different regions.

---

## What it does

The dashboard allows you to:

- Select a country (e.g., Kenya, Germany)
- Adjust local conditions (temperature, humidity)
- Set water availability and energy cost
- Get a recommended cooling method:
  - Air Cooling
  - Liquid Cooling
  - Evaporative Cooling

It also shows:
- Key environmental metrics
- Comparison of energy use across methods
- A short explanation of why a method is suggested

---

##  Why this matters

Cooling is one of the biggest energy and water challenges in data centers.

Different regions face different constraints:
- Some areas have high temperatures
- Others have limited water resources
- Energy cost varies significantly

This project explores how cooling decisions can adapt to these differences.

---

##  Built with

- Python  
- Streamlit  
- Pandas  
- Plotly & Altair (for visualization)

---

##  How to run
1. Install dependencies:
```bash
pip install streamlit pandas plotly altair requests scikit-learn

2. Run the app:
```bash
streamlit run app.py
3. Open the link shown in the terminal (usually http://localhost:8501
)



##  Features
-Interactive dashboard
-Country-based environmental context
-Adjustable local conditions
-Energy comparison chart
-Explanation panel for recommendations

💡 Notes
This is a prototype project created for exploring sustainable technology ideas.


