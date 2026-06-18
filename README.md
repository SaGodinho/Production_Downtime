# Production_Downtime

This project presents a data-driven analysis of a bottled drink manufacturing facility with the objective of identifying the main sources of productivity loss, operational waste, and equipment downtime. Using Lean Manufacturing and Six Sigma principles, the analysis combines production and downtime records to evaluate operational efficiency and uncover opportunities for process improvement.

The study focuses on quantifying downtime, evaluating process performance, identifying root causes of inefficiencies, and assessing Overall Equipment Effectiveness (OEE).

## Live Project

View the rendered notebook:

https://sagodinho.github.io/Production_Downtime/

## Repository

https://github.com/SaGodinho/Production_Downtime

---

## Project Overview

Manufacturing profitability depends heavily on maximizing productive machine time while minimizing operational waste and downtime. Excessive downtime directly reduces throughput, increases operational costs, and lowers equipment utilization.

This project aims to answer the following questions:

- **What are the main drivers of productivity loss?**
  Machine Failure and Inventory Shortage account for most downtime (a total of 40%) according to Pareto analysis- both non-added-value activities that are also not operator driven.
  
- **Are there operator-specific performance differences?**
  Analysis concluded that differences are not significant - competence is evenly spread across the workforce.
  
- **Do different products significantly affect production performance?**
  Cola 2L takes the most time to produce. If we normalize the values, Cola 2L and Cola 600ml managed to stay closer to the ideal production cycle time.
  
- **What Lean wastes are most prevalent?**
  Predominantly Waiting and Defect: the more delays (Waiting), the more rush there is afterwards to keep up, the higher the potential for mistakes (Defects). The more Defects, the more time needed on repair and rework (increasing waiting time).

### Improvement Opportunities
**Maintenance Optimization**
  
Implement Autonomous Maintenance (operator-led basic maintenance tasks)

Introduce preventive maintenance scheduling based on machine runtime

**Inventory & Material Flow**

Improve forecasting to reduce inventory shortages

Maintain buffer stock to avoid production stops

Optimize material positioning to reduce prep and waiting time

**Process Efficiency**

Standardize setup procedures

Reduce changeover and preparation delays

Improve workflow organization to minimize idle time


- **What is the operational state of the company?**

  With an Availability of ~64% , the manufacturing process could use improvement and is bellow typical industry standards. This means over a thrid of the time is lost and not generating profit.

---


## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly 
- Jupyter Notebook
- Power BI
- Git & GitHub

---

## Project Structure

Production_Downtime/
│
├── BI/
│   └── Power BI dashboard files
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── production_and_downtime.ipynb
│
├── screenshots/
│   └── dashboard and analysis images
│
├── index.html
└── README.md
