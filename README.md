# Cardiovascular Disease & Diabetes in Nigeria: Data-Driven Insights from WHO

DESCRIPTION 

This project uses WHO datasets (https://ncdportal.org/CountryProfile/GHE110/NGA) to explore how lifestyle and biological risk factors drive the rising burden of cardiovascular disease (CVD) and diabetes in Nigeria. Non-communicable diseases (NCDs) like heart disease and diabetes are rising globally, and Nigeria is no exception.

The analysis focuses on two main questions:

-Which lifestyle and metabolic risk factors are most strongly associated with CVD deaths in Nigeria?

-How has diabetes prevalence changed over time, and what does this mean for the future?


<img width="781" height="509" alt="Screenshot (22)" src="https://github.com/user-attachments/assets/fe5bd4ad-a8d0-4e2e-b929-3f6d6ef6db90" />

INTRODUCTION

Cardiovascular diseases (CVDs) and diabetes are two of the fastest-growing health challenges in Nigeria. Once considered “diseases of affluence,” they are now major causes of death and disability in low- and middle-income countries.

The World Health Organization (WHO) highlights that non-communicable diseases (NCDs) now account for nearly one-third of all deaths in Nigeria. Understanding how different risk factors interact with outcomes like CVD deaths and diabetes prevalence is essential for prevention, policy, and healthcare planning.

This project uses WHO’s NCD Country Profile data for Nigeria to explore:

-How strongly risk factors (like obesity, cholesterol, inactivity, tobacco use) are linked to CVD deaths.

-How diabetes prevalence has changed over time in different age groups.

-What these patterns suggest about the future burden of NCDs in Nigeria.

By combining data analysis and public health storytelling, the project demonstrates how data science can make complex health issues more visible and provide insights that matter for real-world impact.

AIM

The aim of this project is to analyze the relationship between major risk factors and the burden of cardiovascular diseases (CVD) and diabetes in Nigeria.
The project also seeks to:

-Understand how lifestyle and biological factors (such as obesity, high cholesterol, physical inactivity, and tobacco use) correlate with CVD-related deaths.

OVERVIEW

Cardiovascular diseases (CVD) and diabetes are among the leading causes of illness and premature deaths worldwide, and Nigeria is no exception. With changing lifestyles, urbanization, and dietary shifts, these non-communicable diseases are rising steadily and placing a heavy burden on both individuals and the healthcare system.

This project takes a data-driven look at how key risk factors including obesity, physical inactivity, high cholesterol, hypertension, and diabetes itself influence CVD and diabetes outcomes. By analyzing WHO  dataset, I explored trends, correlations, and insights that show the hidden links between lifestyle habits and disease outcomes.

The goal is to create actionable knowledge that can inform awareness, prevention, and healthier choices in Nigeria.

PROCESS

I followed a clear step-by-step approach:

-Data Collection:  Pulled WHO dataset on cardiovascular diseases, diabetes, and related risk factors such as obesity, hypertension, and physical inactivity.

-Data Cleaning & Preparation: Handled duplicates/missing values, and structured it into pivot tables so analysis would be smooth.

-Exploratory Analysis: Looked at trends, gender differences, and year-to-year changes in key indicators (like diabetes prevalence, hypertension cascade, and CVD deaths).

-Correlations & Overlays: Compared indicators side-by-side (e.g., obesity vs. diabetes, inactivity vs. CVD deaths) to see how lifestyle factors connect to outcomes.

-Visualization: Created clear plots to bring the story in the data to life.

-Insights & Interpretation: Translated the numbers into meaningful takeaways about where Nigeria stands and what the data might be telling us.

TOOLS AND LIBRARIES

To explore and visualize the data, I worked mainly with Python and a few libraries:

-Pandas: for cleaning, reshaping, and organizing the data into pivot tables.

-NumPy: for handling numerical operations.

-Matplotlib & Seaborn: to create line graph  that make the trends easier to see.

-SciPy: for calculating correlations and checking how strongly risk factors connect with disease outcomes.

-Jupyter Notebook: as the main workspace for writing, running, and documenting the analysis step by step.


FINDINGS 

<img width="782" height="428" alt="Screenshot (24)" src="https://github.com/user-attachments/assets/64e52bad-1f0d-4c65-9fed-82215709e361" />

<img width="533" height="160" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/325819f4-58c5-46c8-8e67-1d64b2813a63" />

<img width="861" height="544" alt="Screenshot (18)" src="https://github.com/user-attachments/assets/70fa54a5-4eef-48b2-bd28-af669510a9a6" />

<img width="434" height="214" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/9311b389-65b5-46b2-9474-cc1bdcc0ffe3" />

<img width="796" height="513" alt="Screenshot (23)" src="https://github.com/user-attachments/assets/b21c78d4-a9bd-4912-94d0-71d77f56db67" />


1.Diabetes Prevalence is Rising Steadily

-Both adults aged 18+ and 30+ show a consistent increase in diabetes between 2000 and 2023.

-Women have higher prevalence rates than men, and the gender gap widens over time.

2.Treatment Coverage is Improving, but Still Too Low

-Among adults aged 30+, treatment coverage has gradually increased.

-However, treatment uptake remains much lower than the actual prevalence, especially for men. This shows a gap between diagnosis and access to effective care.

3.Physical Inactivity is Declining, but Women Remain More Inactive

-Physical inactivity has dropped steadily in both men and women over the last two decades.

-Men are more physically active than women overall, highlighting a gender difference that may affect long-term health outcomes.

4.Hypertension Strongly Predicts CVD Deaths

-Controlled, diagnosed, and treated hypertension all show very strong positive correlations with cardiovascular deaths.

-Interestingly, raised blood pressure has a negative correlation with CVD deaths, suggesting that better blood pressure control over time may be helping reduce premature deaths.

5.Obesity and Diabetes are Major Risk Drivers

-Obesity, overweight, high cholesterol, and diabetes (18+) all show strong positive correlations with CVD deaths.

-Among these, diabetes has the highest correlation, confirming its role as a critical driver of CVD mortality.

6.Lifestyle Risk Factors Show Unexpected Patterns

-Tobacco use, alcohol consumption, and physical inactivity all showed negative correlations with CVD deaths in the dataset.

-This likely reflects data limitations or under-reporting, not a true protective effect. It highlights the importance of interpreting public health data with caution.

 INSIGHT
 
-The rising prevalence of diabetes and obesity signals a growing NCD (non-communicable disease) burden in Nigeria.

-Although treatment coverage for diabetes is improving, it still lags far behind prevalence, especially in men, pointing to access and equity issues. 

-Physical inactivity is falling, but women remain more inactive than men, which may put them at higher long-term risk.

-Hypertension control is key: the strong correlation between hypertension and CVD deaths underlines the urgent need for better screening and treatment.

-Lifestyle risk factors (tobacco, alcohol, inactivity) showed unusual correlations, reminding us that national datasets may have reporting gaps or confounding variables that need further study.

RECOMMENDATIONS

1.Scale Up Early Detection & Treatment

-Increase screening for diabetes and hypertension, especially in adults over 30.

-Improve access to affordable treatment, with targeted programs for men who lag behind in coverage.

2.Promote Active Lifestyles

-Invest in community-level programs that encourage physical activity, with tailored interventions for women.

-Urban planning should prioritize safe spaces for exercise and active transport.

3.Strengthen Public Health Campaigns

-Raise awareness of obesity, diabetes, and hypertension risks through culturally sensitive health promotion.

-Address myths or under-reporting around tobacco and alcohol by integrating behavioral health campaigns.

4.Close the Gender Gap in NCD Care

-Encourage gender-sensitive healthcare delivery, ensuring women and men both get equal preventive and treatment opportunities.

5.Enhance Data Quality & Surveillance

-Strengthen national health information systems to improve reliability of lifestyle risk factor reporting.

-Use longitudinal and community-based surveys to validate national-level trends.

CONCLUSION

This analysis highlights the growing impact of diabetes, obesity, and hypertension on cardiovascular deaths in Nigeria. While progress has been made in reducing inactivity and expanding treatment coverage, the burden of NCDs continues to rise thereby threatening future health outcomes. Tackling these challenges will require a comprehensive public health strategy that combines early detection, treatment access, healthier environments, and stronger data systems.

By turning insights into action, Nigeria can not only reduce premature deaths from cardiovascular diseases but also strengthen its overall health system to manage the rising tide of chronic diseases.

-Track trends in diabetes prevalence across different adult age groups over time.

-Provide insights that can support better awareness, policy-making, and targeted interventions for reducing the impact of non-communicable diseases in Nigeria.


The project is about using data to tell the story of how everyday choices and risk factors connect to two of the country’s biggest health challenges  and why this matters for the future of public health.

NOTE

Click the files section for the python code
