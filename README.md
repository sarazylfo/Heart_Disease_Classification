# Heart_Disease_Classification

OBJECTIVE: Attempting to predict the liklihood that a person will get Coronary Heart Disease. 

Heart disease is the leading cause of premature death in the UK. However in the last 50 years there have been massive imporvements in the treatment of the condition, with prescriptions of life-saving lipid lowering drugs exploding from 250,000 to 50 million. This means that more people are being diagnosed in a position where their CHD is treatable. 

I am developing an addition to the NHS Coronary Heart Disease website information service. A screening survey where concerned users can enter their vitals and information, and my model will use the information to predict whether they are at risk of coronary heart disease. 
![Image of NHS website]
https://github.com/sarazylfo/Heart_Disease_Classification/blob/master/Img/Screen%20Shot%202020-02-18%20at%2009.56.27.png

I used a K-Nearest Neighbours algorithm in my final model. The variables shown below had the highest correlation with heart disease prevelance.

![Image of variables]
https://github.com/sarazylfo/Heart_Disease_Classification/blob/master/Img/Screen%20Shot%202020-02-18%20at%2010.00.02.png

In this particular use case, it is more important to reduce false negative type II error. In most medical diagnosis cases, it is considered more damaging to conclude that someone does not have an illness when they do. The counter is also traumatic, to diagnose someone with something they do not have, however in terms of cost to life, this is the minimised risk. 
In my particular use case, the survey is not to be consdiered as a replacment of a proper medical exam carried out by a liscensed professional. It only serves the purpose to infrom people visiting the website on whether they should prusue proper exmaination or not therefore the false postive rates will only have the impact of encouraging proper health practises, which in the long run, is a good thing. 

![Image of ROC curve]
https://github.com/sarazylfo/Heart_Disease_Classification/blob/master/Img/Screen%20Shot%202020-02-18%20at%2010.19.27.png

