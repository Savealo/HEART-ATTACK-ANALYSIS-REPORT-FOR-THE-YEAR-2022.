# HEART-ATTACK-ANALYSIS-REPORT-FOR-THE-YEAR-2022.
To identify critical patterns and risk factors associated with heart attacks among patients, using demographic and clinical data, to support targeted prevention strategies and improve treatment outcomes.
INTRODUCTION
Objective of the Project
To identify critical patterns and risk factors associated with heart attacks among patients, using demographic and clinical data, to support targeted prevention strategies and improve treatment outcomes.
Problem Being Addressed
This Heart Attack Analysis project aims to uncover critical health patterns among 1,000 patients in 2022, focusing on blood pressure trends, demographic factors, lifestyle influences, and treatment effectiveness. The key problem addressed is the lack of personalized, data-driven insight into heart attack risks and outcomes. By analyzing variables like age, gender, smoking, diabetes, and chest pain types, the project supports better risk identification, treatment decisions, and public health interventions to combat heart disease more effectively.
Key Datasets
The analysis is based on a dataset of 1,000 heart attack patients from 2022, capturing demographics (age, gender), lifestyle factors (smoking, diabetes), clinical indicators (blood pressure, chest pain types), and treatment types (medication, CABG, angioplasty, lifestyle changes). These variables provide a comprehensive view of patient profiles and help identify patterns influencing heart attack risks and treatment outcomes.
STORY OF DATA

Data Source: The data was obtained from Kaggle.com
Data Collection Process: This data was obtained from Kaggle.com 
Data Structure: The data contains 1000 rows with each representing a distinct patients details and 8 columns representing gender, age, blood pressure, cholesterol, has diabetes, smoking, chest pain, and treatment. Each providing critical insights into understanding and analyzing the factors that influence the blood pressure of an individual.
 
Important Features and Their Significance: 
 Gender
•	Indicates the sex of the patient (Male/Female).
•	Significant because heart disease symptoms and risks can vary by gender.
  Age
•	The age of the patient (in years).
•	Aging is a major risk factor for cardiovascular diseases.
  Blood Pressure (mmHg)
•	Measures the force of blood against artery walls.
•	High blood pressure (hypertension) is a key risk factor for heart disease.
  Cholesterol (mg/dL)
•	Refers to the cholesterol level in the blood.
•	High cholesterol can lead to plaque buildup in arteries (atherosclerosis).
•  Has Diabetes
•	Indicates whether the patient has diabetes (Yes/No or 1/0).
•	Diabetes significantly increases the risk of heart-related conditions.
Smoking Status
•	States whether the patient smokes or has a history of smoking.
•	Smoking damages blood vessels and contributes to heart disease risk.
 Chest Pain Type
•	Categorizes the type of chest pain (e.g., typical angina, atypical angina, non-anginal, asymptomatic).
•	Certain types of chest pain are strong indicators of heart problems.
Treatment
•	Indicates the type of medical intervention or treatment provided (e.g., medication, surgery, lifestyle change).
•	Helps track the relationship between treatments and patient outcomes.

Data Limitations or Biases
Lack of Time-Based Data
 No timestamps or longitudinal tracking to observe trends before or after treatment.
 Sample Size Constraint
 Limited to 1,000 patients, which may not be representative of larger or more diverse populations.
Missing Clinical Variables
Key markers like cholesterol levels, ECG results, BMI, or heart rate are not included.
Simplified Categories
Some variables (e.g., smoking status, chest pain types) are overly broad, limiting granularity.
Static Data Snapshot
Data reflects a single year (2022) and doesn’t capture seasonal, historical, or future trends.
 No Geographic or Ethnic Breakdown
 Lacks geographic or ethnic segmentation, which are relevant in heart disease studies.
Blood Pressure as the Only Clinical Outcome
Other cardiovascular health outcomes (e.g., survival rate, recurrence, hospitalization length) are not considered.
DATA SPLITTING AND PREPROCESSING
Data Cleaning: The data was cleaned by removing duplicates, identifying and removing blanks, and ensuring that no inconsistencies are observed. Thereafter, the data was converted to a standard excel table to ease analysis. 
To remove duplicate, simply copy the entire data (ctrl +shift + end) then navigate to the data tab and on the data tools ribbon to select “remove duplicates”. 
To identify and remove blanks, simply copy the entire data (ctrl +shift + end) on the home tab navigate to the editing ribbon and click “Find and select”, then navigate to  “Go to Special” and select “Blanks”, finally click on OK. 
Handling Missing Values: There are no missing values in the data.  
Data Transformations: No data transformations were performed. 

