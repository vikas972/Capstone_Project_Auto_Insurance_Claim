# Capstone_Project_Auto_Insurance_Claim
Build a Predictive Model using Machine Learning algorithms ,to predict whether an owner will initiate an auto insurance claim in the next year.

# List [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome#readme)
Use Cases
The model shall mainly support the following use cases:
1)	Conquering Market Share: It should be possible to conquer market share by lowering the prices of the premium for the customers, who are least likely to claim.
2)	Risk Management: It should be possible to charge right premium from the customer, who is likely to claim insurance in the coming year
3)	Smooth Processing: It should be possible to reduce the complexity of pricing models, as with majority of transactions happening online and with more customer attributes available (thanks to internet and social media), time is ripe to harness the power of data and build complex ML models
4)	Increased Profits: As per industry estimate 1% reduction in claim can boost profit by 10%. So, through predictive model we can identify and deny the insurance to driver who will make the claim. Thus, ensuring reduced claim out go and increased profit.

Part of the model development is to identify and prioritize above use cases.
Process Flow

The ML model shall mainly consist of two phases: 

1)	EDA (Exploratory Data Analysis): This phase will include analysing datasets to summarize their main characteristics, often with visual methods. A statistical model can be used, but primarily EDA will be used for seeing what the data can tell us beyond the formal modelling or hypothesis testing task. 
➢ Scaling/Normalization – so that entire data is on same scale 
➢ fill the missing values
➢ feature selection & engineering to ensure right input to model 


Following tasks can be performed as a part of EDA:
 

2)	Data Visualization: 

Create different graphs based on the data type of columns and understand the current situation, how is the team performing, understand the current baseline. This will help the stakeholder measure the improvement that we can suggest from our predictive model 
Write down the list of hypotheses that are formed by looking at the data

3)	Machine Learning Modelling: 
After EDA, modelling comes into process. The process of training an ML model involves providing an ML algorithm (that is, the learning algorithm) with training data to learn from. The term “ML model” refers to the model artefact that is created by the training process. 
 
The training data must contain the correct answer, which is known as a target or target attribute. The learning algorithm finds patterns in the training data that maps the input data attributes to the target (the answer that you want to predict), and it outputs an ML model that captures these patterns. 
You will use the ML model to get predictions on new data for which you will not know the target.
Following tasks can be performed as a part of modelling:
➢ Start with basic model but eventually move towards ensemble
➢ Use Deep Learning with sklearn, MLPClassifier and check if neural network model is better than traditional models
➢ Arrival at a model with best f1-score
Deploy the model using Flask

After evaluating all the models, the final model that is accepted by the client needs to be deployed that can we used by our agents to enter the details and predict if the insurance should be issued or not?
That model should also display the various parameters that can help the sales guy take the final call – informed decision based on the prediction.
Dataset Dimension

The project involves the use of a dataset with 600k training data and 57 features/data.
Target Environment
You will use Edureka’s CloudLab, a cloud-based Jupyter Notebook, which is pre-installed with Python packages on the cloud-lab environment to work on this Project. It is offered by Edureka as a part of the course, where you can execute all the demos and work on real-life projects in a fluent manner.
You’ll be accessing the CloudLab via your browser, which requires minimal hardware configuration.
Deliverables

Following are the deliverables (.ipynb files), which needed to be developed with respect to Exploratory Data Analysis:
1.	Write at least 3 important inferences from the data above
2.	Is the data balanced? Meaning are targets 0 and 1 in right proportion?
3.	How many categorical features are there?
4.	How many binary features are there?
5.	Write inferences from data on Interval variables.
6.	Write inferences from data on ordinal variables.
7.	Write inferences from data on binary variables.
8.	Check if the target data is proportionate or not. Hint: Below than 30% for binary data is sign of imbalance
9.	What should be the preferred way in this case to balance the data? 
10.	How many training records are there after achieving balance of 12 %? 
11.	Which are the top two features in terms of missing values? 
12.	In total how many features have missing values? 
13.	What steps should be taken to handle the missing data? 
14.	Which interval variables have strong correlation? 
15.	What's the level of correlation among ordinal features? 
16.	Implement Hot Encoding for categorical features 
17.	In nominal and interval features which features are suitable for Standard Scaler?
18.	Summarize the learnings of ED
19.	A picture is worth a thousand words, explain with different graphs and visualization techniques that you have learnt what is the data telling, 
20.	Draw a mind map to high light the pain that can be identified from the dataset
Following are the deliverables (.ipynb files), which needed to be developed with respect to Modelling:
1. The Simple Logistic Regression Model seem to have high accuracy. Is that what we need at all? What is the problem with this model?
2. Why do you think f1-score is 0.0?
3. What is the precision and recall score for the model?
4. What is the most important inference you can draw from the result?
5. What is the accuracy score and f1-score for the improved Logistic Regression model?
6. Why do you think f1-score has improved?
7. For model Linear SVC play with parameters – dual, max_iter and see if there is any improvement
8. For -- SVC with Imbalance Check & Feature Optimization & only 100K Records is there improvement in scores?
9. XGBoost is one the better classifiers -- but still f1-score is very low. What could be the reason?
10. What is the increase in number of features after onehotencoding of the data?
11. Is there any improvement in scores after encoding?
12. If not missing a positive sample is the priority which model is best so far?
13. If not marking negative sample as positive is top priority, which model is best so far?
14. Do you think using AdaBoost can give any significant improvement over XGBoost?
15. MLPClassifier is the neural network we are trying. But how to choose the right no. of layers and size
16. At what layer size we get the best f1-score?
17. Help the management decide which model to signoff and help the management take informed decision based on the evaluation metrics – explain in brief the pros-cons of the best 3 models
18. Flask website that holds the final predictive model (give some sample examples where the model is able to predict different outputs based on changes input parameter)
19. Can you showcase to the management, what changes in the parameter can help improve the profit, what is the likelihood of profit boost that can be expected after deploying the model


