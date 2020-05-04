Due to the spread of COVID 19, we are investigating existing interpretable AI tools and algorithms to quickly determine whether a person is a potential COVID- 19 patient or not. 

Firstly, We reproduce the existing implementation of a neural network (https://github.com/aildnont/covid-cxr) which can predict the possibility of a person having COVID-19 or not. It uses Local Interpretable Model-Agnostic Explanations (i.e. LIME to explain the reason by giving potential COVID-19 features in chest X-ray pictures. 

Secondly, we summarize another algorithm called SHAP (https://github.com/slundberg/shap) which is a unified approach to interpret model predictions. 

Finally we try to integrate SHAP implementation into and explain the reason why it currently has some integration problems.

The report and results for the above steps is at [here](https://github.com/HaoranZhuExplorer/Report-on-COVID19-X-Ray-Classification/blob/master/report.pdf). Since this project is mainly focusing on reproducing [covid-cxr](https://github.com/aildnont/covid-cxr) and [SHAP](https://github.com/slundberg/shap) and writing an investigation report, we don't change the source code in the above projects, so we don't provide the cloned code at this project. 
