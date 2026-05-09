**Lifeline International Hospital - Project Background**

**Overview**

Lifeline Hospital is a multi-specialty healthcare institution established in 2018 and headquartered in the United States. The hospital serves a diverse patient population across multiple states, offering a broad range of medical procedures, including diagnostics, surgical interventions, and post-operative rehabilitation. Its multidisciplinary team of licensed physicians and specialists is committed to delivering accessible, high-quality care to every patient. As the hospital continues to expand, there is a growing need for a structured system to efficiently manage patient records, procedures, and overall hospital operations. This project aims to develop a reliable solution that streamlines these processes and supports Lifeline Hospital's mission of excellent patient care.

**Problem Statement**

Despite managing a growing volume of patient records, procedural data, and operational information across multiple states, Lifeline Hospital has largely left this data underutilised. Without a structured and centralised management system, the hospital lacks the visibility needed to efficiently coordinate patient care, track procedures, and make informed administrative decisions, hindering its ability to deliver consistent, high-quality healthcare.

**Project Objective**

This project delivers a structured and comprehensive system for managing Lifeline Hospital's patient records, procedural data, and operational information across all service areas. By transforming fragmented and underutilised data into an organised and accessible platform, this project equips Lifeline Hospital's administration with the tools needed to coordinate patient care more effectively, streamline hospital operations, and support informed decision-making across all states.

**Key Areas of Analysis**

1. **Doctor Performance**: An evaluation of individual and departmental doctor performance across Lifeline Hospital, examining patient outcomes and procedure success rates. 

2. **Patient Demographics & Impact**: An analysis of the hospital's patient base, exploring demographic factors. This helps understand how these characteristics influence treatment patterns, procedure demands, and overall healthcare outcomes.

3. **Hospital Performance Trends**: An evaluation of the hospital's overall performance over time, tracking patterns in patient admissions, service utilisation, and operational output across all states.

4. **Procedural & Financial Analysis**: An investigation into the range of medical procedures performed at Lifeline Hospital, examining procedure frequency, associated costs, and financial outcomes.

This aims to identify opportunities for improved resource allocation and operational efficiency across all service areas.

**Data Structure & Initial Checks**

Lifeline's database consists of six tables: transactions, doctors, patients, Location, procedure, and date, with 230 transactions.

<img width="1163" height="664" alt="WhatsApp Image 2026-05-06 at 12 11 33" src="https://github.com/user-attachments/assets/340b88eb-b210-4fbc-b0b1-8aaa331b966e" />


**Executive Summary — Hospital Executive Overview**

1. Lifeline Hospital generated $273,560 in total revenue, $85,050 in total profit, and a 31.09% profit margin across 230 transactions and 86 total patients served across all operational states.

2. California ($142K) outperforms New York ($131.6K) in revenue, while both states maintain similar net profit margins (31%). This suggests broadly consistent profitability across markets, though differences in revenue may reflect higher procedure volumes, payer mix, or case composition (e.g., dermatology or radiology) in California.

3. A predominance of patients in their 30s suggests that the hospital mainly provides preventive, outpatient, and diagnostic services for working-age adults

4. An average revenue of approximately $1,189 per transaction suggests a moderate transaction value, likely associated with outpatient and diagnostic services. Revenue could be increased through service bundling and the gradual expansion of specialized procedures.

5. 47 male vs 39 female patients: a 17% gap that may signal underserved women's health needs. Male-skewed patient volumes in specialty care can reflect underdiagnosis or access barriers for women. Adding women's health specialties (OB/GYN, breast imaging, endocrinology) could close the gap and open a large untapped revenue stream, particularly in the 30s age group.

<img width="1151" height="717" alt="WhatsApp Image 2026-05-06 at 11 35 00" src="https://github.com/user-attachments/assets/553f9006-bd6a-4ca9-ba1c-ea5f33c8666f" />


**Insight Deep Dive — Doctor Performance**

Key Findings

1. Ava Adams generated $24.75K in revenue, nearly twice that of the second-highest earning physician, Liam Turner ($20.33K). This indicates a notable concentration of revenue among a small number of physicians, which may expose the hospital to operational and financial risk if key personnel reduce their workload or leave the organization.

