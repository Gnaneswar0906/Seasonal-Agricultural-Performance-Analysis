<div align="center">

# 🌾 Seasonal Agriculture Performance Analysis

### <i>An End-to-End Agronomic Analytics & Statistical Modeling Framework</i>

<br>

<p>
<b>Understanding seasonal variations in agricultural productivity, environmental conditions, resource utilization, and economic performance.</b>
</p>

<br>

<img src="https://img.shields.io/badge/Python-3.9%20%7C%203.10%20%7C%203.11-blue?logo=python&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-2.0%2B-150458?logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/NumPy-1.24%2B-013243?logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/SciPy-1.10%2B-8CAAE6?logo=scipy&logoColor=white">
<img src="https://img.shields.io/badge/Statsmodels-0.14%2B-blueviolet">
<img src="https://img.shields.io/badge/Matplotlib-3.7%2B-orange?logo=matplotlib">
<img src="https://img.shields.io/badge/Seaborn-0.12%2B-4c72b0">
<img src="https://img.shields.io/badge/License-MIT-yellow.svg">

<br><br>

<table>
<tr>
<td align="center"><b>4,000</b><br>Farm Units</td>
<td align="center"><b>8</b><br>States</td>
<td align="center"><b>10</b><br>Districts</td>
<td align="center"><b>8</b><br>Crop Varieties</td>
<td align="center"><b>28</b><br>Features</td>
</tr>
</table>

</div>

---

## 📌 Executive Overview

<div align="justify">

Agricultural productivity is strongly influenced by seasonal variations in temperature, precipitation, soil conditions, resource availability, irrigation practices, crop selection, and operational costs.

This project performs a comprehensive analysis of **4,000 agricultural farm units across India**, covering **8 states, 10 districts, and 8 crop varieties**.

The study compares the three major agricultural seasons — **Kharif, Rabi, and Zaid** — to identify meaningful differences in productivity, environmental conditions, resource utilization, and financial performance.

Unlike a purely descriptive analysis, this project combines **exploratory data analysis, statistical hypothesis testing, correlation analysis, regression modeling, factorial ANOVA, effect-size estimation, and anomaly detection** to derive evidence-based agricultural insights.

</div>

---

## 🎯 Problem Statement

<div align="justify">

Raw agricultural data contains numerous environmental, operational, production, and financial variables. However, these variables alone do not clearly explain how agricultural performance changes across seasons.

The project therefore investigates:

* Seasonal differences in agricultural productivity
* Changes in environmental conditions
* Variations in water and input utilization
* Relationships between environmental factors and yield
* Seasonal differences in economic performance
* Regional and crop-specific seasonal behavior
* Unusual resource-consumption and financial patterns

The central objective is to identify **meaningful patterns, trends, relationships, and variations** that can support evidence-based seasonal agricultural planning.

</div>

---

## 🔬 Research Questions

<table>
<tr>
<th>ID</th>
<th>Research Question</th>
</tr>

<tr>
<td><b>AQ1</b></td>
<td>How do crop yield, production, water efficiency, and profit vary across Kharif, Rabi, and Zaid?</td>
</tr>

<tr>
<td><b>AQ2</b></td>
<td>Which environmental indicators distinguish the three seasonal farming conditions?</td>
</tr>

<tr>
<td><b>AQ3</b></td>
<td>How do water, NPK, pesticide usage, and irrigation practices change across seasons?</td>
</tr>

<tr>
<td><b>AQ4</b></td>
<td>What linear and non-linear relationships exist between environmental factors and crop yield?</td>
</tr>

<tr>
<td><b>AQ5</b></td>
<td>Does increasing input consumption generate proportional yield improvements?</td>
</tr>

<tr>
<td><b>AQ6</b></td>
<td>How do operating costs, revenue, profit margins, and loss rates vary seasonally?</td>
</tr>

<tr>
<td><b>AQ7</b></td>
<td>Are seasonal performance patterns consistent across different states?</td>
</tr>

<tr>
<td><b>AQ8</b></td>
<td>Does crop type influence the effect of seasonality on agricultural performance?</td>
</tr>

</table>

---

## 🌦️ Seasonal Framework

<div align="center">

|           🌧️ Kharif          |          ❄️ Rabi         |          ☀️ Zaid          |
| :---------------------------: | :----------------------: | :-----------------------: |
|        Monsoon / Autumn       |      Winter / Spring     |           Summer          |
|         High rainfall         |     Moderate rainfall    |        Low rainfall       |
| Strongest overall performance | Intermediate performance | Highest resource pressure |

