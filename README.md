# Global Water Risk Assessment for Manufacturing Site Selection

*A Business Intelligence Case Study using Power BI*

---

# Overview

Manufacturing site selection has traditionally been driven by economic indicators such as GDP, market size, and industrial capability. However, increasing water scarcity has become a critical operational risk that can significantly impact production continuity, supply chain resilience, and long-term sustainability.

This project demonstrates how **environmental sustainability can be integrated with economic performance** to support strategic manufacturing site selection.

Using **Power BI**, I developed an interactive Business Intelligence dashboard that evaluates **164 countries** by combining water stress, GDP, manufacturing intensity, and population into a unified decision-support framework.

---

# Business Problem

Imagine advising a global manufacturing company planning its next production facility.

Should the decision be based solely on economic strength, or should environmental risks such as water scarcity also influence long-term investment decisions?

This project addresses that question by combining environmental and economic indicators to identify manufacturing locations that offer both growth potential and operational resilience.

---

# Project Highlights

- Analyzed **164 countries** using environmental and economic indicators
- Designed a **4-page interactive Power BI dashboard**
- Developed a custom **Manufacturing Expansion Index**
- Integrated multiple public datasets into a unified analytical model
- Delivered executive-level business recommendations

---

# Dataset

The dashboard combines publicly available global datasets from:

- **World Bank** – GDP (Current US$)
- **World Bank** – Manufacturing Value Added (% of GDP)
- **World Bank** – Population
- **World Resources Institute (Aqueduct)** – Water Stress

### Data Preparation

The data was transformed and modeled using **Power Query** and **DAX**.

Preparation included:

- Cleaning and validating datasets
- Standardizing country names
- Creating data relationships
- Developing calculated measures
- Building a composite Manufacturing Expansion Index

---

# Dashboard Walkthrough

## Home

The landing page provides intuitive navigation to each section of the dashboard.

![Home](Images/home%20page.png)

---

## Page 1 – Global Water Risk Overview

This page provides a global view of water stress and highlights countries facing the highest environmental risk.

### Key Components

- Water Risk Distribution
- Global Water Stress Map
- Top High Water Risk Countries
- Key Performance Indicators
- Interactive Filters

### Business Insight

Approximately **29% of assessed countries** fall into the High or Extremely High Water Stress category, demonstrating the importance of incorporating environmental sustainability into manufacturing expansion decisions.

![Page 1](Images/page%201.png)

---

## Page 2 – Economic & Manufacturing Opportunity Assessment

This page evaluates manufacturing potential by combining economic performance with industrial capability and sustainability.

### Key Components

- Top GDP Countries
- Manufacturing Intensive Economies
- Manufacturing Expansion Index
- Regional Manufacturing Opportunity Analysis

### Manufacturing Expansion Index

A composite score was developed using the following weighted criteria:

| Metric | Weight |
|---------|-------:|
| GDP | 40% |
| Population | 20% |
| Manufacturing (% of GDP) | 15% |
| Inverse Water Stress | 25% |

### Business Insight

Economic strength alone does not guarantee long-term manufacturing suitability. Countries that balance industrial capability with lower environmental risk provide stronger opportunities for sustainable expansion.

![Page 2](Images/page%202.png)

---

## Page 3 – Executive Recommendations

The final dashboard translates analytical findings into actionable business recommendations.

### Key Sections

- Executive Summary
- Priority Manufacturing Markets
- Markets Requiring Risk Mitigation
- Strategic Recommendations
- Business Conclusion

### Business Insight

The analysis identifies countries offering the strongest balance between economic opportunity and environmental sustainability while highlighting regions where water-risk mitigation strategies should accompany future investments.

![Page 3](Images/page%203.png)

---

# Key Findings

- **29%** of assessed countries face High or Extremely High Water Stress.
- Manufacturing capability is concentrated within a relatively small number of economies.
- Economic size alone is insufficient for long-term manufacturing site selection.
- Environmental sustainability should complement traditional financial indicators when evaluating expansion opportunities.

---

# Technologies Used

- Microsoft Power BI
- DAX
- Power Query
- Microsoft Excel

---

# Business Value

This project demonstrates how Business Intelligence can support strategic decision-making by integrating environmental sustainability with traditional economic indicators.

Rather than evaluating countries solely on economic performance, the dashboard provides a balanced framework that enables more informed manufacturing expansion decisions.

---