2. Doctor gender split is nearly equal,  42 male vs 39 female, indicating good workforce diversity. A near-parity workforce is associated with better patient satisfaction scores, broader referral networks, and reduced gender bias in diagnosis. 
   
3. Doctors in their 50s contribute only $0.74K in profit — vs $62.54K for 40s — a striking drop-off
This suggests very few doctors in the 50s age bracket, or that older physicians are working reduced schedules. This creates a knowledge-transfer and succession risk, particularly in high-specialized roles like neurology and cardiology, where decades of patient relationships hold financial value.

4. Dermatology generated approximately $68.35K more in revenue than cardiology and neurology combined, making it the hospital’s leading specialty area. The treemap further highlights the strong revenue contribution of cardiology and neurology, which may have greater reimbursement potential due to the complexity of their procedures.
   
5. Strong year-over-year revenue growth among several mid-tier physicians, such as Elijah Mitchell (90.47%), may reflect increasing clinical activity and patient demand. Supporting these physicians with adequate resources could help sustain long-term revenue growth. 


<img width="1151" height="711" alt="WhatsApp Image 2026-05-06 at 11 35 01" src="https://github.com/user-attachments/assets/28eb0954-4b47-470f-b03d-bb8fc82330dc" />


**Insight Deep Dive — Patient Demographics & Impact**

Key Findings

1. 20s patients generate the highest average revenue ($1,264) despite being the smallest group (8 patients). Young patients with fewer visits generating the highest average revenue likely indicate high-cost acute or diagnostic procedures (e.g., imaging, injury treatment). This is unsustainable as a core revenue driver; these are episodic, not recurring visits. The 30s cohort at $1,245 average with 39 patients is a far more reliable revenue anchor.
 
2. Harper Young generated the highest patient profit at $5.07K with a 30.43% margin, which is broadly aligned with the hospital’s average margin. The top five patients (Harper Young through Mia Adams) contributed approximately 22% of total profit despite representing only 5.8% of the patient population. This concentration suggests that a small group of patients contributes disproportionately to profitability.

3. John Doe and Olivia Anderson recorded year-over-year revenue growth of 50% and 66.85%, respectively, indicating increased utilization of hospital services. This trend may reflect greater healthcare needs, more frequent visits, or expanded use of specialized services.

4. Patients in their 50s generated the lowest average revenue per patient ($1,064), despite older age groups often being associated with higher healthcare utilization. This may reflect the relatively small cohort size (8 patients) or differences in the types of services received.

5. The clustering of patient profit margins around 30–32% suggests a largely uniform margin structure, potentially driven by standardized pricing or reimbursement arrangements. This may warrant further review to determine whether higher-complexity cases are adequately differentiated in revenue allocation.

<img width="1149" height="711" alt="WhatsApp Image 2026-05-06 at 11 35 00 (1)" src="https://github.com/user-attachments/assets/e8d6c6d0-a0e5-4aff-9da9-617a89908d73" />


**Insight Deep Dive — Procedure & Financial Analysis**

Key Findings

1. Dermatology leads both in revenue ($38.6K) and profit ($12.12K), making it the strongest performing specialty in absolute financial terms. This suggests strong overall demand and favourable revenue contribution relative to other departments.

2. General Medicine records the lowest profit ($6.28K), despite generating relatively high revenue from General Checkups ($21,050) against expenses of $14,770, resulting in a thin margin. This may indicate that General Medicine functions primarily as an entry point for patient care, with potential downstream referrals to higher-margin specialties such as cardiology, radiology, and dermatology.
  
3. Radiology generates $36.55K in revenue across two procedures (MRI and X-Ray), indicating strong output from a limited service set. MRI ($17K revenue, $11.8K cost) and X-Ray ($19.5K revenue, $13.7K cost) both require high upfront capital investment but typically have lower incremental costs per additional scan, depending on utilization levels.

4. The overall profit margin of 31% suggests relatively stable profitability across services. Differences in total profit are therefore more likely driven by revenue volume rather than margin variation, though this should be validated with more granular category-level analysis.
   
