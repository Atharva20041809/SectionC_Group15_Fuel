hey there 

---

# **Coal Inventory Optimization & Risk Monitoring Dashboard**

---

## **Project Overview**

**This project focuses on analyzing coal stock adequacy, operational coverage, and supply dependency to support data-driven decision-making in inventory planning.**

The objective is to provide a consolidated analytical view of:

- **Stock vs Required Levels**
- **Coverage Duration**
- **Supply Dependency (Domestic vs Import)**
- **Operational Risk Categories**

> **A dashboard was developed to enable proactive monitoring and improve planning efficiency.**

---

## **Problem Statement**

**The organization lacks a clear and consolidated view of stock adequacy and operational risk over time.**

Although data on total stock, required stock levels, coverage days, and supply dependency exists, there is **no structured mechanism** to:

- **Evaluate** whether inventory levels meet required benchmarks
- **Track** coverage performance across years
- **Understand** operational risk exposure
- **Identify** dependency patterns

> **This results in reactive decision-making instead of proactive planning.**

---

## **Objective**

**The goal of this project is to build a data-driven solution that:**

- Compares **total stock** against **normative requirements**
- Tracks **stock coverage trends** over time
- Analyzes **domestic and import dependency**
- Classifies **operational risk levels**
- Provides an **interactive dashboard** for monitoring

---

## **Data Engineering Process**

**The data preparation workflow included:**

- Standardizing date and categorical formats
- Converting numeric values stored as text
- Removing inconsistencies and blank records
- Creating derived analytical features

### **Derived Metrics**

| Metric | Description |
|---|---|
| **Total Stock** | Overall inventory available |
| **Stock Surplus / Deficit** | Gap between actual and required stock |
| **Days of Stock Available** | Coverage duration in days |
| **Domestic Dependency** | Share of domestic supply |
| **Import Dependency** | Share of imported supply |
| **Risk Category** | Operational risk classification |

> **These transformations enabled meaningful KPI analysis and decision insights.**

---

## **Key Performance Indicators (KPIs)**

**The project evaluates stock health using:**

- **Total Stock vs Required Stock**
- **Days of Coverage**
- **Domestic Share vs Import Share**
- **Minimum Coverage Trends**
- **Risk Category Distribution**

---

## **Dashboard Features**

**The dashboard provides both executive and operational insights:**

### **Executive View**

- **Total Stock vs Required Stock** comparison
- **Average Days of Coverage**
- **Supply Dependency Indicators**

### **Operational View**

- Coverage trends over time
- Minimum stock risk analysis
- Risk category distribution
- Year-wise performance comparison

---

## **Key Insights**

- **Stock levels frequently fall below required benchmarks.**
- **Coverage duration varies across periods, indicating instability.**
- **Domestic supply dominates but imports support during shortages.**
- **Moderate and low-buffer risk conditions occur frequently.**

---

## **Recommendations**

- **Align** stock planning with normative requirements.
- **Monitor** coverage days continuously.
- **Optimize** domestic and import supply balance.
- **Implement** risk-based alerts for proactive action.

---

## **Business Impact**

**The solution enables:**

- **Improved** inventory visibility
- **Faster** decision-making
- **Reduced** operational risk
- **Better** planning efficiency

---

## **Limitations**

- Analysis is limited to available stock and requirement data.
- External factors such as logistics and demand variability were **not included**.
- Predictive forecasting was **not implemented**.

---

## **Future Enhancements**

- **Predictive modeling** for stock forecasting
- **Real-time monitoring** and alerts
- **Integration** with supply chain data
- **Plant-level or regional** dashboards

---

## **Tools & Technologies**

| Tool | Purpose |
|---|---|
| **Google Sheets / Excel** | Data storage & manipulation |
| **Data Cleaning & Transformation** | Preprocessing pipeline |
| **Pivot Analysis** | Aggregation & summarization |
| **Dashboard Visualization** | Interactive reporting |

---
