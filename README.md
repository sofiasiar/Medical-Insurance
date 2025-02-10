# Medical-Insurance
Data Source:
External. Obtained from the website Kaggle
https://www.kaggle.com/datasets/mirichoi0218/insurance

Data Collection:
Administrative Data and Survey: Collected primarily through insurance companies.
Data Contents:
Summary: The dataset contains information about individuals' medical costs and related
personal characteristics.

Variables (Columns):
age: Age of the primary beneficiary.
sex: Gender of the insurance contractor (female, male).
bmi: Body mass index.
children: Number of children/dependents covered by insurance.
smoker: Smoking status (yes/no).
region: Beneficiary's residential region in the US (northeast, southeast, southwest,
northwest).
charges: Individual medical costs billed by health insurance.
Limitations:
Limitations might include how the data was collected (e.g., self-reported data might
have biases), the representativeness of the sample, and potential missing values.
Relevance:

Scenario 1: Project Objective: Predict medical costs.
Hypothesis: Smoking status is a strong predictor of medical costs.
Relevance: age, sex, bmi, children, smoker, region: All are potentially relevant. These
variables could influence medical costs. smokers are particularly relevant to
the hypothesis.
Charges: This is the dependent variable

Scenario 2: Project Objective: Investigate regional di􀆯erences in medical costs.
Hypothesis: Medical costs are higher in the Northeast region compared to other
regions.
Relevance:
Region: This is the key variable for this objective.
charges: This is what you're comparing across regions.
age, sex, bmi, children, smoker: Potentially relevant.


Scenario 3: Project Objective: Analyze the impact of family size on medical costs.
Hypothesis: The number of children/dependents is positively correlated with
medical costs.
Relevance:
Children: This is the independent variable of interest.
Charges: This is the dependent variable.
age, sex, bmi, smoker, region:
Project Goals:
Identify the key factors that contribute to high medical costs.
Understand regional variations in medical costs.
Data Profile:
Data Profile for df_clean
1. Variables and Data Types:
age: Quantitative, time-invariant, discrete
sex: Qualitative, time-invariant, nominal
bmi: Quantitative, time-invariant, continuous
children: Quantitative, time-invariant, discrete
smoker: Qualitative, time-invariant, binary
region: Qualitative, time-invariant, nominal
charges: Quantitative, time-variant, continuous


Data cleaning:
Duplicate row found and removed.

Questions:
Hypothesis: Smoking status is a strong predictor of medical costs.
How does smoking prevalence vary across di􀆯erent demographic groups?
Within the smoker group, are there other factors (like bmi or children) that further
influence the charges, and do these factors interact with sex?

Hypothesis: Medical costs are higher in the Northeast region compared to other regions.
Are we comparing average charges across regions, or total charges for each region?
Hypothesis: The number of children/dependents is positively correlated with medical
costs.
Are there specific age groups where the correlation between children and charges
is stronger?
Does the relationship between children and charges vary by sex or smoking status?
Tableau Storyboard
https://public.tableau.com/views/2_5Histogram-Box/Sheet2?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
