# Hackathon_LoanRepaymentAnalysis
Detailed analysis of given dataset to derive insights on applicant culture most likely to default to help develop strategies to tackle the same


The video in the link below will showcase my presentation of the said analysis
https://www.loom.com/share/bc79a4fadf574d0792f62f0c125aff72?sid=439c995a-d3e3-4dcd-8b6d-f4de99c3da9e

Test and train dataset were loaded to derive insights against the target data

Missing values were dealt with by dropping as they were under 10%

EDA would yield the following insights

1)Nearly half of joint applicant default
whereas as only less than a third of individual applicants pay when due

2)nearly all defaulter are in annual income of under 70k

3)F,G & E grade applicants are most likely to default

4)longer term loan applicants are more likely to default

5)applicants with higher interest rate tend to default

6)credit score of loan applicants was not too effective as they were nearly the same

Balanced data was then used to perform logistic regression against the target data - loan status
that would yield 80% accuracy

Random Forest Method would yield the same
