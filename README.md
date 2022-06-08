# Credit-Card-Approval-Prediction-Model

### This model will assist the credit card sanctioning companies, in order to decide whether to approve a credit card to a particular customer who has applied for one, or reject the application.

## The factors taken into consideration for deciding the approval of a credit card are:-

i) Occupation Type

ii) Education Type

iii) Housing Type

iv) Income Type

v) Total Income Amount

vi) Employed Years

vii) Age of the person

viii) Family Status

ix) Family Members Count

x) Children's Count

xi) Gender of the person

xii) Person has a Car?

xiii) Person has Realty? 

xiv) E-Mail provided?

xv) Personal Phone provided?

xvi) Work Phone provided?

## The credit records of the past applicants, which the credit car provider has in storage, is also taken into consideration.

### A month-by-month analysis of the due credit has been used in the credit_records.csv file.

## The credit card dues has been divided as per the following criterion:-

i) 'C' : 'Good_Debt' 

ii) 'X' : 'Good_Debt' 

iii) '0' : 'Good_Debt' 

iv) '1' : 'Neutral_Debt'

v) '2' : 'Neutral_Debt' 

vi) '3' : 'Bad_Debt' 

vii) '4' : 'Bad_Debt' 

viii) '5' : 'Bad_Debt'

### For a particular ID, the results for all months is collaborated and a decision is made.

## The criterion for credit card approval, with the help of the 'Good', 'Neutral' or 'Bad' Debt history is:-

### For Approval:-

i) 'Good_Debt' > 'Neutral_Debt'

ii) 'Good_Debt' > 'Bad_Debt'

iii) 'Neutral_Debt' > 'Bad_Debt'

### For Rejection:-

i) 'Neutral_Debt' > 'Good_Debt'

ii) 'Bad_Debt' > 'Good_Debt'

ii) 'Bad_Debt' > 'Neutral_Debt'

### Both the 'application_record' and 'credit_record' .csv files were merged into one 'final_dataset' .csv file.

## 8 SKLearn Models were tested and the results were that:-

### Support Vector Machine, Logistic Regression and Multi-Layer Perceptron Models gave the joint-most accuracy score. (~ 99.5 %)

### Decision Tree Model gave the worst accuracy score. (~ 98.9 %)

<img width="471" alt="Screenshot 2022-06-08 at 11 06 44 AM" src="https://user-images.githubusercontent.com/78081835/172539840-6c4880c5-1487-48f6-a34d-f0d4206ed42e.png">

## Confusion Matrices and Classification Reports are also included for all of the models. 


<img width="441" alt="Screenshot 2022-06-07 at 5 00 21 PM" src="https://user-images.githubusercontent.com/78081835/172369051-501a5003-3e70-47a7-af40-c72f16535413.png">





