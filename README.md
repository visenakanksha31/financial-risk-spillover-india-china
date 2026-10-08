
# Financial Risk Spillover Between Banking and Fintech Sectors: India vs China

> **A Comparative Study Using VaR, CoVaR, Delta CoVaR, Volatility, Correlation framework**
---

## 📌 Project Overview

This project investigates **financial risk, interconnectedness, and potential risk spillovers between Banking and Fintech sectors in India and China**.

The analysis combines market-risk and systemic-risk measures with interactive **Power BI dashboards** to examine how the two sectors behave under normal and stressed market conditions.

### Study Period

**2023–2024**

### Market Components

| Country | Sector |
|---|---|
| 🇮🇳 India | Banking |
| 🇮🇳 India | Fintech |
| 🇨🇳 China | Banking |
| 🇨🇳 China | Fintech |

---

## 🎯 Research Objectives

The main objectives of this project are:

- Measure downside market risk using **Value at Risk (VaR)**.
- Examine conditional systemic risk using **CoVaR**.
- Measure incremental conditional risk using **Delta CoVaR**.
- Analyze sector-level **volatility and correlation**.
- Compare Banking–Fintech risk characteristics between **India and China**.
- Extend the analysis using the **Diebold–Yilmaz spillover framework**.
- Present findings through interactive **Power BI dashboards**.

---
## 🛠️ Tools

- Power BI
- DAX
- Power Query
- Data Cleaning using Python
- Statistical Analysis
- Financial Risk Analysis
- VAR Modelling
- MS Excel

---

# 🔬 Methodology

## 1. Value at Risk (VaR)

**Value at Risk (VaR)** estimates potential downside loss at a specified confidence level.

It is used to compare the downside risk of:

- Indian Banking
- Indian Fintech
- Chinese Banking
- Chinese Fintech

---

## 2. Conditional Value at Risk (CoVaR)

**CoVaR** measures the risk of one sector conditional on another sector being under financial stress.

The analysis considers:

- Indian Fintech conditional on Indian Banking stress
- Indian Banking conditional on Indian Fintech stress
- Chinese Fintech conditional on Chinese Banking stress
- Chinese Banking conditional on Chinese Fintech stress

---

## 3. Delta CoVaR

**Delta CoVaR** measures the change in conditional risk between normal and stressed conditions.

It helps assess the incremental risk associated with stress in the conditioning sector.

---

## 4. Volatility

Volatility measures fluctuations and uncertainty in financial returns.

The dashboards include:

- Average volatility
- Rolling volatility
- Banking vs Fintech volatility comparisons

---

## 5. Correlation

Correlation measures the degree of linear co-movement between Banking and Fintech returns.

Correlation analysis is performed for:

- India
- China
- Combined four-market analysis

> **Note:** Correlation indicates co-movement/dependence and does not by itself establish causal risk transmission.

---

## 6. Normalized Index

A normalized index with a common base value is used to compare the relative movement of selected market series over time.

---


---

# 📊 Power BI Dashboards

## 🇮🇳 Dashboard 1 — Indian Banking vs Fintech Risk

### Key Components

- Average Banking Volatility
- Average Fintech Volatility
- Correlation
- Maximum CoVaR
- Normalized Index
- Rolling Volatility
- Correlation Heatmap
- Risk Metric Table

### Preliminary Observations

| Metric | India |
|---|---:|
| Banking–Fintech Correlation | **0.97** |
| Banking Average Volatility | **15.29%** |
| Fintech Average Volatility | **14.89%** |

These are preliminary dashboard observations and are subject to validation through the final statistical analysis.

---

## 🇨🇳 Dashboard 2 — Chinese Banking vs Fintech Risk

### Key Components

- Average Banking Volatility
- Average Fintech Volatility
- Correlation
- Maximum CoVaR
- Normalized Index
- Rolling Volatility
- Correlation Heatmap
- Risk Metric Table

### Preliminary Observations

| Metric | China |
|---|---:|
| Banking–Fintech Correlation | **0.24** |
| Banking Average Volatility | **17.27%** |
| Fintech Average Volatility | **39.54%** |

The preliminary results indicate substantially higher volatility in the Chinese Fintech series compared with Chinese Banking during the displayed period.

---

## 🌏 Dashboard 3 — India vs China: Systemic Risk & Contagion Analysis

### Key Components

- India Correlation
- China Correlation
- Banking and Fintech Volatility
- Delta CoVaR Comparison
- VaR vs CoVaR
- Correlation Heatmap
- Summary Risk Metrics

This dashboard integrates the country-level analysis into a comparative framework.

---

# 📈 Preliminary Findings

## 🇮🇳 India

Indian Banking and Fintech display strong co-movement, with correlation of approximately **0.97**.

### Displayed Average Volatility

- Banking: **15.29%**
- Fintech: **14.89%**

---

## 🇨🇳 China

Chinese Banking and Fintech display comparatively lower correlation, approximately **0.24**.

### Displayed Average Volatility

- Banking: **17.27%**
- Fintech: **39.54%**

---

## 🇮🇳 vs 🇨🇳 India–China Comparison

The preliminary analysis suggests different patterns of Banking–Fintech interconnectedness:

- India shows substantially stronger Banking–Fintech co-movement.
- China shows substantially higher Fintech volatility.
- Conditional risk measures indicate differences in sector-level risk relationships.

> **Important:** These observations are preliminary and should not be treated as final causal conclusions until the complete econometric analysis is performed.

---

# 🧮 Analytical Workflow

```text
Financial Market Data
        ↓
Data Cleaning & Transformation
        ↓
Daily Returns
        ↓
Volatility | Correlation | VaR
        ↓
CoVaR → Delta CoVaR
        ↓
VAR / Connectedness Framework
        ↓
India vs China Comparison
        ↓
Power BI Dashboards

<img width="1330" height="742" alt="Image" src="https://github.com/user-attachments/assets/080f3b54-be11-46e1-b920-a178ba995c5c" />
