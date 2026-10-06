# Municipal Crime Analytics: End-to-End Data Pipeline & Resolution Dashboard

This repository contains a full-stack data analytics portfolio project that transforms a highly irregular, simulated municipal crime dataset into a strategic business intelligence dashboard. The project demonstrates robust data engineering, systematic data cleansing, and advanced visualization techniques to evaluate law enforcement incident frequencies, financial damages, and case resolution rates.

## Technical Stack & Data Architecture
**MySQL:** Conducted backend data engineering, utilizing Common Table Expressions (CTEs) for deduplication and COALESCE to professionally handle NULL values, ensuring financial and demographic metrics remained unskewed.

**Data Transformation:** Standardized anomalous categorical text (e.g., grouping weapon types and crime variations), rectified financial data entry errors including negative values and formatting anomalies, and engineered temporal features.

**Power BI:** Developed an interactive dashboard utilizing DAX measures for dynamic KPIs (such as "Most Used Weapon"), structured data modeling, and accessible visual filtering.

## Core Business Insights

**Executive KPIs:** The environment tracks 5.1K total incidents resulting in $126M in total property loss, averaging $24.86K per incident. The overall case resolution rate across all regions is 7.4%.

**Case Status & Resolution:** Currently, 25.17% of cases remain open and 24.64% are under active investigation. Resolution rates vary heavily by crime type; graffiti incidents see a 15% resolution rate, whereas homicides and hacking remain near 5%.

**Temporal & Severity Trends:** The vast majority of incidents occur at night (2,132), followed by the afternoon (1,263). Incident severity is relatively evenly distributed between medium (28.84%) and low (28.72%) categorizations.

**Regional Performance:** The Northeast region maintains the highest resolution rate (9.2%), significantly outperforming the Southeast region (4.9%). The North region experiences the highest total volume of incidents (696).

**Incident Attributes:** Driving Under the Influence (353) and Drug Offences (350) are the highest-frequency crimes. Knives (646) and blunt objects (640) are the most frequently used weapons.

**Demographics:** Adults (2.2K) and the elderly (1.5K) are the primary victims. While suspect gender volume is highly symmetrical, female suspects correlate with a marginally higher resolution rate (8.2%) compared to male suspects (6.7%). 


## Author
**Mohd Junaid**

Bachelor of Computer Applications (BCA) | Data Analyst
