# 📊 Eleckart MMM

**Eleckart MMM (Marketing Mix Modeling)** is a data-driven project designed to measure and optimize the impact of marketing and non-marketing factors on Eleckart’s business KPIs (such as sales, conversions, or revenue).
It helps identify which marketing channels drive the most ROI and supports smarter budget allocation.

---

## 🧠 Project Overview

Marketing Mix Modeling (MMM) uses regression-based techniques to **quantify the effect of media spends, pricing, seasonality, and other variables** on business outcomes.
This project focuses on:

* Measuring the **incremental impact** of each marketing channel.
* Modeling **adstock and saturation** effects for digital and offline media.
* Providing actionable insights for **media planning and forecasting**.

---

## ⚙️ Key Components

| Component                            | Description                                                                  |
| ------------------------------------ | ---------------------------------------------------------------------------- |
| **Adstock Transformation**           | Captures carryover effects of media over time (decay function).              |
| **Lagged Features**                  | Incorporates delayed media impact using lag transformations.                 |
| **Modelling Approach**               | Uses additive regression / multiplicative regression / distributed lag models|

---

## 🧮 Methodology

1. **Data Cleaning & Integration** – Combine spend, KPI, and control data.
2. **Adstocking** – Apply decay functions to media variables.
4. **Feature Selection** – Remove multicollinearity and select significant predictors.
5. **Model Fitting** – Use regression.

---

## 🧰 Tech Stack

* **Language:** Python (3.10+)
* **Libraries:**

  * `pandas`, `numpy` – Data wrangling
  * `scikit-learn`, `statsmodels` – Modeling
  * `matplotlib`, `seaborn`– Visualization
---