</div>

---

## 📊 Key Empirical Findings

<div align="center">

| Metric                |        🌧️ Kharif |       ❄️ Rabi |        ☀️ Zaid |
| :-------------------- | ----------------: | ------------: | -------------: |
| **Mean Yield**        |     **5.64 t/ha** |     5.08 t/ha |      4.67 t/ha |
| **Median Yield**      |     **1.95 t/ha** |     1.66 t/ha |      1.45 t/ha |
| **Water Consumption** |        6,094.0 m³ |    5,837.2 m³ | **6,423.1 m³** |
| **Water Efficiency**  | **5.91 t/1000m³** | 5.18 t/1000m³ |  4.44 t/1000m³ |
| **Mean Farm Profit**  |      **₹179,367** |       ₹88,197 |   **-₹26,592** |
| **Farms in Loss**     |            42.27% |        51.28% |     **64.52%** |
| **Rainfall**          |      **885.6 mm** |      486.2 mm |       198.8 mm |
| **Temperature**       |            27.8°C |        22.4°C |     **32.5°C** |

</div>

---

## 💡 Major Insights

### 🥇 1. Kharif Leads Overall Performance

Kharif demonstrates the highest mean and median crop yield and records the strongest average farm profitability among the three seasons.

### ☀️ 2. Zaid Exhibits a Resource-Efficiency Paradox

Zaid farms experience:

* Highest average temperature
* Lowest average rainfall
* Highest water consumption
* Lowest water efficiency
* Negative average farm profit
* Highest percentage of loss-making farms

This indicates significant resource and financial pressure during the summer season.

### 🌱 3. Crop Choice Mediates Seasonal Performance

The analysis identifies a strong **Season × Crop interaction**. High-value crops such as Sugarcane and Chilli demonstrate stronger economic performance, while cereals such as Rice, Wheat, and Maize experience severe losses under Zaid conditions.

### 🗺️ 4. Regional Seasonal Patterns Remain Relatively Stable

The **Season × State interaction** does not reach conventional statistical significance, indicating that broad seasonal performance patterns do not substantially reverse across the analyzed states.

### 💧 5. Irrigation Efficiency Matters

Flood irrigation contributes approximately **55.31% of extreme water-consumption anomalies**, highlighting the importance of efficient irrigation infrastructure.

---

## 🧪 Statistical Methodology

<div align="center">

```text
Data Distribution Analysis
          ↓
Assumption Diagnostics
          ↓
Parametric Testing
          ↓
Non-Parametric Validation
          ↓
Post-Hoc Comparisons
          ↓
Factorial ANOVA
          ↓
Effect Size Analysis
          ↓
Evidence-Based Interpretation
```

</div>

### Statistical Techniques

* **D'Agostino-Pearson Omnibus Test** — Normality
* **Q-Q Plots** — Distribution diagnostics
* **Levene's Test** — Variance homogeneity
* **Bartlett's Test** — Variance homogeneity
* **One-Way ANOVA** — Seasonal comparison
* **Kruskal-Wallis H-Test** — Non-parametric seasonal comparison
* **Mann-Whitney U Test** — Pairwise post-hoc analysis
* **Bonferroni Correction** — Multiple-comparison control
* **Two-Way Factorial ANOVA** — State/Crop interaction analysis
* **Pearson Correlation** — Linear relationships
* **Spearman Correlation** — Rank-based relationships
* **Polynomial Regression** — Non-linear and diminishing-return analysis

---

## 📈 Statistical Evidence

### Seasonal Yield Differences

```text
Kruskal-Wallis H = 68.6043
p = 1.267 × 10⁻¹⁵
```

The result provides strong statistical evidence of differences in seasonal yield distributions.

### Season × State

```text
F = 1.6889
p = 0.0511
```

The seasonal pattern does not show a conventionally significant interaction with state.

### Season × Crop

```text
F = 19.4468
p = 4.25 × 10⁻⁴⁸
```

The strong interaction indicates that seasonal effects depend substantially on crop type.

---

## 🔄 End-to-End Analytical Pipeline

<div align="center">

