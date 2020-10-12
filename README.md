# test
To include a categorical variable in a regression model, the variable has to be encoded 
  as a binary variable (dummy variable). In Pandas, we can easily convert a categorical 
  variable into a dummy variable 
**age** - age in years*
sex - (1 = male; 0 = female)
cp - chest pain type

    value1: typical angina
    value2: atypical angina
    value3: non-anginal pain
    value4: asymptomatic

trestbps - resting blood pressure (in mm Hg on admission to the hospital)
chol - serum cholesterol in mg/dl
fbs - (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
restecg - resting electrocardiographic results

    value0: normal
    value1: having ST-T wave abnormality(T wave inversions and/or ST elevation and depression of >005 mV)
    value2: showing probable or definite left ventricular hypertrophy by Estes criteria.

thalach - maximum heart rate achieved in beats per minutes(bpm)
exang - exercise induced angina (1 = yes; 0 = no)
oldpeak - ST depression induced by exercise relative to rest
slope - the slope of the peak exercise ST segment
diagnosis - have disease or not (1 = yes, 0 = no)
