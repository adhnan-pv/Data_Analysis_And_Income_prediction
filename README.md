This is a project of income prediction on the basis of different Features 
This project contain  Data analysis and income prediction which have 
- EDA
- Machine Learning
- PowerBI dashboard

this porject contain 5 files which are
- Dataset - which is incomeData.csv.xls
- jupyter notebook files - which is income prediction.ipynb
- cleaned Dataset - which is final_income_prediction.csv
- powerBI file - which is BI_income_prediction_Analysis.pbix
- The screenshot of the PowerBi dashboard - which is Income_prediction_dashboard_screenshot.png

The Dataset contains the detail such as

1. age: continuous. It denotes the age of the person.
2. workclass: It denotes the working class of the 
   person. Sample values: Private, Self-emp-not-inc, 
   Self-emp-inc, Federal-gov, Local-gov, State-gov, 
   Without-pay, Never-worked.
3. fnlwgt: continuous.
4. education: It denotes the educational qualification 
   of the person. Sample values: Bachelors, Somecollege, 11th, HS-grad, Prof-school, Assoc-acdm, 
   Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 
   10th, Doctorate, 5th-6th, Preschool.
5. education-num: continuous. It denotes the 
   quantitative values with reference to education. 
6. marital-status: It denotes the marital status of 
   the person. Sample values: Married-civ-spouse, 
   Divorced, Never-married, Separated, Widowed, 
   Married-spouse-absent, Married-AF-spouse.
7. occupation: It denotes the occupation of a person. 
   Sample values: Tech-support, Craft-repair, Otherservice, Sales, Exec-managerial, Prof-specialty, 
   Handlers-cleaners, Machine-op-inspct, Adm-clerical, 
   Farming-fishing, Transport-moving, Priv-house-serv, 
   Protective-serv, Armed-Forces.
8. relationship: It denotes the people present in the 
   family. Sample values: Wife, Own-child, Husband, 
   Not-in-family, Other-relative, Unmarried.
9. race: It denotes the person’s origins. Sample 
   values: White, Asian-Pac-Islander, Amer-IndianEskimo, Other, Black.
10. sex: It denotes the person's gender. Sample 
    values: Female, Male. 
11. capital-gain: continuous. It denotes the monitory 
    gains by the person.
12. capital-loss: continuous. It denotes the monitory 
    loss by the person.
13. hours-per-week: continuous. It denotes the number 
    of working hours per week by the person.
14. native-country: It denotes the country to which 
    the person belongs. Sample values: United-States, 
    Cambodia, England, Puerto-Rico, Canada, Germany, 
    Outlying-US(Guam-USVI-etc), India, Japan, Greece, 
    South, China, Cuba, Iran, Honduras, Philippines, 
    Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, 
    Ireland, France, Dominican-Republic, Laos, Ecuador, 
    Taiwan, Haiti, Columbia, Hungary, Guatemala, 
    Nicaragua, Scotland, Thailand, Yugoslavia, ElSalvador, Trinadad&Tobago, Peru, Hong, HolandNetherlands


The next step in the project is EDA 
- in thiss we use libraries like
  * pandas
  * numpy
  * matplotlib
  * seaborn
 
    
This dataset was not cleaned
- The  age column was named NAN so it was renamed to age
- there was some special character in the columns like "?" it was replaced by NAN
- and then the NAN was replaced by FFILL



The next step was visualisation 
different type of visuals are used in this EDA like 
- Pie chart
- Bar chart
- Heat Map
- Box Plot
- Boxen Plot
- Histogram
- Scatter plot


After completing the Visualisation the next step was Building a model for that the first step was 

- Encoding the dataset the entire dataset was encoded
- After completing the encoding the next step was SMOTE the dataset using SMOTE
- After SMOTE the data the next step was spliting the dataset
- the data was split into X_train,X_test,Y_train,Y_test using train_test_split
- this step was done to train and test the data
- the next step was creating the model using Logical regression
- after creating the model we train the data with x_train and y_train data
- and predict the data by x_test

  the next  step was checking the accuracy of the model by using the Y_test data
  checked the
- accuracy score
- confusion_matrix
- f1_score
- precision_score
- recall_score

after completing the creation of the model the next step was creating the dashboard 

Dashboard was created in the powerBi 
Dax was used to measure count of the each features 
different plot were created in the Dashboard Which are 
- Donut Chart
- Slicer
- Bar Chart
- Card
- Funnel
- Stacked Bar Chart


This is the overall outline of the Project 






  