```text
┌──────────────────────────────┐
│ 1. Environment & Data Input  │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│ 2. Data Cleaning             │
│    & Feature Engineering     │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│ 3. Exploratory Data Analysis │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│ 4. Seasonal Comparison       │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│ 5. Correlation & Regression  │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│ 6. State & Crop Interaction  │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│ 7. Statistical Validation    │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│ 8. Outlier & Anomaly Mining  │
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│ 9. Insights & Recommendations│
└──────────────┬───────────────┘
               ↓
┌──────────────────────────────┐
│ 10. Final Notebook           │
└──────────────────────────────┘
```

</div>

---

## ⚙️ Feature Engineering

The analysis creates domain-specific variables to improve interpretation:

| Feature                      | Purpose                                             |
| ---------------------------- | --------------------------------------------------- |
| `Profit_Margin_pct`          | Measures relative financial performance             |
| `Verified_Land_Productivity` | Represents productivity relative to cultivated area |
| `Total_NPK_kg_ha`            | Aggregates major fertilizer nutrients               |

The preprocessing workflow also performs missing-value treatment, categorical standardization, record validation, and target-leakage prevention.

---

## 🚨 Outlier & Anomaly Detection

Multiple approaches are used to identify unusual observations:

* Tukey's **1.5 × IQR** method
* Modified Z-score using MAD
* Extreme water-consumption profiling
* Loss-making farm identification
* Irrigation-method analysis
* Soil and district-level anomaly investigation

---

## 🌾 Evidence-Based Recommendations

<table>
<tr>
<th>Area</th>
<th>Recommendation</th>
</tr>

<tr>
<td><b>🌱 Zaid Crop Planning</b></td>
<td>Reduce water-intensive cereal cultivation during Zaid and consider drought-tolerant or higher-margin alternatives.</td>
</tr>

<tr>
<td><b>💧 Water Management</b></td>
<td>Promote efficient irrigation systems such as drip and sprinkler irrigation in water-stressed conditions.</td>
</tr>

<tr>
<td><b>🧪 Fertilizer Optimization</b></td>
<td>Use precision fertilization approaches because returns begin to plateau beyond approximately 300 kg/ha Total NPK.</td>
</tr>

<tr>
<td><b>💰 Financial Risk</b></td>
<td>Consider revenue, input-cost volatility, and market conditions alongside yield when designing agricultural risk-management strategies.</td>
</tr>

</table>

---

## 🛠️ Technology Stack

<div align="center">

|    Technology   | Role                        |
| :-------------: | --------------------------- |
|    🐍 Python    | Core analytical environment |
|    🐼 Pandas    | Data manipulation           |
|     🔢 NumPy    | Numerical computation       |
|     📐 SciPy    | Statistical analysis        |
|  📊 Statsmodels | Statistical modeling        |
|  📈 Matplotlib  | Visualization               |
|    🎨 Seaborn   | Statistical visualization   |
|    📓 Jupyter   | Analysis documentation      |
| ☁️ Google Colab | Execution environment       |

</div>

---

## 🚀 Getting Started

### Requirements

```text
Python 3.9 / 3.10 / 3.11
JupyterLab or Google Colab
```

### Install Dependencies

```bash
pip install pandas numpy scipy statsmodels matplotlib seaborn
```

### Python Packages

```text
pandas>=2.0.0
numpy>=1.24.0
scipy>=1.10.0
statsmodels>=0.14.0
matplotlib>=3.7.0
seaborn>=0.12.0
```

---

## 📓 Project Deliverable

The complete analytical workflow is implemented in a **Jupyter Notebook**, including:

<div align="center">

`Data Preparation` → `EDA` → `Seasonal Analysis` → `Statistical Testing` → `Anomaly Detection` → `Insights` → `Recommendations`

</div>

The notebook includes validation checks for data integrity, null handling, record retention, and feature consistency.

---

## 📌 Conclusion

<div align="justify">

The analysis demonstrates that agricultural performance varies considerably across seasons. **Kharif generally exhibits stronger productivity and financial performance**, whereas **Zaid experiences greater water demand, lower water efficiency, and higher financial risk**.

The statistical analysis further demonstrates that crop type plays an important role in determining how seasonal conditions affect agricultural outcomes. Consequently, effective agricultural planning should consider **season, crop selection, environmental conditions, irrigation infrastructure, resource efficiency, and economic performance together**.

</div>

---

<div align="center">

### 🌾 Data-Driven Insights for Better Seasonal Agricultural Planning

<b>VOIS AICTE Batch 1 • Major Project 2026–2027</b>

<br><br>

⭐ <i>Explore the notebook to reproduce the complete analysis.</i>

</div>

---

## 📜 License

This project is licensed under the **MIT License**.
