#  Data Center Cooling Dashboard

![Python](https://img.shields.io/badge/Python-3.9+-blue)
![Streamlit](https://img.shields.io/badge/Streamlit-App-red)
![Status](https://img.shields.io/badge/Status-Prototype-orange)
![Focus](https://img.shields.io/badge/Focus-Sustainable%20Tech-green)

A simple decision-support dashboard for selecting efficient data center cooling strategies based on environmental conditions.

---

##  Overview

This project explores how key environmental and resource factors influence cooling decisions in data centers across different regions.

It focuses on:

* 🌡️ Temperature
* 💧 Humidity
* 🚰 Water availability
* ⚡ Energy cost

The goal is to simulate real-world trade-offs and promote more sustainable infrastructure decisions.

---

##  What It Does

The dashboard allows users to:

* Select a country (e.g., Kenya, Germany)
* Adjust environmental conditions
* Define water availability and energy cost
* Get a recommended cooling method:

  * Air Cooling
  * Liquid Cooling
  * Evaporative Cooling

###  Outputs

* Key environmental metrics
* Energy usage comparison across methods
* Explanation for the selected cooling strategy

---

##  Why This Matters

Cooling is one of the biggest challenges in data center operations.

Different regions face different constraints:

* High temperatures increase cooling demand
* Water scarcity limits certain technologies
* Energy prices vary significantly

This project demonstrates how cooling strategies can adapt to local conditions for better efficiency and sustainability.

---

##  Built With

* Python
* Streamlit
* Pandas
* Plotly
* Altair
* Scikit-learn

---

##  How to Run

### 1. Install Dependencies

```bash
pip install streamlit pandas plotly altair requests scikit-learn
```

### 2. Run the App

```bash
streamlit run app.py
```

### 3. Open in Browser

Visit:

```
http://localhost:8501
```

---

##  Features

* Interactive dashboard
* Country-based environmental context
* Adjustable input parameters
* Energy comparison visualization
* Recommendation explanation panel

---


##  Future Improvements

* Add real-world climate datasets
* Integrate live weather APIs
* Expand cooling method options
* Optimize recommendation algorithm

---

## 💡 Notes

This is a prototype project built to explore sustainable technology concepts in data center design.

---

##  Author

Your Name
GitHub: https://github.com/abdimalik252
