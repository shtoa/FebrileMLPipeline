# FebrileMLPipeline
Febrile patient classification (EBT) and oral temperature prediction.

--- 

The following notebook explores the regression task of predicting the oral temperature in fast mode *aveOralF* and the temperature measured in monitor mode *aveOralM* by an Infrared Thermograph, using the dataset, Infrared Thermography Temperature Dataset from UC Irivine Machine Learning Repository (Wang et. Al, 2022). Monitor mode offers more precise readings and was used as the target in the paper by Wang et. Al, 2022, however this notebook will additionally engage in predicting the reading in fast mode as an additional exercise.  

Secondly, further models will be developed in a classification task to predict if the patient is ferbile or not. This will be defined by exceeding the threshold temperature of $>37.5 \text{°C}$ based on the reference oral temperature *aveOralF* and *aveOralM*. 
