# Call Center Performance Analytics Dashboard

Built an interactive Power BI dashboard to monitor call volume, service efficiency, and customer experience. The dashboard provides operational visibility to support staffing optimization, agent performance evaluation, and service quality improvement.

---

## Dashboard Preview

### Call Center Performance Dashboard
![Call Center Dashboard](./screenshots/CallCenter_Dashboard.png)

---

## Context
This project analyzes call center operational data to evaluate demand patterns, service efficiency, and customer experience. The goal was to identify performance gaps, understand workload distribution, and support data-driven operational decisions.

**Data Source:** Call center interaction dataset containing approximately **5,000 call records** collected over **three months**, including call timestamps, agent information, call topics, resolution status, and customer satisfaction ratings.

---

## Analytical Approach
- Monitored **call volume and demand patterns** across time (hour, day, and month)
- Evaluated **service quality and efficiency** using resolution rate, first-call resolution, and handling time metrics
- Analyzed **agent-level performance** to identify variability in efficiency and effectiveness
- Assessed **call topics** to understand complexity drivers and workload distribution
- Enabled interactive filtering to support **root-cause analysis and operational drill-downs**

---

## Business Questions Addressed
- When are call volumes highest, and how does demand vary by time?
- How many calls are answered versus abandoned, and where do capacity gaps exist?
- How effective are agents at resolving customer issues on the first contact?
- Which call topics require longer handling times?
- How does customer satisfaction align with operational performance?

---

## KPIs Tracked
- **Total Calls:** 5,000  
- **Answered Calls:** 4,000  
- **Abandoned Calls:** 946 (~19%)  
- **Resolution Rate / First Call Resolution:** 72.92%  
- **Average Speed to Answer:** ~55 seconds  
- **Average Talk Duration:** ~3 minutes  
- **Customer Satisfaction (CSAT):** 2.76 / 5  

---

## Key Insights
- Nearly **1 in 5 calls were abandoned**, indicating capacity constraints during peak demand periods.
- Call volumes peak during business hours and vary by weekday, highlighting opportunities for **staffing optimization**.
- Resolution rates suggest moderate effectiveness, with room to reduce repeat calls.
- Agent performance varies across resolution and handling time, supporting targeted coaching opportunities.
- Customer satisfaction trails resolution performance, indicating experience factors beyond issue resolution impact CSAT.

---

## Tools Used
Power BI, DAX, SQL, Excel

---

## Dashboard PDF (Optional)
- [Call Center Dashboard (PDF)](./dashboard/Call_Center_Performance.pdf)
