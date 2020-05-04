Due to the spread of COVID 19, we are investigating existing interpretable AI tools and algorithms to quickly determine whether a person is a potential COVID- 19 patient or not. 

Firstly, We reproduce the existing implementation of a neural network(1) which can predict the possibility of a person having COVID-19 or not. It uses Local Interpretable Model-Agnostic Explanations (i.e. LIME(5)) to explain the reason by giving potential COVID-19 features in chest X-ray pictures. 

Secondly, we summarize another algorithm called SHAP(4) which is a unified approach to interpret model predictions. 

Finally we try to integrate SHAP imple- mentation into (1) and explain the reason why it currently has some integration problems.