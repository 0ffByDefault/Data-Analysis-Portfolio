# 📊 Data Analysis Project 1: Fictional PMO Business Sector Evaluation

---

## 🧾 Introduction

This report presents a comprehensive evaluation of project performance across various business sectors within a fictional Project Management Office (PMO) of a large technological consulting firm. 

> ⚠️ **Note:** All data contained herein is AI-generated for the purpose of demonstrating advanced data analysis and reporting capabilities.

The primary objective of this analysis is to assess the **"health" of the company's project portfolio**, identifying which sectors are excelling and which require strategic intervention. 

By moving beyond individual project tracking to **sector-level aggregation**, the PMO can make informed decisions regarding:
- Resource allocation  
- Risk management  
- Strategic planning  

---

## ⚙️ Methodology

The evaluation follows a structured methodology based on industry-standard Project Management metrics:

### Data Aggregation
Raw project-level data was categorized by business sector:
- E-Commerce  
- Clean Energy  
- EdTech  
- FinTech  
- Cybersecurity  
- Telecommunications  
- Healthcare IT  
- GovTech  
- Enterprise Software  
- Artificial Intelligence  

### KPI Calculation

For each sector, the following key performance indicators (KPIs) were calculated:

- **Average Cost Performance Index (CPI)** → Measures financial efficiency  
- **Average Schedule Performance Index (SPI)** → Measures adherence to timelines  
- **Budget Compliance** → Percentage of projects under budget  
- **To Complete Performance Index (TCPI)** → Efficiency required to complete remaining work  

### Grading System

A proprietary scoring model was applied:

Each KPI = **1 point (pass/fail)**  
Total possible score = **5 points**

#### Performance Thresholds

| KPI | Requirement |
|-----|------------|
| Cost Efficiency (CPI) | > 0.9 |
| Schedule Efficiency (SPI) | > 0.75 |
| Budget Compliance | < 50% projects over budget |
| Financial Buffer | ≥ 30% reserve |
| Resource Management (TCPI) | > 0.9 |

---

## 🛠 Skills Demonstrated

The insights in this report were derived using:

- **Advanced Formulas:**  
  UNIQUE, SUMIFS, AVERAGEIFS, Pivot Tables, RANDBETWEEN  

- **Data Transformation:**  
  Cleaning and structuring raw data for accuracy  

- **Comparative Analysis:**  
  Using Earned Value Management (EVM) metrics to benchmark sectors  

- **Insight Synthesis:**  
  Translating numerical outputs into executive-level insights  

---

## 📈 Sector Score Analysis

The scores are calculated based on:

- CPI > 0.9  
- SPI > 0.75  
- Budget Compliance (< 50% over budget)  
- Budget Reserve ≥ 30%  
- TCPI > 0.9  

---

---

## 📊 Visualizations

### 1. Sector Performance Scores

![Sector Performance Scores](https://quickchart.io/chart?c={type:'bar',
data:{
labels:['EdTech','FinTech','Cybersecurity','Telecom','Clean Energy','Healthcare IT','GovTech','E-Commerce','Enterprise','AI'],
datasets:[{
label:'Score (out of 5)',
data:[5,5,5,5,4,4,4,3,3,1]
}]
}
})

---

### 2. CPI vs SPI Comparison

![CPI vs SPI](https://quickchart.io/chart?c={type:'bar',
data:{
labels:['EdTech','FinTech','Cybersecurity','Telecom','Clean Energy','Healthcare IT','GovTech','E-Commerce','Enterprise','AI'],
datasets:[
{
label:'CPI',
data:[4.05,1.70,7.91,1.34,1.10,1.20,208.06,1.03,0.79,0.62]
},
{
label:'SPI',
data:[1.79,1.54,1.20,1.92,2.36,2.89,3.63,1.64,1.58,0.60]
}
]
}
})

---

### 3. Budget Reserve by Sector

![Budget Reserve](https://quickchart.io/chart?c={type:'bar',
data:{
labels:['EdTech','FinTech','Cybersecurity','Telecom','Healthcare IT','Enterprise'],
datasets:[{
label:'Budget Reserve (%)',
data:[47.3,42.1,61.5,42.7,50.6,47]
}]
}
})

---

### 4. Percentage of Projects Over Budget

![Over Budget Percentage](https://quickchart.io/chart?c={type:'bar',
data:{
labels:['Healthcare IT','GovTech','E-Commerce','Enterprise','AI'],
datasets:[{
label:'% Over Budget',
data:[63.64,50,66.67,71.43,80]
}]
}
})

---

### 5. Performance Distribution (Score Breakdown)

![Score Distribution](https://quickchart.io/chart?c={type:'pie',
data:{
labels:['Top (5/5)','Strong (4/5)','Moderate (3/5)','Underperforming (1/5)'],
datasets:[{
data:[4,3,2,1]
}]
}
})