5. The top three categories (Dermatology, Radiology, and Pediatrics) account for approximately 55% of total revenue, indicating a moderate level of revenue concentration. This suggests that performance in a small number of specialties has a meaningful impact on overall hospital revenue. As a result, changes in key service lines—such as shifts in physician availability, equipment utilization, or payer agreements—could materially affect total revenue performance.

<img width="1147" height="715" alt="WhatsApp Image 2026-05-06 at 11 35 02" src="https://github.com/user-attachments/assets/6de33328-329f-4847-b5ce-b2acf310ce46" />


**Insight Deep Dive — Hospital Performance Trend**

**Key Findings**

1. Revenue grew steadily from Q1 2021 ($20.65K) to a peak of $44.36K in Q4 2022, reflecting strong operational growth over nearly two years before a sharp and sustained decline through 2023.
2. Total profit followed the same trajectory, peaking at $13.69K in Q4 2022 before falling to its lowest point of $2.72K in Q3 2023, representing a significant erosion of profitability that demands strategic attention.
3. Expenses peaked alongside revenue at Q4 2022 ($30.67K) and declined sharply through 2023, suggesting that reduced patient activity rather than improved cost efficiency is the primary driver of the expense reduction.
4. Profit margin spiked unusually to 38.97% in Q1 2023 before collapsing back to 30.56% by Q3 2023, indicating financial instability likely driven by irregular patient volumes or one-off procedural revenues during that period.
5. The consistent decline across revenue, profit, and expenses from Q1 2023 through Q3 2023 points to a broader operational slowdown that requires urgent investigation into patient retention, referral volumes, and service utilization across all states.

<img width="1152" height="716" alt="WhatsApp Image 2026-05-06 at 11 35 01 (1)" src="https://github.com/user-attachments/assets/21e98076-0753-45ce-abbf-e6900242dc82" />

**Recommendations**

1. The hospital should urgently investigate the sharp revenue and profit decline from Q1 2023 through Q3 2023, developing a comprehensive recovery strategy focused on patient retention, referral partnerships, and service expansion to reverse the downward performance trend.
2. Dermatology, Cardiology, and Neurology should receive increased investment in staffing, equipment, and resources as the hospital's three highest revenue-generating specialties, to further maximize their financial contribution and strengthen overall hospital performance.
3. A structured performance development programme should be introduced for underperforming doctors, particularly those recording 0% or low year-on-year revenue growth, with a mentorship initiative pairing them with top performers such as Ava Adams and Liam Turner.
4. The hospital should design targeted healthcare packages and preventive care programmes for patients in their 30s, who represent the largest and most profitable demographic, while developing outreach programmes for patients in their 50s to increase their service utilization.
5. General Medicine and Dentistry, which record the lowest profit margins across all procedure categories, should undergo a thorough cost and pricing review to identify inefficiencies and improve their financial contribution to overall hospital performance.
6. A quarterly performance monitoring framework should be established to track revenue, profit, expenses, and patient volumes in real time, enabling hospital leadership to detect early warning signs of decline and respond proactively before performance deteriorates.
7. The hospital should introduce loyalty and referral programmes targeting high-value patients such as Harper Young and Ethan Lopez to incentivize satisfied patients to recommend Lifeline Hospital, driving new patient acquisition across all operational states.
8. Gender-specific health programmes and campaigns should be introduced to attract more male patients, who currently represent the smaller patient group, to close the volume gap and unlock additional revenue opportunities for the hospital.
9. The hospital should expand operational capacity in California and New York, which lead in revenue generation, while simultaneously investing in marketing and outreach efforts in underperforming states to drive patient volume and overall revenue growth.
10. Lifeline Hospital should diversify its procedure offerings by introducing new categories in high-demand medical fields, reducing dependence on existing procedures, and attracting a broader patient demographic to achieve more stable and sustainable long-term financial performance.

**Tools Used Tool Purpose**

1. Power BI Desktop — Data modelling, DAX measure development, dashboard design and layout
2. Power Query (M) — Data transformation, column structuring, data type enforcement
3. DAX KPI measures — Total Revenue, Total Profit, Total Expense, Total Doctors, Total Patients, conditional formatting logic.
4. Star Schema Modelling — Structured the data model with one fact table and five dimension tables for clean cross-filtering
5. Custom Date Table — Built manually in Power Query to enable accurate time intelligence and correct Month Name ordering.

