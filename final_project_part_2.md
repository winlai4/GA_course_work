# Project Design Writeup and Approval Template

Follow this as a guide to completing the project design writeup. The questions for each section are merely there to suggest what the baseline should cover; be sure to use detail as it will make the project much easier to approach as the class moves on.

### Project Problem and Hypothesis

The objective of this project is to use data to build a model that can be used to predict the 'Repsonse' variable in the data set in order to classify potential customer insurance risk.For this problam we are trying to predict a categorical or binary value i.e the 'Reponse' of the customer purchasing an insurance product based on over a hundred variables describing attributes of life insurance applicants. 

Im hoping to fit different models (logistic, KNN, random forest) to the data set to see which model best describes our data and the best at predicting and categorising insurance risk.

If successful, the model can help insurance companies identify the most important attributes of life insurance applicants and help and calssify and predict, based on the an applicants response, what type of insurance customer they are and whether they are a good or bad insurance risk. By developing a predictive model that accurately classifies risk this can help insurance companies make decisions much faster and more accurately which would improve customer experience.

Im also hoping to fit different models (logistic, KNN, random forest) to the data set to see which model best describes our data and the best at predicting and categorising insurance risk.

I think attributes relating to health, age and medical history are likely to have the biggest impact.


### Datasets
The data set is made of hundreds of variables that describe a customer's attributes for life insurance policy. Some fo the variables are a coninuous number (age, height, weight) while others appear to be binary values (product information, medical history). While the 'Response' variable that we are trying to predict is a binary or categorical varible ranging from 1 to 8.    


### Domain knowledge
My domain knowledge in this field is very limited. But a quick Google search have shown that insurance companies have been adopting Machine Learning to classify customer's purchasing incurance products. Machine learning algorithms are currenlty being applied to interpret driver data in an effort to monitor market trends, identify business opportunities and classify insuracce risk of potential insurance applicants.

A lot of insurance companies are already applying something similar which allows cusomter's to purchase or get a quote for insurance by answering a set of questions online.  



### Project Concerns

My biggest concern is not being confident in deciding whether this is a predictive exercise (i.e applying a regression model such as logistic regression) or whether this is a classification exercise (apply a classifier such as KNN) or both.

The model is based on actual customer reponses from Prudential Insurance. The model should be representative of a typical insurance customer. Ideally i would like to have more knowledge of the industry and a industry benchmark model that I can compare the accuracy of my model against. It would also be good if i can build more knowledge of the industry so that i can apply standard industry metrics to measure my performance.

If the model is incorrect then we may end up incorrectly classifying potential customer's which can affect the companies bottom line. For example we may predict that a cusomter is a good insurance risk when they are not or we may incorrectly recommend insurance products to customer's which would affect potential sales and impact overall customer experience.



### Outcomes

My aim is two-folds - feature slection and identifying/comparing machine learning algorithms (logistic regression, random forest etc.) that can be used to classify insurance customer's and predict customer's 'Reponse' to insurance policy application. If we can predict a customer's "Reponse" using certain attributes we can also help classify cusotmer insurance risk which can help insurance companies provide quotes on insurance policies much quicker and more accurately. This would save time and minimise revenue risk. We can also cross-sell and recommend other insurance products to potential customers. Ideally i would like to extract the key features in the data set that drives my model so the model can be built using only a few key variables and that way we can use this insight to understand the key features in  insurance risk calssification.

My target audience will also expect to be informed of what are the key variables that can be used to classify insurance applicants and to have a model which can be generalised for the wider customer base. 

I'm hoping to provide a simple but effective model which can be easily interpreted and reproduced so that non-technical people are able to understand how the model classifies and predicts insurance customers. If i can successfully apply feature selection of my data set, produce a simple model to explain the data and make predictions then i will consider this to be a success. 

If im unable to produce a robust model with the data set i have then i will need to find alternative data or redesign my project so that the data can be used to answer an alternative business problem - for example, maybe the data can be used to build a clustering algorithm for customer segmentation targeted product promotion instead.




