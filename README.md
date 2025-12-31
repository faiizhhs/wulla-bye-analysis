# AI-Driven Automation Risk and Adaptive Capacity in ASEAN

## TL;DR
This project maps ASEAN countries along two dimensions:
- **Automation Exposure** (sectoral employment structure)
- **Adaptive Capacity** (institutions, human capital, innovation)

Using PCA on cross-country indicators, the analysis shows that exposure and capacity are distinct, and that several ASEAN countries face future automation risks despite low current exposure.


## Overview

This project examines how ASEAN countries differ in their exposure to AI-driven automation and their capacity to adapt to technological disruption. Rather than predicting job losses or estimating causal effects, the analysis adopts a **risk-mapping and structural diagnostics approach**, identifying cross-country patterns using multivariate statistical methods.

The project contributes to policy discussions by **empirically separating automation exposure from adaptive capacity**, two dimensions that are often conflated in debates on the future of work and digital transformation.

---

## Research Question

**How do ASEAN countries differ in their levels of AI-driven automation exposure and adaptive capacity, based on economic structure, institutions, and human capital?**

More specifically:

- Are countries with higher exposure to automation also better equipped to adapt?
- Can exposure and resilience be empirically distinguished using cross-country indicators?

---

## Conceptual Framework

This study conceptualizes automation-related risk along **two distinct but related dimensions**:

### 1. Automation Exposure

Automation exposure is proxied through **sectoral employment structure**, particularly employment in industry. This sector is more likely to embed AI-enabled automation through production technologies, machinery, and capital equipment, making them relevant for early-stage automation risk.

### 2. Adaptive Capacity

Adaptive capacity reflects a country’s ability to absorb, adjust to, and benefit from technological change. It is captured through structural and institutional indicators, including:

- **Institutional quality** (government effectiveness, regulatory quality)
- **Human capital** (Human Capital Index)
- **Innovation capacity** (R&D expenditure)
- **Level of economic development** (GDP per capita)

This distinction allows the analysis to move beyond a single “risk ranking” and toward a **two-dimensional typology** of countries.

---

## Data and Indicators

The analysis combines publicly available cross-country indicators, primarily from the World Bank Data.

Key variables include:

- Manufacturing employment (% of total employment)
- Government effectiveness
- Regulatory quality
- Human Capital Index (HCI)
- R&D expenditure (% of GDP)
- GDP per capita (constant USD)

Countries with insufficient data coverage are excluded, and remaining missing values are handled using **median imputation**.

---

## Methodology

The core analytical method is **Principal Component Analysis (PCA)**.

### Why PCA?

- To reduce multiple correlated indicators into a smaller set of interpretable dimensions
- To assess whether **automation exposure and adaptive capacity emerge as distinct structural axes** across ASEAN countries

### Analytical Steps

1. Data cleaning and preprocessing  
2. Standardization of indicators  
3. PCA to extract principal components  
4. Interpretation of component loadings  
5. Visualization of countries along the first two principal components  

The first two principal components are interpreted as:

- **PC1: Adaptive Capacity**
- **PC2: Automation Exposure**

Clustering is used only as an **exploratory tool** and is not the primary basis for interpretation.

---

## Key Findings

- Automation exposure and adaptive capacity emerge as **empirically distinct dimensions** in ASEAN.
- Higher exposure to automation does **not** automatically imply stronger adaptive capacity.
- Several countries exhibit **low current exposure but also low adaptive capacity**, indicating vulnerability if industrial upgrading and AI adoption accelerate.
- A small number of countries combine **high exposure with high adaptive capacity**, suggesting greater readiness for AI-driven structural change.

Overall, the findings challenge simplified narratives that equate industrialization or technological exposure with preparedness.

---

## Policy Implications

- **Low current exposure should not be interpreted as low long-term risk.**
- Countries with limited adaptive capacity may face greater disruption as AI adoption expands.
- Strengthening institutions, skills formation, and innovation systems is critical **before** exposure intensifies.
- Regional cooperation can play an important role in supporting adaptive capacity in lower-income ASEAN members.

Rather than offering country-specific prescriptions, the analysis highlights **structural patterns** that can inform comparative policy discussions.

---

## Limitations

- Employment in industry is used as a proxy for early-stage automation exposure and does not capture AI impacts in services or non-routine cognitive tasks.
- The analysis is descriptive and exploratory; it does not establish causal relationships.
- Cross-country indicators may mask substantial within-country heterogeneity.

---

## Notes

This project is intended as a **structural diagnostics exercise** rather than a forecasting or causal inference study. Results should be interpreted as indicative patterns rather than definitive rankings.
