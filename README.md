# predict_final_income_censusdata
### Capstone Project - Predict Final Income from Census Data - Classification
#### About Data
This data was extracted from the census bureau database found at http://www.census.gov/ftp/pub/DES/www/welcome.html.

Donor: Ronny Kohavi and Barry Becker, Data Mining and Visualization Silicon Graphics.
e-mail: ronnyk@sgi.com for questions.
Extraction was done by Barry Becker from the 1994 Census database. A set of reasonably clean records was extracted using the following conditions: ((AAGE>16) && (AGI>100) && (AFNLWGT>1)&& (HRSWK>0))

#### Prediction Task
The Census Income dataset contains 13 independant variables for use in predicting whether final income is above or below $50,000 USD

#### Census Income:
The Census Income dataset contains 13 independant variables for use in predicting whether final income is above or below $50,000 USD

The variables are as follows:
Age- A continuous numerical variable representing the age of the individual surveyed.

Workclass- Factors of the following options, “Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.”

Fnlwgt- Final weight, a continuous numerical variable describing a Census-specific value for how many other individuals this entry represents in the population. This value will likely be meaningless for predicting income, and it shows no relationship with other variables.

Education- Factors of the following options, “Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.” This represents the final level of the individual’s education at the time of the survey.

Education-num- A continuous numerical variable describing how many years of education the individual has had.

Marital-status- Factors of the following options, “Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.”

Occupation- Factors of the following options, “Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.”

Relationship- Factors of the following options, “Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.”

Race- Factors of the following options, “White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.”

Sex- Factors of the following options, “Female, Male.”

Capital-gain- A continuous numerical variable describing investment income which is not from wage or salary.

Capital-loss- A continuous numerical variable describing investment depreciation which is not from wage or salary.

Hours-per-week- A continuous numerical variable describing how many hours the individual currently works per week.

Native-country- Factors of the following options, “United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.”

