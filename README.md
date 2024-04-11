

#### Problem Statement:
The research aims to investigate the factors influencing the default rate of a credit platform using logistic regression and XGBoost models. Key objectives include identifying significant variables impacting default rates and providing insights for risk assessment in lending.

#### Data Source:
The data for the article is sourced from the Data Science Website Heywhale Community at https://www.heywhale.com/home/dataset. The dataset comprises loan records from a credit platform, consisting of two CSV files with a total of 1 million entries. 800,000 entries are in the training set, while 200,000 entries are in test set A. The dataset contains 47 columns of variables, with 15 columns being anonymous variables. Certain information such as employmentTitle, purpose, postCode, and title have undergone desensitization processing.
The dataset used for analysis includes information on user social demographic variables, transaction details, and special behavioral features.

#### Data Processing:
- Handling Missing Values: Employed random forest imputation for the 'employmentLength' variable.
- Encoding Categorical Variables: Utilized One-Hot Encoding for categorical data like 'homeOwnership', 'verificationStatus', and 'purpose'.
- Feature Engineering: Created a new variable 'CreditLine' by calculating the duration between 'issueDate' and 'earliesCreditLine'.

#### Solutions:
- Utilized logistic regression and XGBoost models to analyze the impact of various factors on the default rate.
- Identified correlations between variables and conducted dimensionality reduction using principal component analysis.
- Provided recommendations such as cautious lending for long-term loans due to higher default risks associated with extended loan durations.


