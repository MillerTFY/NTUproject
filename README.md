# NTUproject

1. Introduction & Objective

1.1 Introduction

With the rise of technology, globalization, and concerns over Covid-19 being easily transmissible through contaminated surfaces, contactless and cashless payment options have been a new norm for consumers in conducting daily purchases. Credit cards, being one of the widely used alternatives, evolved from vendors allowing customers to receive items on credit with the expectation that the account balances be repaid in a given timeframe. It serves as a valuable financial tool when used responsibly, providing accessibility and convenience to users, through near field communication (NFC) cards, mobile apps, and wearables.

However, individuals may succumb to credit card defaults upon successive failures to repay its principal amount. This is often tagged with high-interest rates, for an extended period of time. Especially during unsettling economic times, with defaults occurring after six months in a row of not making at least the minimum payment due by holders. Banks are, henceforth, put at risk when these numbers start to accumulate.

It is therefore vital, in the perspective of banks, to conduct an investigation through credit analysis across the population of its credit cardholders to identify the key warning signs of poor credit and the probability of an individuals' repayment abilities. In this report, Six AI modeling techniques are adopted to provide an in-depth study, targeting to improve the bank’s loaning processes. Through analyzing customers’ data sets and combining machine-learning algorithms, better predictions can raise early warning flags to capture credit defaulters in advance.

1.2 Objectives

To address the study on credit card defaults, this project aims to achieve the following objectives:

● In order to reduce the risk of banks’ exposure in large credit card default incidents, utilize various data classification techniques with a large data set of customer records to screen for potential credit card defaulters.

● Identify common key traits, features, and conditions through the pool of customers’ datasets for early detection and trigger for preventive measures.

● To avoid experiencing customer defaults with a snow-balling effect, derive accurate predictions and recommendations of test results to the flag for default accounts in advance.

2. Literature Review

2.1 Methodology

Using machine learning methods on a large dataset of historical customer credit lines in predicting credit defaults, and analyzing features of customer behaviors associated with credit delinquencies, is a widely discussed topic across researchers in this era.

Butaru et al (2016) have illustrated the benefits of running large data sets collected across six banks to construct Decision Trees, regularized Logistic Regression, and Random Forest models to draw conclusions on consumers’ tendencies on credit delinquencies and to derive a prediction. Meanwhile, Neema and Soibam (2017) drew a conclusion on Random Forest, amongst seven techniques in comparison, that it provides the highest predictive accuracy in credit card defaults, thanks to the non-linearity on various cost factors.

2.2 Determinants of Credit Card Defaults

Identifying key features of credit card default behaviors can flag early warning signals to banks or risk management teams within an institution. T. M. Alam et al (2020) explore multiple factors such as an individual’s payment history, approved credit limits, client’s personal information, and economic status are closely linked to the probability of defaults. Neema and Soibam (2017) further asserted the importance of placing a heavier weight on credit limit, billing and payment information, while a lighter weight other discriminant variables are less significant like personal information.

2.3 Consequence of Credit Card Defaults

The key takeaway of this study is to provide better insights to card issuers such that a more stringent model can be rolled out starting from the client application process. Potential applicants should be carefully assessed based on the most relative characteristics indicating a higher probability of default. H. Kim et al (2018) emphasized the avoidance of significant losses institutions would suffer, with every small improvement in modeling accuracy for high-risk defaulters.

3. Business Solution (Problem Statement)

With poor and rising uncertainties in the global macroeconomics environment, such as entering a recession or rising unemployment rate, card issuers face an increasing rate of credit card delinquencies, especially from the lower-income earners. This personal line of credit holds one of the highest interest rates when compared to a mortgage or auto loan, as it does not require collateral to be granted with a card. Hence, it is targeted for large-scale consumer consumption.

To reduce the susceptibility of banks with a hefty write-down on outstanding balances left unpaid and funding the losses from their reserves, enhancing a classifier performance on AI modeling can provide solutions to better predict potential credit card defaults, and help identify key factors leading to a default.

4. Exploratory Data Analysis

4.1 Dataset Information

This dataset contains 30,000 records on default payments, demographic factors, credit data, repayment records, and bill statements of credit card owners in Taiwan between April 2005 to September 2005.

Column ID Details

ID ID assigned to each individual client

LIMIT_BAL Amount of credit limit given to the client based on their customer profile

SEX Gender of client (1 = Male, 2 = Female)

EDUCATION Highest level of education obtained (1 = graduate school, 2 = university, 3 = high school, 4 = others, 5 = unknown, 6 = unknown)

MARRIAGE Last reported marital status (1 = Married, 2 = Single, 3 = Others)

AGE Client age in years

PAY_0 Repayment status in September, 2005 (-1 = pay duly, 1 = payment delay for one month, 2 = payment delay for two months, … 8 = payment delay for eight months, 9 = payment delay for nine months and above)

PAY_2 Repayment status in August, 2005 (Same as above)

PAY_3 Repayment status in July, 2005 (Same as above)

PAY_4 Repayment status in June, 2005 (Same as above)

PAY_5 Repayment status in May, 2005 (Same as above)

PAY_6 Repayment status in April, 2005 (Same as above)

BILL_AMT1 Amount of outstanding balance in September, 2005 (NT dollar)

BILL_AMT2 Amount of outstanding balance in August, 2005 (NT dollar)

BILL_AMT3 Amount of outstanding balance in July, 2005 (NT dollar)

BILL_AMT4 Amount of outstanding balance in June, 2005 (NT dollar)

BILL_AMT5 Amount of outstanding balance in May, 2005 (NT dollar)

BILL_AMT6 Amount of outstanding balance in April, 2005 (NT dollar)

PAY_AMT1 Amount of previous bill payment in September, 2005 (NT dollar)

PAY_AMT2 Amount of previous bill payment in August, 2005 (NT dollar)

PAY_AMT3 Amount of previous bill payment in July, 2005 (NT dollar)

PAY_AMT4 Amount of previous bill payment in June, 2005 (NT dollar)

PAY_AMT5 Amount of previous bill payment in May, 2005 (NT dollar)

PAY_AMT6 Amount of previous bill payment in April, 2005 (NT dollar)

default.payment.next.month Payment defaulted (1 = Yes, 0 = No)
