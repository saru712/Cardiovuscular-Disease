## Cardiovuscular-Disease Prediction 

According to World Health Organisation,

CVDs are the number 1 cause of death globally i.e More people die annually from CVDs than from any other cause. An estimated 17.9 million people died from CVDs in 2016, representing 31% of all global deaths. Of these deaths, 85% are due to heart attack and stroke

From the above facts and figures, we can easily conclude that Cardiovascular disease (CVD) accounts for the majority of death and hospitalization, health care expenditures and loss of productivity in developed country

<img src = '/Medical.jpg'>

### Data Columns:
- age :age of a person in Days
- gender :gender of the person
- height :height of the person in cm
- weight :weight of the person in kg
- ap_hi :Systolic blood pressure i.e. Pressure exerted when Blood is ejected in arteries. Normal value : 120mmhg or Below
- ap_low :Diastolic blood pressure i.e. Pressure exerted when Blood exerts between arteries and heartbeats. Normal Value : 80mmhg or Below
- cholesterol :Cholestreol value (Cholesterol is a type of fat found in your blood) of your blood
- gluc :Glucose Level. They're less than 100 mg/dL after not eating (fasting) for at least 8 hours. 
- smoke :Binary Values stating whether Person is a Smoker or not i.e. {0 : 'Not a Smoker', 1 : 'Smoker'}
- alco :Binary Values stating whether Person is an alchoalic or not i.e. {0 : 'Not a Alchoalic', 1 : 'Alchoalic'}
- active :Binary Values stating whether Person is involved in physical activites or not i.e. {0 : 'Not involved in Physical Activites', 1 : 'involved in physical activites'}
- cardio :Binary Values stating whether Person has Cardiovascular diseases (CVDs) or Not i.e. {0 : 'Not Have CVD', 1 : 'Have CVD'}

## Work:
- Need to predict if a person has Cardiovuscular Disease or not.

## SuperVised Learning:
- Used AdaBoost Classifier with Hyperparameter Tuning to obtain 75% accuracy

## Deployment:
 -Created the Web Application.
- Used Heroku platform for deployment [Prediction of Cardiovuscular-Disease](http://cardiodiseasepredict.herokuapp.com/).


