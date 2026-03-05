#Healthcare Patient Admissions & Outcomes Analysis
#Project Overview
This repository contains a comprehensive data analysis of healthcare delivery, focusing on patient demographics, disease prevalence, and hospital operational efficiency. The project transforms raw medical records into actionable clinical insights using Python.

🔍 #Analytical Deep-Dive (11 Key Questions)
Total Patient Volume: Analyzed the dataset scale to establish a baseline for all clinical metrics.

Disease Prevalence: Identified the Top 3 Diseases (e.g., Malaria, Typhoid) to assist in resource and medication prioritization.

Gender Distribution: Examined the gender split to identify specific healthcare needs across demographics.

Treatment Status Overview: Visualized the ratio of recovered, deceased, and active cases using a custom Donut Chart.

Mortality Rate: Calculated the facility's death rate with precision (formatting results to 2 decimal places).

Recovery Rate: Quantified the success of clinical interventions.

Active Caseload: Measured the number of patients currently "Under Treatment" to assess hospital capacity.

Age Group Segmentation: Binned ages into categories to identify vulnerable populations (e.g., pediatrics and geriatrics).

Monthly Admission Trends: Engineered features from timestamps to visualize seasonal spikes in patient inflow.

Peak Admission Heatmap: Correlated "Day of Week" vs "Month" to pinpoint exact "high-traffic" periods for staffing.

Cause of Death Analysis: Isolated mortality factors by cleaning missing values with .dropna() for accurate epidemiological reporting.

🛠️ #Technical Stack & Skills
Data Wrangling: Pandas (handling NaN values, reindex, and groupby).

Time-Series: Advanced extraction using .dt.strftime().

Visualization: * Seaborn: Heatmaps with annot=True for density analysis.

Matplotlib: Line and Bar charts with manual data annotations for high readability.
