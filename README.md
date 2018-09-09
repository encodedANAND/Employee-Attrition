# Employee-Attrition



We are going to find major causes of attrition in employees. Attrition results in lack of productivity which reults in lack of profit ,which ultimately leads to unemployment. It seems simple to point out few factors behind attrition such as low wages, working environment,relationship with boss etc, but actually there are a lot more from one's personal reason to his education. And this is where Statistics come in. This field of concern is so wide thatit has given birth to new ML research called "Interpretability".


We have implemented Logistic Regression to our data and getting a response of about 87.3% with about 85% precision rate. The model shows enough of sensitivity but a lack of specificity.

To compensate for this, we chose RFE for taking only the relevant features and leaving out the rest.WeWe have applied logistic model to the data getting an accuracy of 87.30%. As it is clear from our model that we are getting low value of recall for true value of attrition ,i.e., we are not getting enough of the relevant information from the data. The retrieved model shows high senstivity but low specifity see a slight increase in accuracy of our model. We have trimmed our dataset to 40 features. Though we are reporting a decrease in precision of attried employees, we are getting a noticeable increase in recall and F-score.This ultimately results in increase of specificity of our model.This model also reduces our memory space and processing time as the operations to be performed are much less than former.
