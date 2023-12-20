# Data-Visualization
## From Data to Insight: Navigating Tuberculosis and Global Health Trends

### INTRODUCTION:

Tuberculosis (TB) is a persistent global health challenge that has significantly impacted populations worldwide for centuries. Caused by the bacterium Mycobacterium tuberculosis, the disease primarily affects the lungs but can also affect other parts of the body. TB spreads through the air when an infected person coughs or sneezes, making it highly contagious. Despite advancements in medical science, TB remains a leading cause of death globally.
Global Impact of Tuberculosis
According to the World Health Organization (WHO), TB is among the top ten causes of death worldwide, ranking above diseases such as HIV/AIDS. The global burden of TB is substantial, with millions of new cases reported each year. The disease particularly affects vulnerable populations, including those with compromised immune systems.
The United Nations (UN) recognizes the severity of the TB epidemic and has taken proactive measures to address it. The UN's Sustainable Development Goals (SDGs) include a specific target to end the TB epidemic by 2030, emphasizing the importance of global collaboration to eradicate this disease. The World Health Assembly has endorsed the WHO's End TB Strategy, highlighting the need for intensified research and innovation to achieve this goal.
Personal Motivation for Research
The motivation behind choosing TB as the focus of this research stems from personal experiences. Witnessing close friends being diagnosed with TB sparked a deep interest in understanding the complexities of the disease beyond the clinical diagnosis. This research aims to delve into the various factors influencing TB, going beyond medical perspectives to explore the broader societal, nutritional, and healthcare dimensions.
Ambitiousness of the project:
This research project embarks on a comprehensive exploration of Tuberculosis (TB) and its intricate connections with various global health indicators. Our ambition is to delve into diverse dimensions of the TB epidemic, encompassing a multitude of factors that extend beyond traditional medical perspectives. The extensive scope of this project reflects our commitment to unraveling the complexity of TB and contributing valuable insights to the broader discourse on global health.
Data Sources
To undertake this ambitious endeavor, we have meticulously gathered data from reputable sources, including the World Health Organization (WHO), World Bank, and Our World in Data because we are working on data across the world. Leveraging these rich datasets allows us to conduct a thorough analysis and draw meaningful conclusions that encompass global, regional, and local perspectives.
The ambitiousness of this project lies in its commitment to address a diverse range of topics, contributing not only to our understanding of TB but also offering valuable insights for policymakers, healthcare professionals, and researchers worldwide.
By combining data from prominent global organizations, our research aims to provide a holistic perspective on TB, transcending geographical boundaries and societal contexts. This ambitious approach reflects our dedication to unraveling the complexities of TB and its interplay with global health indicators, ultimately contributing to the ongoing efforts to combat this pervasive infectious disease.
Research questions:
1. How does protein intake impact the incidence and mortality of tuberculosis?
2. What is the combined impact of protein and fat intake on the prevalence and mortality of tuberculosis?
3. How has vaccine coverage across the world affected the mortality rates associated with tuberculosis?
4. To what extent does the healthcare infrastructure in different regions influence TB mortality rates?
5. How does healthcare infrastructure impact the success of vaccination programs in combatting tuberculosis in 2008?
6. In what ways has food supply across the world over time influenced mortality rates associated with TB?
7. What is the relation between population size and TB mortality in 2010?
8. How have the death rates from TB changed over a specific period in a set of countries?

