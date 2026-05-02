# CRM Optimization, Funnel Analysis and Hubspot Workflows

### Executive Summary

This project simulates a full CRM transformation, including data cleaning, lifecycle analysis, and workflow automation design within a HubSpot environment. Using a synthetic SaaS dataset, I identified key funnel inefficiencies and implemented a dynamic lead scoring and lifecycle system to improve lead qualification and sales prioritization.
</br>
</br>
### Business Problem

The CRM system contains inconsistent data, unclear lifecycle definitions, and no standardized lead qualification process. As a result, high-intent leads are not prioritized effectively, low-quality leads enter the sales pipeline, and conversion performance suffers.

To prepare for a transition to HubSpot, the system must be cleaned, structured, and supported by scalable logic for lead scoring, lifecycle management, and workflow automation.
</br>
</br>
### Methodology

1. Generate synthetic datasets for this project using ChatGPT.
2. Performed data hygiene, including standardization, deduplication, and relational validation
3. Analyzed lifecycle distribution, conversion rates, and time-to-stage to identify funnel bottlenecks
4. Conducted segmentation by lead source and job title category to evaluate performance differences
5. Designed a rule-based lead scoring model using behavioral, persona, and acquisition inputs
6. Implemented a modular workflow system in HubSpot to operationalize scoring, lifecycle updates, and lead routing
</br>

### Skills

SQL: Data cleaning, validation and analysis using CTEs, table joins, and case expressions.

Hubspot: Created properties, lists, and workflows

AI: Used to create synthetic datasets, write python code for visualizations, and generate lifecycle workflow image.
</br>
</br>
### Results

##### Key Findings
- ~37% of contacts remain in the Lead stage, indicating friction in early-stage activation or unclear qualification criteria
- Opportunity to Customer is the primary bottleneck, with the lowest conversion rate (~29%) and longest time-to-stage (~26 days)
- Conversion varies meaningfully by lead source and job title, indicating differences in lead quality and buyer alignment

##### System Improvements
- Implemented a dynamic lead scoring model using recent behavioral engagement, persona fit, and lead source
- Established a clear MQL definition (Score ≥50 + engagement) to improve qualification accuracy
 -Introduced time-decayed behavioral scoring (30-day window) to reflect real-time intent
- Designed automated workflows in HubSpot to operationalize lead scoring and route leads accoringly

<img width="1536" height="1024" alt="lifecycle logic workflow" src="https://github.com/user-attachments/assets/cd436484-b688-4c67-a7e1-f0b20a35349d" />


##### Business Impact
- Improves prioritization of high-intent leads for faster sales engagement
- Reduces pipeline noise from low-quality or inactive leads
- Aligns marketing and sales through a consistent qualification framework
- Creates a scalable system for ongoing CRM management and optimization