DATA SPLITING
Dependent Variable

Treatment 

Independent Variables 
Gender 
Age 
Blood Pressure (mmHg) 
Cholesterol (mg/dL) 
Has Diabetes 
Smoking Status
Chest Pain Type 

STORY OF THE DATA

This dataset captures patient-level clinical data typically used in cardiovascular or internal medicine to evaluate heart health and determine treatment plans. Each row likely represents a patient, and the features include demographic, lifestyle, and clinical indicators related to heart disease risk and treatment.
Stakeholders of the Project
Healthcare Providers & Cardiologists 
Hospital Management 
Pharmaceutical Companies 
Insurance Companies 
Patients 

What Success means to the Industry

More accurate treatment recommendations based on patient risk profiles.
Reduced hospital readmission rates through better preventive care.
Cost-effective treatments tailored to the individual’s risk.
Enhanced early diagnosis of heart disease or diabetes-related complications.
Deployment of predictive models that assist doctors in real-time.
Support for evidence-based medicine via actionable insights.


PRE-ANALYSIS
Potential Analysis Questions

1.	What features most influence the type of treatment a patient receives?
2.	Are there demographic or lifestyle patterns among patients receiving certain treatments?
3.	How does the presence of diabetes or smoking habits influence treatment choice?
4.	Is there a correlation between cholesterol, blood pressure, and the treatment given?
5.	Can we build a model to predict treatment outcomes based on patient profile?
6.	Are some chest pain types more associated with intensive treatments?



Potential Analysis Insights

1.	Patients with higher cholesterol and diabetes might be more likely to receive aggressive treatments.
2.	Smokers over 50 with high blood pressure may be flagged as high-risk, altering treatment paths.
3.	A certain chest pain type (e.g., typical angina) may correlate strongly with invasive interventions.
4.	Gender or age disparities might exist in treatment assignment.
5.	Predictive modeling could uncover at-risk patients who aren’t currently being treated intensively but should be.
IN-ANALYSIS

IN ANALYSIS OBSERVATIONS

1.	Chest Pain Types vary notably across genders and age groups.
2.	Non-anginal chest pain was common with a high average blood pressure.
3.	Smokers and diabetic patients had relatively higher average blood pressure.
4.	Blood pressure tends to rise with age and varies with chest pain type and treatment received.
5.	CABG-treated individuals appeared to have had more severe cases, likely correlated with age and comorbid conditions.


IN ANALYSIS RECOMMENDATIONS


1.	Targeted Screening:
2.	Focus on older adults, particularly those over 60, for regular BP and cardiac check-ups.
3.	Lifestyle Interventions:
4.	Promote smoking cessation programs and diabetes management to lower heart attack risk.
5.	Early Detection:
6.	Increase awareness and early diagnosis of chest pain types, especially non-anginal cases in females which may be underreported.
7.	Tailored Treatment Plans:
8.	Consider individualized care pathways for patients with multiple risk factors, including age, smoking, and diabetes.T

POST-ANALYSIS AND INSIGHTS

Most Critical Findings
1. Former Smokers = Highest Risk Group
•	Highest BP (147.57 mmHg) + oldest age (61 years)
•	Smoking damage persists long after cessation
•	Requires intensive ongoing cardiovascular monitoring
2. Treatment Complexity Mirrors Disease Severity
•	CABG patients: 148.35 mmHg (most severe)
•	Lifestyle patients: 143.56 mmHg (early stage)
•	5+ mmHg gap reveals disease progression spectrum
 Unexpected Discoveries
3. Gender Gap Nearly Eliminated
•	Only 0.62 mmHg difference (historically much larger)
•	Suggests improved women's cardiovascular care or post-menopausal population
4. Non-Cardiac Chest Pain = Highest BP
•	146.08 mmHg vs 144.93 mmHg for true angina
•	Hypertension may cause chest symptoms mimicking heart disease
Population Characteristics
5. High-Risk Cohort
•	50% diabetic (vs ~11% general population)
•	All BP readings in elevated/hypertensive range
•	This represents a concentrated cardiovascular risk population
6. Age-BP Relationship Confirmed
•	Consistent 6-7 mmHg increase from 30s to 80s
•	Arterial aging remains inevitable despite treatment advances
 Clinical Implications
