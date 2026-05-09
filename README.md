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


![Hospital Dashboard](assets/dashboard_preview.png)

[Download the Power BI file](https://github.com/MelodyNwaonusuru/Hospital_Project/blob/main/Hospital_Data.pbix)



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

1. Revenue fell by approximately 80% from the 2022 peak to Q3 2023, indicating a significant decline in performance. The persistence of this drop suggests potential changes in patient volume, payer mix, or service delivery that require further investigation.

2. Profit fell by approximately 80% from Q4 2022 to Q3 2023, broadly mirroring the decline in revenue. This may suggest limited cost flexibility, though confirmation would require a breakdown of fixed and variable costs.

3. Expenses peaked alongside revenue at Q4 2022 ($30.67K) and declined sharply through 2023, suggesting that reduced patient activity rather than improved cost efficiency is the primary driver of the expense reduction.
   
4. In 2021–2022, it showed strong growth (+115% revenue), suggesting the model works at scale. The rise from $20.65K (Q1 2021) to $44.36K (Q3 2022) validates the underlying business model and physician mix. The hospital can recover if the 2023 volume decline is reversed — indicating the priority should be demand recovery, not cost-cutting.

<img width="1152" height="716" alt="WhatsApp Image 2026-05-06 at 11 35 01 (1)" src="https://github.com/user-attachments/assets/21e98076-0753-45ce-abbf-e6900242dc82" />

**Recommendations**

1. Launch an emergency demand recovery programme:
Revenue fell 80% from the 2022 peak to Q3 2023. The cost base tracks revenue — meaning the model is fundamentally sound. The crisis is demand, not operations. Prioritize immediate outreach: re-engage lapsed patients, launch GP referral partnerships, and activate digital appointment campaigns targeting the 30–40s demographic.

2. Retain and protect top-earning physicians immediately: Ava Adams alone generates $24.75K — 9% of total revenue. The top 5 doctors account for a disproportionate share of profit. A single departure creates an immediate double-digit revenue hole. Implement contractual retention incentives, performance bonuses, and structured succession plans for the top 10 earners now.
   
3. Scale dermatology and radiology, the two revenue engines: Dermatology ($38.6K revenue, $12.12K profit) and Radiology ($36.55K, $17K combined), consistently lead every performance view. Both are scalable with a low marginal cost per additional case. Add subspecialties (Mohs surgery, cosmetic derm, MRI-guided procedures) and extend operating hours to increase throughput without a proportional cost increment.

4. Add women's health and chronic disease services for 40–60+ patients:47 male vs 39 female patients reveals an underserved women's health gap. The 50s age group generates the lowest average revenue ($1,064), and the 60+ segment is virtually absent, the highest-utilization demographic in healthcare. Adding OB/GYN, breast imaging, endocrinology, and chronic disease management would open two large untapped revenue streams simultaneously.
   
5. Invest in fast-growth doctors before competitors poach them: Elijah Mitchell (90.47% YoY), Olivia Anderson (66.85%), and John Doe (50%) are on steep productivity growth curves, building patient panels and referral networks rapidly. These doctors are most vulnerable to better offers elsewhere. Assign dedicated admin support, upgrade their facilities, and lock in multi-year contracts now while their loyalty is still forming.

6. Build a VIP patient programme for top-profit patients: The top 5 patients (Harper Young, Ethan Lopez, et al.) generate ~22% of profit from just 5.8% of the patient base. These high-value patients have premium insurance, complex multi-service needs, and strong follow-up rates. A dedicated care coordinator, priority scheduling, annual health reviews, and proactive specialist referrals would significantly improve retention and lifetime value.

7. Shift from cost-plus to value-based pricing on high-demand procedures: Every patient margin clusters tightly at 30–32%, suggesting standardized cost-plus pricing. This leaves money on the table for high-demand, low-availability procedures like cardiac imaging, Mohs surgery, and MRI. Dynamic pricing charging premium rates where demand exceeds capacity,  could expand margins on 20–30% of procedures without affecting the broader patient panel.

8. Reduce specialty concentration risk by diversifying into surgery and orthopedics: The top 3 categories (Dermatology, Radiology, Pediatrics) generate 55% of revenue. Any physician departure, equipment failure, or payer contract change in dermatology alone could cause a 14% revenue drop. Strategically building volume in Surgery ($29.9K) and Orthopedics ($33.8K) already in the portfolio would spread risk while entering two higher complexity, higher-reimbursement service lines.

9. Double down on California and replicate what's working there in New York: California ($142K) outperforms New York ($131.6K) in revenue while both maintain ~31% profit margins — confirming the model translates across markets. California's edge likely reflects a better procedure or payer mix. A granular analysis of California's case mix vs New York's would reveal exactly which services to promote harder in New York to close the $10K revenue gap.

10. Introduce procedure bundling to raise average transaction value: At an average revenue per transaction of $1,189, the hospital is leaving upsell revenue uncaptured. Bundling related services, e.g. MRI scan + radiologist consultation + follow-up; skin biopsy + dermatologist review + treatment plan, increases visit value without adding a new patient. Even a 15% improvement in average transaction value would add $41K in annual revenue at current volume levels.

**Tools Used Tool Purpose**

1. Power BI Desktop — Data modelling, DAX measure development, dashboard design and layout
2. Power Query (M) — Data transformation, column structuring, data type enforcement
3. DAX KPI measures — Total Revenue, Total Profit, Total Expense, Total Doctors, Total Patients, and conditional formatting logic.
4. Star Schema Modelling — Structured the data model with one fact table and five dimension tables for clean cross-filtering
5. Custom Date Table — Built manually in Power Query to enable accurate time intelligence and correct Month Name ordering.

