

This is an investigation report for dealing with covid-19 x ray images classification problem. 


Due to the spread of COVID 19, we are investigating existing interpretable AI tools and algorithms to quickly determine whether a person is a potential COVID- 19 patient or not. 

Firstly, We reproduce the existing implementation of a neural network (https://github.com/slundberg/shap) which can predict the possibility of a person having COVID-19 or not. It uses Local Interpretable Model-Agnostic Explanations (i.e. LIME to explain the reason by giving potential COVID-19 features in chest X-ray pictures. 

Secondly, we summarize another algorithm called SHAP (https://github.com/slundberg/shap) which is a unified approach to interpret model predictions. 

Finally we try to integrate SHAP implementation into and explain the reason why it currently has some integration problems.