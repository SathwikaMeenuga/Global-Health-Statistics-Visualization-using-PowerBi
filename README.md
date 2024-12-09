# Global-Health-Statistics-Visualization-using-PowerBi
**Data Source and Introduction**
** **
The dataset, sourced from Kaggle, provides a comprehensive overview of global health statistics. It includes information on disease prevalence, mortality rates, healthcare access, and socioeconomic factors. With data spanning from 2000 to 2024, this dataset enables the analysis of health trends, disease burden, treatment costs, and the effectiveness of healthcare systems globally. It serves as a valuable resource for policymakers, researchers, and healthcare professionals to understand global health patterns and inform public health strategies. Power BI was employed to visualize the data and create interactive dashboards.
****
Link to the Dataset and PowerBi file: https://drive.google.com/drive/folders/1ReSSGMyipMaYVyBmO81SH8WVdTfiS3ku?usp=drive_link
****
**Summary of the Dataset:**
****
•	Country: The name of the country where the health data was recorded.

•	Year: The year in which the data was collected.

•	Disease Name: The name of the disease or health condition tracked.

•	Disease Category: The category of the disease (e.g., Infectious, Non-Communicable).

•	Prevalence Rate (%): The percentage of the population affected by the disease.

•	Incidence Rate (%): The percentage of new or newly diagnosed cases.

•	Mortality Rate (%): The percentage of the affected population that dies from the disease.

•	Age Group: The age range most affected by the disease.

•	Gender: The gender(s) affected by the disease (Male, Female, Both).

•	Population Affected: The total number of individuals affected by the disease.

•	Healthcare Access (%): The percentage of the population with access to healthcare.

•	Doctors per 1000: The number of doctors per 1000 people.

•	Hospital Beds per 1000: The number of hospital beds available per 1000 people.

•	Treatment Type: The primary treatment method for the disease (e.g., Medication, Surgery).

•	Average Treatment Cost (USD): The average cost of treating the disease in USD.

•	Availability of Vaccines/Treatment: Whether vaccines or treatments are available.

•	Recovery Rate (%): The percentage of people who recover from the disease.

•	DALYs: Disability-Adjusted Life Years, a measure of disease burden.

•	Improvement in 5 Years (%): The improvement in disease outcomes over the last five years.

•	Per Capita Income (USD): The average income per person in the country.

•	Education Index: The average level of education in the country.

•	Urbanization Rate (%): The percentage of the population living in urban areas.

The “Per Capita Income” and “Average Treatment Cost” columns were converted to the appropriate numeric data type to facilitate calculations and visualizations.

**Data Visualization**
****
**Dashboard 1:** In-Built Data Explorer using features like Q&A and Key Influencers in PowerBi.

The Power BI Q&A feature offers a powerful tool for interactive data exploration. By asking natural language questions, users can quickly gain insights from their data.
In this specific example, the Disease Name emerged as a key influencer, suggesting that certain diseases are more prevalent in the USA compared to other countries. This insight can be valuable for targeted public health interventions and resource allocation.
Furthermore, the Q&A feature enables users to ask specific questions like "How many countries are there?" or "What is the maximum per capita income (USD)?", providing quick answers and facilitating deeper data exploration.

Key Findings:

•	Age group “18-35” and diseases like “HIV/AIDS” and “COVID-19” emerged as significant factors influencing certain trends.

•	Countries with higher per capita income and better healthcare access generally had lower disease burdens and higher recovery rates.

•	The analysis revealed significant variations in disease prevalence and mortality rates across different regions of the world.

•	By categorizing diseases into groups like infectious, non-communicable, and others, we were able to identify trends and patterns within specific categories.

