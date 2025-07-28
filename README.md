# Campaign Performance Modelling

A data-driven project exploring how to evaluate and optimize the performance of a marketing campaign using uplift analysis, A/B testing, and customer segmentation. This end-to-end workflow simulates a real-world business case faced by marketing teams at banks or large enterprises.

---

## Project Overview

This project simulates the launch of a marketing campaign and applies statistical and machine learning techniques to analyze its impact on customer behavior.

### Objectives:
- Evaluate the **effectiveness of a marketing campaign** using A/B testing and uplift modeling.
- Identify **customer segments** that respond differently to campaigns.


---

## Data Schema

The dataset columns and their descriptions are defined in the [`data/data_schema.yaml`](data/data_schema.yaml) and  [`data/data_schema.json`](data/data_schema.json) files.

---

## Techniques & Concepts

- A/B Testing & Lift Calculation  
- Uplift Modeling (Causal Inference)  
- Customer Segmentation with uplift score

---

## Tools Used
- **SQL**
- **Python**: pandas, numpy, scikit-learn, matplotlib, seaborn, scipy 
- **Jupyter Notebooks**  


---

## 📁 Project Structure
```
campaign-performance-modeling/
│
├── README.md
├── data/ # Synthetic customer & campaign dataset
| ├── campaign_data.csv
| ├── data_schema.json  
│ └── data_schema.yaml
|
├── 01_synthetic_campaign_marketing_data.ipynb  
├── 02_data_preprocessing.ipynb
├── 03_uplift_analysis.ipynb
└── 04_customer_segmenation.ipynb


```