### METHODOLOGY:
The selection of data sources was based on the credibility and authenticity of the organizations providing the data. Our World in Data, WHO, and the World Bank are renowned for their commitment to data transparency, accuracy, and global health surveillance.
This research project relies on a meticulous collection of data from reputable and authentic sources, each chosen for its reliability and relevance to the research questions. The primary datasets were sourced from the following organizations:
1.Our World in Data – Global Food:
Our World in Data - Food Supply provided crucial data on caloric supply, protein intake, and fat intake across different countries. The platform is renowned for its commitment to data accuracy and transparency.
2.World Health Organization (WHO) - tuberculosis-death-rates-by-age:
WHO - Global Tuberculosis Report 2022 served as a fundamental source for TB-related data, particularly mortality rates. The WHO is a globally recognized authority in health information and disease surveillance.
3.Our World in Data - World Healthcare Budget:
Our World in Data - Financing Healthcare contributed data on healthcare infrastructure globally, providing insights into the financial aspects of healthcare.
4.World Health Organization (WHO) - BCG Vaccination:
WHO - Immunization Data supplied essential data on vaccination coverage, specifically focusing on BCG (Bacillus Calmette-Guérin) vaccination. The WHO is a leading authority on global vaccination programs.
5.World Bank - World Population:
World Bank - World Population furnished population data for countries worldwide, contributing to the analysis of population dynamics in relation to tuberculosis.
Tools and Software:
The analysis and visualization of the datasets were conducted using Tableau, a widely recognized and powerful data visualization tool. Tableau's capabilities facilitated the creation of dynamic and interactive representations, enhancing the clarity of complex relationships within the data.
### ANALYSIS:
Visualization 1:Protein Intake on TB Child Mortality
To assess the relationship between protein intake and tuberculosis (TB) mortality in children under 5 years, we conducted a detailed analysis spanning from 1990 to the present. The focus was on understanding how changes in protein intake correlate with the incidence of TB-related mortality in this vulnerable age group.
We created a calculated field “Protein to Fat Ratio” with the below formula:
• [Food supply (Protein g per capita per day)] / [Food supply (Fat g per capita per day)]
The analysis reveals a consistent and notable decline in TB-related mortality among children under 5 years over the examined period. This positive trend aligns
with global efforts to improve healthcare infrastructure and enhance TB prevention and treatment programs.
Visualization 2: Protein to Fat Intake on TB Adult(15-49) Mortality
To comprehensively understand the impact of nutrition on tuberculosis (TB), we extended our analysis to investigate the combined influence of protein and fat intake on the prevalence and outcomes of TB. Our focus was on assessing whether changes in fat intake, when considered alongside protein intake, contribute to a significant decline in TB cases.To gauge the combined impact, we created a calculated field representing the Protein to Fat Ratio.
Despite a decline in TB cases, the calculated Protein to Fat Ratio has remained relatively consistent over the observed period. This indicates that, while the overall number of cases has reduced, the proportional contribution of protein and fat to nutritional habits has not significantly shifted.
Visualization 3: Vaccination vs. Mortality in 5-14 years across the world
The visualization explores the intricate relationship between vaccination doses and the average death rate of Tuberculosis (TB) in children aged 5-14 years. Utilizing a geographical map, we visually depict the countries with the highest vaccination doses and their corresponding TB death rates among children.
The geographical map highlights regions where countries have implemented high doses of TB vaccination. These areas serve as focal points for understanding the impact of vaccination programs.
The visualization serves as a tool for assessing the effectiveness of TB vaccination programs. Identifying regions with high vaccination doses but persistent TB mortality prompts a reassessment of program strategies.
Visualization 4: Effect of Healthcare budget on Average TB Mortality in Old Population in 2008
In this analysis, we explored the relationship between the percentage of total budget on healthcare of a nation and the mortality of the older population specifically in the year 2008. The visualization presented a conventional
representation that warrants a deeper and more detailed study to extract meaningful insights.
We observe that countries spending less on healthcare have low mortality rates and countries spending the least do not have highest mortality rates either.So there are few other factors to be explored.
Visualization 5: Population vs. Death Rates: Global Comparison (Year: 2010)
In this analysis, we investigated the relationship between the population of countries in the year 2010 and their corresponding death rates. The primary observation was the notable disparity between countries with the highest populations, such as India and China, and their mortality rates, challenging common assumptions.
Countries with the highest populations, specifically India and China, did not exhibit the highest mortality rates in 2010. This contrasts with expectations based solely on population size.
Visualization 6: TB Mortality Rates in Different Age Groups from 1990
In this dynamic visualization, we employed animated dual-axis charts (line and bar) to compare Tuberculosis (TB) mortality rates in two distinct age groups: children below 5 years and individuals over 70 years. The animated timeline spans from 1990 to the present, offering a nuanced exploration of age-specific TB mortality trends.
The animated visualization highlighted clear distinctions in TB mortality rates between the two age groups. Notably, individuals over 70 years consistently exhibited higher mortality rates compared to infants.
Visualization 7: Country-Specific TB Mortality Variation
In this visualization, a subset of countries was selected using a filter mechanism to study the variations in Tuberculosis (TB) mortality rates. The filter was applied based on the year, allowing for a focused examination of how the mortality rates in the chosen countries evolve over time.
Notably, the findings indicated significant disparities in progress, with Congo displaying limited improvement while China showcased notable success in decreasing mortality rates.
Visualization 8: Food Supply Categories and TB Mortality Rates
In this animated map visualization, we introduced a calculated field called "Food Supply Category" using the provided code:
Food Supply Category:
IF AVG([Food supply (kcal per capita per day)]) < 2000 THEN 'Low <2000'
ELSEIF AVG([Food supply (kcal per capita per day)]) >= 2000 AND AVG([Food supply (kcal per capita per day)]) < 3000 THEN 'Medium >2000 and <3000'
ELSE 'High > 3000'
END
The animation tracked the transition of countries between food supply categories over time, revealing a noteworthy trend: as countries transitioned from low to high food supply ranges, there was a corresponding decrease in Tuberculosis (TB) mortality rates.
Visualization 9: Vaccine coverage vs Healthcare expenditure in 2007
In this visualization, we explored the relationship between vaccine coverage and healthcare expenditure for the year 2007. The visualization incorporated two key
metrics: vaccine coverage, represented by a color gradient, and healthcare expenditure. Notably, the size of data points indicated the number of deaths, revealing a pattern where countries with lower vaccine coverage experienced higher mortality rates.
Dashboards:
The dashboard presents a comprehensive overview of key factors influencing Tuberculosis (TB) outcomes globally. The protein intake visualization highlights a steady decline in TB mortality rates with increased protein consumption, emphasizing the potential role of nutrition in combating the disease. Together, these visualizations underscore the intricate interplay of nutritional factors in shaping TB outcomes, providing valuable insights for public health interventions on a global scale.
The dashboard provides a comprehensive perspective on the multifaceted dynamics influencing Tuberculosis (TB) outcomes worldwide. Together, these visualizations contribute to a comprehensive understanding of the interplay between healthcare factors, demographics, and vaccination efforts in shaping the global landscape of TB outcomes.
### CONCLUSION:
1. How does protein intake impact Tuberculosis (TB) mortality rates in children under 5 years?
Answer: Our analysis reveals a consistent decline in TB mortality rates with an increase in protein intake, suggesting a potential protective effect of adequate protein consumption on the vulnerability of children under 5 to TB.
2. What is the combined impact of protein and fat intake on TB prevalence and outcomes?
Answer: While there is a decline in TB cases over time, the protein to fat ratio remains relatively stable. This prompts further investigation into the nuanced
relationship between macronutrients and TB incidence, indicating that the impact of fat intake may not be as pronounced as protein.
3. How does food supply influence TB mortality rates globally?
Answer: The animated world map categorizing countries by food supply showcases a compelling correlation between improved food supply and decreased TB mortality rates. Countries transitioning from low to high food supply categories experience a notable reduction in TB mortality.
4. What is the relationship between vaccine coverage, healthcare expenditure, and TB mortality in 2007?
Answer: Higher vaccine coverage is associated with lower TB mortality rates, underlining the success of global immunization programs. The visualization of healthcare expenditure highlights its potential impact, with countries experiencing suboptimal healthcare infrastructure facing higher mortality rates.
5. How does population size correlate with TB mortality rates?
Answer: Our analysis shows that populous countries, such as India and China, do not necessarily exhibit the highest TB mortality rates. Population size alone does not determine TB outcomes, emphasizing the need for nuanced considerations in understanding global TB dynamics.
6. What is the impact of vaccination on TB mortality rates globally?
Answer: The visualization of vaccination vs. mortality demonstrates a clear correlation between higher vaccine coverage and reduced TB mortality. Countries achieving greater vaccine coverage experience a proportionally lower burden of TB-related deaths.
7. How do nutritional habits and healthcare infrastructure collectively influence TB outcomes globally
Answer: Our synthesis of visualizations underscores the intricate interplay of nutritional factors and effective healthcare infrastructure in shaping TB outcomes.
The complexities highlight the need for multifaceted strategies to address the global burden of TB.
8. How have the death rates from Tuberculosis (TB) changed over a specific period in a set of countries (China, India, Pakistan, Bangladesh, Philippines, Indonesia, Nigeria, Democratic Republic of Congo)?
Answer: The analysis focused on a specific set of countries over a defined period, unraveling nuanced patterns in the temporal evolution of TB death rates. China demonstrated substantial improvement, showcasing a consistent decline in TB mortality rates. India, while experiencing an overall decline, faced persistent challenges, reflecting the complex landscape of TB dynamics. Pakistan and Bangladesh exhibited varied trajectories, suggesting unique contextual factors influencing TB outcomes. The Philippines showcased positive trends, aligning with successful interventions. Indonesia, Nigeria, and the Democratic Republic of Congo faced challenges with varying degrees of progress. This exploration prompts further investigation into the factors driving diverse trends, facilitating the identification of effective interventions and targeted strategies to address TB effectively in each context.
Additional research questions I look forward to in solving in the future are:
• What is the impact of emerging infectious diseases, such as the current state of global pandemics, on TB outcomes, and how can integrated healthcare systems effectively manage dual health challenges?
• How does the genetic susceptibility of populations interact with environmental factors to shape the risk profile for TB, and can personalized medicine approaches be applied to enhance prevention and treatment?
• What role does the digital divide play in accessing healthcare information and services related to TB, and how can innovative technologies be leveraged to bridge gaps and improve health literacy?
• How do geopolitical factors, including conflict and migration patterns, influence the spread and persistence of TB, and what strategies can be implemented to address TB in regions affected by political instability?
• What are the long-term effects of antibiotic resistance on TB outcomes, and how can interdisciplinary research inform the development of novel therapeutic interventions to combat drug-resistant strains?
• How do economic inequalities and disparities in access to education impact TB outcomes, and what policy measures can be implemented to address these social determinants on a global scale?
