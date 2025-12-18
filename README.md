Pharma-Market-Shift-Analysis
Market shift analysis of injectable anaesthesia drugs using Medicare claims data. This project evaluates competitive movement across four products, identifies the drivers behind Midazolam’s market share decline, and recommends data-driven strategies such as territory prioritization, HCP engagement, and predictive analytics.
________________________________________
Table of Contents
•	Project Overview
•	Problem Statement
•	Data Sources & Preprocessing
•	Analysis & Key Insights
o	Market Dynamics & Competitive Landscape
o	Key Market Drivers
o	Geographic Market Trends
•	Strategies to Strengthen Product 2’s Market Position
•	Project Deliverables
•	Future Enhancements
•	Repository Structure
•	Contact Information
________________________________________
Project Overview
This project provides an in-depth analysis of market shifts within the injectable anesthesia drug market. The primary objective is to understand why Product 2 (Midazolam Hydrochloride) was unable to capture the declining demand of Product 1 (Ketorolac Tromethamine) and instead lost share to Product 3 (Fentanyl Citrate). By examining prescription behavior, competitive trends, and market drivers, the analysis delivers actionable insights to improve Product 2’s commercial performance.
________________________________________
Problem Statement
•	Product 1 (J1885 – Ketorolac Tromethamine): Legacy market leader experiencing a steady decline in utilization
•	Product 2 (J2250 – Midazolam Hydrochloride): Recently introduced alternative intended to absorb Product 1’s decline, but currently underperforming
•	Product 3 (J3010 – Fentanyl Citrate): Primary competitor rapidly expanding market presence
•	Product 4 (J2704 – Propofol): Secondary competitor showing early signs of increased adoption
Objective:
Evaluate competitive market dynamics and propose data-backed strategies to address Product 2’s declining market position.
________________________________________
Data Sources & Preprocessing
The analysis integrates multiple datasets to construct a comprehensive, analysis-ready dataset.
Datasets Utilized
•	Medicare Claims Data: ~1 million records containing procedure, diagnosis, and provider information
•	HCP Demographics Data: Physician specialties and geographic attributes
•	Patient Demographics Data: Patient age segments and demographic indicators
•	Zip-to-Territory Mapping: Mapping provider ZIP codes to sales territories
•	Diagnosis Code Mapping: ICD-10 codes grouped by clinical specialty
•	Procedure Code Mapping: HCPCS codes associated with individual products
Data Preparation Workflow
•	Consolidated all claims files into a single structured dataset (~28,368 filtered records)
•	Filtered claims for target procedure codes (J1885, J2250, J3010, J2704)
•	Mapped diagnosis codes to disease categories to analyze prescribing behavior
•	Standardized geographic identifiers and assigned claims to sales territories
•	Enriched claims data with provider and patient demographic attributes
________________________________________
Analysis & Key Insights
1. Market Dynamics & Competitive Landscape
•	Product 3 (J3010) exhibits strong growth driven by consistent prescriber adoption
•	Product 1 (J1885) continues its lifecycle-driven decline
•	Product 2 (J2250) shows limited differentiation relative to competitors
Key Observations & Recommendations:
•	Utilize Product 1’s established brand familiarity to reinforce Product 2’s positioning
•	Enhance HCP engagement through focused education and incentive-based programs
•	Refine territory-level strategies using utilization and demographic insights
________________________________________
2. Key Market Drivers
HCP & Patient Insights
•	Anesthesiologists and cardiologists account for the majority of prescriptions
•	Patients aged 61–70 contribute the highest claim volume
Recommendations:
•	Prioritize educational outreach to high-impact specialties
•	Tailor messaging and engagement strategies for older patient segments
________________________________________
3. Geographic Market Trends
•	Large metropolitan regions (e.g., New York; Los Angeles–San Diego) show pronounced declines for Product 2
•	Mid-sized territories (e.g., Phoenix, Minneapolis) offer recovery potential
Recommendations:
•	Intensify commercial focus in high-density markets
•	Implement localized recovery strategies in moderate-performing regions
________________________________________
Strategies to Strengthen Product 2’s Market Position
•	Territory Optimization: Increase field presence in underperforming high-impact regions
•	Co-pay & Payer Support: Minimize financial barriers through patient assistance initiatives
•	Digital Engagement: Expand webinars, digital campaigns, and targeted HCP outreach
•	Brand Repositioning: Align Product 2 more closely with Product 1’s trusted legacy
•	AI/ML Enablement: Apply predictive analytics to improve targeting and marketing effectiveness
________________________________________
Project Deliverables
•	Jupyter Notebook (810 Final Python File.ipynb): Data preparation, EDA, visualizations, and analysis
•	PowerPoint Presentation (BIA 810-D Final Presentation Group 5.pptx): Executive summary of insights and strategic recommendations
•	Original Data Files (CSV): Source datasets (subject to privacy and compliance constraints)
________________________________________
Future Enhancements
•	Integrate private insurance claims data for broader market coverage
•	Develop advanced machine learning models to predict prescribing behavior
•	Expand competitive analysis to include pricing and promotional effectiveness
________________________________________
Repository Structure
Repository_Structure/
│
├── Original Data Files CSV/
│   ├── Medicare_Claims_data_part_1.csv
│   ├── Medicare_Claims_data_part_2.csv
│   ├── Medicare_Claims_data_part_3.csv
│   ├── Medicare_Claims_data_part_4.csv
│   ├── Medicare_Claims_data_part_5.csv
│   ├── HCP_demographics_data.csv
│   ├── Patient_demographics_data.csv
│   ├── Diagnosis_Code_Mapping.csv
│   ├── Procedure_Code_Mapping.csv
│   └── Zip_to_Territory_Mapping.csv
│
├── 810_final_.ipynb
├── BIA 810 Final Project_Team 5.pptx
└── README.md