![image](https://github.com/user-attachments/assets/1ac4a846-5843-48d1-832a-7e2f5dfe2e68)


Potential Use Cases and Further Analysis:

•	By analyzing the distribution of diseases across different countries, global health trends and potential outbreaks can be identified.

•	The data can be used to compare healthcare systems in different countries, focusing on factors like access to healthcare, mortality rates, and disease prevalence.

•	Leveraging machine learning techniques, future trends in disease outbreaks and healthcare needs can be predicted.

•	The insights gained from this dashboard can inform public health policies and resource allocation.

**Dashboard 2:** Disease Category Overview

This dashboard provides a comprehensive overview of global health data. It allows for in-depth analysis of disease prevalence, mortality, recovery rates, healthcare infrastructure, and treatment costs.

Key features of the dashboard include:

•	Disease Category Overview: This section enables comparisons of health conditions across different categories (e.g., infectious, non-communicable).

•	Disease-Specific Metrics: The dashboard provides detailed stacked column charts with information on disease prevalence, mortality, and recovery rates for various categories of diseases.

•	Treatment Costs: The dashboard also has a line chart to analyze treatment costs for different disease categories.

•	Interactive Features like Slicers for country, gender and year allow for customized exploration of the data.

By leveraging this dashboard, users can gain valuable insights into global health trends, identify areas of concern, and inform public health policies and interventions.

Key Findings:

By focusing on India in 2024 and filtering the data by female gender, we gain valuable insights into the country’s health landscape.

•	Disease Categories and Health Outcomes: India shows a higher prevalence and mortality rate for infectious diseases compared to other categories. Factors such as poor sanitation, inadequate healthcare infrastructure, and high population density contribute to this trend.

• Chronic Diseases: Though less prevalent, chronic diseases like cardiovascular and neurological disorders are significant contributors to mortality and morbidity.

•	Recovery Rates: Recovery rates vary across diseases, with some infectious diseases showing higher recovery rates than chronic conditions, reflecting the complexity of healthcare outcomes.

•	Healthcare Access and Treatment Costs: The average treatment cost for different disease categories in India provides insights into the economic burden of healthcare. Analyzing these costs over time helps identify areas where cost-effective interventions can be implemented to reduce the financial strain on the population.

![image](https://github.com/user-attachments/assets/20c8fad5-e555-4ecc-ac47-00831c5f69df)

**Dashboard 3:** Disease and Treatment Access

This dashboard provides a detailed analysis of global health trends, focusing on various diseases. Here's a summary of the key insights it offers:

•	Disease Prevalence, Mortality, and Recovery Rates: Bar charts visualize these metrics for different diseases across multiple countries, allowing you to identify the most prevalent diseases, understand their mortality rates, and assess recovery trends.

•	Healthcare Infrastructure Impact: Card visuals display key healthcare metrics like the average number of doctors and hospital beds per 1000 people, offering insights into how healthcare infrastructure may influence disease outcomes. This also includes a measure of overall disease burden, DALYs (Disability-Adjusted Life Years). This metric combines years of life lost due to premature death and years lived with disability, providing a comprehensive assessment of disease impact.

•	Treatment Cost Trends: Line charts track the average treatment costs for specific diseases from 2000 to 2024, helping to identify trends in cost fluctuations and pinpoint potential areas for cost reduction.

•	Interactive Exploration: Slicers for country and year enable dynamic filtering, allowing users to explore trends and insights specific to a selected region or time frame.

By interacting with this dashboard, users can gain valuable insights into global disease patterns, the influence of healthcare infrastructure on disease outcomes, and treatment cost trends. These insights can aid policymakers, healthcare professionals, and researchers in making informed decisions to improve global health outcomes.

Key Findings:

The dashboard analyzing Argentina's health trends reveals key insights into the country's disease burden, healthcare infrastructure, treatment costs, and disease-adjusted life years (DALYs). High disease prevalence and mortality rates highlight the need for targeted health interventions, especially for diseases with lower recovery rates. Argentina's healthcare infrastructure shows room for improvement, with fewer doctors and hospital beds per 1000 people, which could affect healthcare access. Treatment costs fluctuate over time, suggesting a potential area for cost-saving strategies. While Argentina's DALY values indicate a moderate disease burden, they emphasize the need to prioritize healthcare resources effectively. Overall, the findings suggest that strengthening healthcare infrastructure, addressing disease-specific challenges, and optimizing treatment costs are essential for improving health outcomes in the country.

![image](https://github.com/user-attachments/assets/40e3ee71-4a15-4f52-aed2-88018d7e570a)

**Limitations and Considerations**
****
•	Data Aggregation: Some metrics, like average treatment cost, may be aggregated at a country level, potentially masking variations within the country.

•	Data Volume: Power BI can only load a maximum of 999 rows at a time, which poses a constraint when working with large datasets. This limitation could lead to performance issues or incomplete analysis when the dataset exceeds the maximum load capacity. In contrast, programming languages like Python can handle larger datasets more efficiently, providing greater flexibility for in-depth analysis and visualization.

By addressing these limitations and utilizing the insights gained from the dashboard, policymakers, healthcare professionals, and researchers can make informed decisions to improve global health outcomes.

**Conclusion**
****
This project presents a comprehensive analysis of global health trends, with a particular focus on disease prevalence, mortality rates, recovery outcomes, healthcare infrastructure, treatment costs, and disability-adjusted life years (DALYs). By leveraging Power BI dashboards, the project provides valuable insights into health patterns across countries, highlighting key areas such as disease burden, healthcare access, and cost trends. Through the visualizations, users can gain an understanding of how healthcare systems and disease-specific factors affect public health outcomes in various regions, including a detailed focus on countries like India and Argentina in 2024.
The analysis of disease categories, healthcare access, and treatment costs enables policymakers, healthcare professionals, and researchers to identify key areas of concern and inform decisions to improve global health outcomes. However, the analysis is subject to limitations, such as the aggregation of data at the country level and Power BI’s constraints with large datasets, which may affect the granularity of insights.



