This Repo is my solution to the Kaggle Titanic Competition.

The link to the competition can be found here: https://www.kaggle.com/c/titanic#description

My solution involves doing some basic exploratory data analysis and creating a base model first.
The base model is a bad model as it predicts that nobody survived the Titanic! 
However, it does give a starting point to build my model up and compare the accuracy of my output.

I then built another naive model predicting that all females survived, as the data showed that females were more likely to survive.

After building these base models, I went ahead with some basic data anlysis which led me to use a few features as the predictors or survival.
This improved my accuracy to about 72%.

After this I incorporated some feature engineering- by cleaning and extracting information from the existing features to create new meaningful features.
These were then clubbed with the previous features and used to make a new prediction model.
This resulted in an accuracy of 78%. (Note that noth the decision tree model and the linear support vector machine model resulted in the same accuracy on the test set)

Further feature engineering and data analysis can reult in better results.