Dataset columns

    age: the person's age (years)
    sex: the person's sex
        0 = female
        1 = male
    cp: chest pain type
        0 = asymptomatic
        1 = atypical angina
        2 = non-anginal pain
        3 = typical angina
    trestbps: the person's resting blood pressure (mmHg on admission to the hospital)
    chol: the person's cholesterol measurement (mg/dl)
    fbs: the person's fasting blood sugar (>120 mg/dl)
        0 = false
        1 = true
    restecg: resting electrocardiographic results
        0 = showing probable or definite left ventricular hypertrophy by Estes' criteria
        1 = normal
        2 = having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of >0.05 mV)
    thalach: the person's maximum heart rate achieved
    exang: exercise induced angina
        0 = no
        1 = yes
    oldpeak: ST depression induced by exercise relative to rest (ST relates to positions on the ECG plot)
    slope: the slope of the peak exercise ST segment
        0 = downsloping
        1 = flat
        2 = upsloping
    ca: the number of major vessels (0-3)
    thal: a blood disorder called thalassemia
        0 = NULL (dropped from the dataset previously)
        1 = fixed defect (no blood flow in some part of the heart)
        2 = normal blood flow
        3 = reversible defect (a blood flow is observed but it is not normal)
    target: heart disease
        0 = yes
        1 = no