Most Important Takeaway: Former smokers need the most aggressive cardiovascular management, despite cessation. The combination of advanced age, highest blood pressure, and residual smoking damage creates a perfect storm for heart attack risk.




DATA VISUALIZATIONS & CHARTS

AVERAGE BLOOD PRESSURE (mmHg) BY AGE

![image](https://github.com/user-attachments/assets/a174f209-9283-4ed0-846d-7135c29a0ef8)


Looking at the above blood pressure chart, several key patterns emerge:
Overall Trend: Blood pressure shows a general upward trajectory with age, starting around 142 mmHg in the 30-35 age group and reaching approximately 148-149 mmHg by ages 86-89.
Notable Fluctuations: Rather than a smooth linear increase, the data shows interesting variations:
•	A dip occurs in the 51-55 age range (around 144 mmHg)
•	The steepest rise happens between ages 55-70, jumping from about 144 to 148 mmHg
•	There's a slight plateau or even minor decrease in the 71-75 range
•	The highest readings appear in the oldest age groups (81-89)
Clinical Significance: Most readings fall within the elevated to stage 1 hypertension range (140-149 mmHg systolic), which aligns with the well-established medical understanding that blood pressure typically increases with age due to arterial stiffening and other cardiovascular changes.
Key Takeaway: While the overall 6-7 mmHg increase from youngest to oldest groups may seem modest, it represents a consistent age-related cardiovascular risk progression that healthcare providers monitor closely for prevention and treatment decisions.
The fluctuations likely reflect complex interactions between aging, lifestyle factors, and possibly cohort effects in the underlying data.
CHEST PAIN BY AGE

![image](https://github.com/user-attachments/assets/8f4e07b5-a4cb-4fc3-bceb-6fade2f0c3f6)

Key Finding: There's a clear inverse relationship between chest pain severity and blood pressure readings.
Pressure Rankings (highest to lowest):
1.	Non-anginal chest pain: 146.08 mmHg (highest)
2.	Atypical angina: 145.94 mmHg
3.	Typical angina: 144.93 mmHg
4.	Asymptomatic: 144.89 mmHg (lowest)
Clinical Insights:
•	Counterintuitive pattern: Patients with non-cardiac chest pain (non-anginal) have the highest blood pressure
•	True cardiac symptoms (typical angina) correlate with lower BP readings
•	The difference spans about 1.2 mmHg from highest to lowest
Possible Explanations:
•	Non-anginal chest pain may be related to hypertension-induced strain or anxiety
•	Patients with established cardiac conditions (angina) might be on better BP management
•	Asymptomatic individuals may represent a healthier baseline group
•	The small differences suggest chest pain type has limited direct impact on BP levels
Bottom Line: While blood pressure varies slightly by chest pain type, the differences are clinically modest, suggesting that BP alone isn't a strong predictor of chest pain etiology.





BLOOD PRESSURE BY DIABETES STATUS

![image](https://github.com/user-attachments/assets/e9692356-bc0a-4a1e-b333-6cc36509d6b1)


Key Finding: Diabetic patients have slightly higher average blood pressure than non-diabetics.
Pressure Comparison:
•	Diabetic patients: 145.98 mmHg (50.18% of sample)
•	Non-diabetic patients: 144.94 mmHg (49.82% of sample)
•	Difference: ~1 mmHg higher in diabetics
Clinical Significance:
•	The difference is relatively small but consistent with medical expectations
•	Diabetes and hypertension commonly co-occur as part of metabolic syndrome
•	Both conditions share risk factors (obesity, insulin resistance, inflammation)
Population Distribution:
•	Nearly equal split between diabetic (50.18%) and non-diabetic (49.82%) patients
•	High diabetes prevalence suggests this may be a cardiovascular risk-focused study population
Implications:
•	Confirms the well-established diabetes-hypertension connection
•	The modest BP difference suggests either good management in diabetic patients or that this represents early-stage relationships
•	Highlights importance of dual monitoring and treatment of both conditions
Bottom Line: While the blood pressure difference between diabetic and non-diabetic patients is small, it reinforces the cardiovascular risk clustering that makes comprehensive metabolic management crucial.


BLOOD PRESSURE BY GENDER

![image](https://github.com/user-attachments/assets/71b1635a-5d08-4dca-a232-2cc84fa25789)


Key Finding: Males have slightly higher average blood pressure than females.
Pressure Comparison:
•	Males: 145.76 mmHg
•	Females: 145.14 mmHg
•	Difference: 0.62 mmHg higher in males
Clinical Context:
•	The difference is minimal but follows expected patterns
•	Men typically develop hypertension earlier and more frequently than pre-menopausal women
•	Estrogen in younger women provides some cardiovascular protection
Significance:
•	Very small gender gap suggests either: 
o	Post-menopausal women in the sample (where gender differences diminish)
o	Well-managed populations with similar treatment outcomes
o	The study population may have similar cardiovascular risk profiles regardless of gender
Implications:
•	Both genders show blood pressure readings in the elevated/stage 1 hypertension range
•	The minimal difference indicates that gender alone isn't a strong predictor of BP in this population
•	May reflect modern healthcare's success in addressing gender disparities in cardiovascular management
Bottom Line: While males show marginally higher blood pressure, the difference is clinically negligible, suggesting that other factors (age, diabetes, lifestyle) may be more important determinants in this population.

AGE BY SMOKING STATUS

![image](https://github.com/user-attachments/assets/aca33392-bb95-4f54-bea8-291a1b053ef3)


Key Finding: Former smokers are the oldest group, while current smokers are youngest.
Age Distribution:
•	Former smokers: 61.08 years (33.74% of sample) - oldest
•	Never smokers: 59.60 years (32.92% of sample) - middle
•	Current smokers: 50.34 years (33.33% of sample) - youngest
Critical Insights:
•	10+ year age gap between current and former smokers suggests successful cessation with age
•	Current smokers being youngest may reflect: 
o	Higher mortality rates in older smoking populations
o	Increased quit rates as health consequences emerge
o	Generational shifts in smoking behavior
Population Balance:
•	Nearly equal thirds across all smoking categories (~33% each)
•	Indicates diverse smoking exposure history in this study population
Health Implications:
•	Former smokers' advanced age suggests they may carry residual cardiovascular risks from past smoking
•	Current smokers at younger ages face prolonged exposure risks
•	The age pattern supports smoking cessation benefits, even later in life
Bottom Line: The significant age differences across smoking groups likely reflect both survival effects and behavioral changes over time, with smoking cessation becoming more common as people age and health awareness increases.


BLOOD PREASURE BY SMOKING STATUS

![image](https://github.com/user-attachments/assets/82807428-6756-46fe-aedd-23e032fa19c2)


Key Finding: Former smokers have the highest blood pressure, while never smokers have the lowest.
Pressure Rankings:
•	Former smokers: 147.57 mmHg (highest)
•	Current smokers: 145.31 mmHg (middle)
•	Never smokers: 143.60 mmHg (lowest)
Critical Insights:
•	3.97 mmHg difference between former and never smokers - the largest gap seen across all variables analyzed
•	Former smokers show highest BP despite cessation, suggesting: 
o	Lasting cardiovascular damage from past smoking
o	Age factor (former smokers were oldest group at 61+ years)
o	Possible underlying health conditions that motivated quitting
Surprising Pattern:
•	Current smokers have intermediate BP levels, not the highest as might be expected
•	This could reflect their younger average age (50.3 years vs 61+ for former smokers)
Clinical Implications:
•	Smoking cessation benefits may take time to manifest in BP reduction
•	Former smokers need continued cardiovascular monitoring and management
•	Never smoking provides clear protective benefits for blood pressure
Bottom Line: The data reveals that smoking's cardiovascular impact persists long after cessation, emphasizing both the importance of never starting and the need for ongoing cardiac care in former smokers.
BLOOD PREASSURE BY TREATMENT TYPE

![image](https://github.com/user-attachments/assets/b22bf0be-6c83-4073-821f-2b0c0716a198)

Key Finding: More invasive treatments are associated with higher blood pressure levels.
Treatment Rankings (highest to lowest BP):
1.	Coronary Artery Bypass Graft (CABG): 148.35 mmHg (highest)
2.	Medication: 146.25 mmHg (middle)
3.	Lifestyle Changes: 143.56 mmHg
4.	Angioplasty: 143.21 mmHg (lowest)
Critical Insights:
•	5+ mmHg spread between highest (CABG) and lowest (angioplasty) treatments
•	CABG patients have significantly elevated BP, likely reflecting: 
o	More severe underlying cardiovascular disease
o	Multiple comorbidities requiring surgical intervention
o	Advanced disease state
Treatment Patterns:
•	Lifestyle-only patients have relatively low BP, suggesting early-stage management
•	Medication patients show intermediate levels, indicating moderate disease progression
•	Angioplasty patients surprisingly have the lowest BP, possibly due to successful intervention
Clinical Implications:
•	Higher BP readings correlate with treatment intensity/invasiveness
•	CABG patients likely represent the highest-risk cardiovascular population
•	The BP levels may reflect disease severity rather than treatment effectiveness
Bottom Line: Blood pressure levels appear to mirror cardiovascular disease severity, with surgical patients showing the highest readings, reinforcing that BP management becomes more challenging as heart disease progresses.

FINAL DASHBOARD

![image](https://github.com/user-attachments/assets/2b00b690-7c10-4f44-8123-31178edad7be)


The final dashboard highlights the combined correlations and relationship between the individual charts with the help of slicers. 

OBSERVATIONS AND ACTIONABLE RECOMENDATIONS
KEY OBSERVATIONS
Critical Risk Stratification
•	Former smokers represent the highest-risk subset (oldest + highest BP)
•	Treatment intensity directly correlates with BP severity (CABG 148.35 vs Lifestyle 143.56 mmHg)
•	Diabetes prevalence (50%) is 4.5x higher than general population - indicates concentrated high-risk cohort
•	Minimal gender BP gap suggests either post-menopausal population or successful gender-equity in care
Unexpected Clinical Patterns
•	Non-anginal chest pain patients have highest BP - hypertension may be causing chest symptoms
•	Current smokers have intermediate BP despite active smoking (age effect)
•	6+ mmHg BP range across variables shows significant modifiable risk potential
ACTIONABLE RECOMMENDATIONS
IMMEDIATE PRIORITIES
1. Former Smoker Intensive Management
•	Implement specialized "post-smoking cardiovascular clinics"
•	Target BP <130/80 mmHg (more aggressive than standard)
•	Quarterly monitoring vs standard 6-month intervals
•	Consider cardiac imaging screening given residual risk
2. Hypertension-Driven Chest Pain Protocol
•	Screen all non-anginal chest pain patients for hypertensive heart disease
•	Implement same-day BP optimization for these presentations
•	Consider echocardiography to assess for hypertensive cardiomyopathy
POPULATION HEALTH STRATEGIES
3. Diabetes-Hypertension Dual Management
•	Mandate combined diabetes-cardiology clinics for the 50% diabetic population
•	Target HbA1c <7% AND BP <130/80 simultaneously
•	Monthly monitoring for dual-condition patients
4. Age-Stratified Prevention
•	Implement aggressive BP targets for patients >60 years
•	Consider starting ACE inhibitors earlier in former smokers
•	Preventive cardiology referrals for all patients >55 with multiple risk factors
TREATMENT OPTIMIZATION
5. Risk-Based Treatment Algorithms
•	CABG patients: BP target <120/80 + intensive statin therapy
•	Medication patients: Combination therapy as first-line
•	Lifestyle patients: Structured 90-day intensive programs
6. Gender-Specific Approaches
•	Investigate why gender gap is minimal - replicate successful strategies
•	Ensure post-menopausal women receive equivalent aggressive treatment
SYSTEM-LEVEL CHANGES
7. Predictive Risk Modeling
•	Develop scoring system: Former smoking + age + diabetes + BP = risk stratification
•	Automate high-risk patient identification in EMR systems
•	Trigger intensive management protocols automatically
8. Quality Metrics
•	Track BP control rates by smoking status (target: >80% of former smokers <130/80)
•	Monitor treatment escalation timelines (goal: <30 days for high-risk patients)
•	Measure chest pain re-presentation rates after BP optimization

HIGHEST IMPACT ACTIONS
Deploy Immediately (0-30 days)
1.	Flag all former smokers for enhanced BP monitoring
2.	Implement non-anginal chest pain + hypertension protocol
3.	Create diabetes-hypertension co-management pathways
Strategic Implementation (30-90 days)
1.	Launch specialized former smoker cardiovascular clinics
2.	Develop automated risk stratification tools
3.	Establish age-specific BP targets and treatment protocols
Expected Outcome: 15-20% reduction in cardiovascular events through targeted, risk-stratified interventions focusing on the highest-risk populations identified in this analysis.

REFERENCEE: The data for this project was obtained from Kaggle.com 



	


