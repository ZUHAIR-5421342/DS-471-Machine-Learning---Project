# DS-471-Machine-Learning---Project
Supervised, unsupervised, or semi-supervised
Q: Define the type of machine learning problem you're dealing with (supervised, unsupervised, or semi-supervised). Why?

We are dealing with a supervised learning problem since we are training our model on already labeled dataset.
Q: What are the input features, and what is the target variable? Explain their significance in the healthcare context.

Input Features:

age: age of patient in years

Significance: Age is a critical risk factor for many diseases, including heart disease. As people age, the risk of cardiovascular problems such as atherosclerosis and hypertension increases.

sex: gender of patient

1: Male
0: Female
Significance: Gender differences play a role in the prevalence and manifestation of heart disease. For instance, men are generally at higher risk for heart disease at a younger age, while women's risk increases after menopause.

cp: chest pain type

1: typical angina
2: atypical angina
3: non-anginal pain
4: asymptomatic
Significance: Chest pain is one of the main symptoms of heart disease. The different types of chest pain (typical angina, atypical angina, non-anginal pain, asymptomatic) help clinicians determine whether chest pain is likely cardiac-related. For instance, typical angina often suggests coronary artery disease.

trestbps: resting blood pressure (in mm Hg on admission to the hospital)

Significance: High resting blood pressure (hypertension) is a major risk factor for heart disease. Persistent high blood pressure can lead to damage of the arteries, heart attack, and stroke.

chol: serum cholestoral in mg/dl

Significance: High levels of cholesterol can lead to the buildup of plaques in arteries, increasing the risk of coronary artery disease and heart attack.

fbs: fasting blood sugar (> 120 mg/dl)

1: true
0: false
Significance: Fasting blood sugar is used to assess if a patient has diabetes or is pre-diabetic. Diabetes significantly raises the risk of heart disease as it can damage blood vessels and the heart.

restecg: resting electrocardiographic results

0: normal
1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
2: showing probable or definite left ventricular hypertrophy by Estes' criteria
Significance: Electrocardiograms (ECG) are used to detect abnormalities in the heart's electrical activity. ST-T wave abnormalities or evidence of left ventricular hypertrophy can indicate underlying heart problems, such as ischemia or hypertrophy due to high blood pressure.

thalach: maximum heart rate achieved

Significance: The maximum heart rate achieved during physical activity can be an indicator of the heart's ability to handle stress. A lower-than-expected heart rate might suggest heart problems such as ischemia.

exang: exercise induced angina

1: yes
0: no
Significance: Exercise-induced angina (chest pain during exercise) often signals coronary artery disease, as it indicates that the heart isn't getting enough blood during periods of exertion.

oldpeak: ST depression induced by exercise relative to rest

Significance: ST depression during exercise suggests a lack of blood flow to the heart (ischemia). This is often seen in patients with coronary artery disease.

slop: the slope of the peak exercise ST segment

1: upsloping
2: flat
3: downsloping
Significance: The slope of the ST segment during exercise provides insights into heart health. Upsloping is usually normal, while flat or downsloping segments can indicate ischemia and an increased risk of coronary artery disease.

ca: number of major vessels (0-3) colored by fluoroscopy

Significance: Fluoroscopy is used to visualize the blood vessels. A higher number of major vessels with blockages detected via fluoroscopy indicates more severe coronary artery disease.

thal:

3: normal
6: fixed defect
7: reversable defect
Significance: Thalassemia is a blood disorder that affects the oxygen-carrying capacity of red blood cells. A fixed defect means the damage to the heart muscle is permanent, while a reversible defect suggests ischemia that might improve with treatment.

Target Variable:

num: diagnosis of heart disease (angiographic disease status)
0: Normal coronary arteries
1: Non-obstructive CAD or significant stenosis in non-significant (<2mm) side branches or slow coronary flow with normal coronary arteries or non-obstructive CAD.
2: Significant (>=2mm) side branch disease or 1 main-vessel disease at any level. except for ostial or proximal LAD lesion.
3: Significant stenosis in 2 main coronary arteries or significant ostial or proximal LAD lesion alone.
4: Obstructive 3-vessel disease or significant left main coronary artery lesion.
Significance: This is the target variable we're trying to predict. It represents the extent of narrowing in the coronary arteries
