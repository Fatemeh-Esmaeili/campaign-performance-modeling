# Campaign Performance Modelling

A data-driven project simulating how marketing teams in banks or large enterprises evaluate and optimize campaign effectiveness using **uplift analysis**, **A/B testing**, and **customer segmentation**.


---

## Project Overview

This end-to-end workflow simulates a marketing campaign launch, applies statistical and machine learning techniques, and provides insight into customer response behavior.

### Objectives:
- Evaluate the **true impact** of a marketing campaign using A/B testing and **uplift modeling*
- Segment customers based on their **response patterns and predicted uplift scores**
- Recommend **data-driven targeting strategies** to optimize campaign ROI

## Key Insights & Takeaways

- Customers in **Segment A** showed significantly higher uplift, suggesting a strong positive response to the campaign
- Uplift modeling revealed that **only --- of customers** benefit from targeting — enabling smarter campaign focus
- Random targeting would waste budget? on the **do-not-disturb** or **negative uplift** groups
- Visualizations (uplift curves, response distributions) highlight the performance difference between treatment and control groups

---

## Data Schema

The dataset columns and their descriptions are defined in the [`data/data_schema.yaml`](data/data_schema.yaml) and  [`data/data_schema.json`](data/data_schema.json) files.

---

## Techniques & Concepts

- **A/B Testing** and **Lift Analysis**
- **Uplift Modeling** with Causal Inference techniques
- **Customer Segmentation** using uplift scores and behavioral features

---

## Tools Used
- **SQL** – for querying and structuring campaign data
- **Python** – `pandas`, `numpy`, `scikit-learn`, `scipy`, `matplotlib`, `seaborn`, `causalml`
- **Jupyter Notebooks** – for step-by-step workflow and analysis

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
