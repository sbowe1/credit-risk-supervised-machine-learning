# Predicting Credit Risk

[Data](Resources/lending_data.csv) from lending services companies, including loan size, interest rate, borrower income, and loan status, was fitted with both Logistic Regression and Random Forest Classifier models. 

Both models ultimately provide a way to classify what group an observation belongs to. Logistic Regression generates a curve that separates two different classes - in this case loan approval and disapproval. The Random Forest Classifier is an algorithim that utilizes multiple decision trees to predict the class of an observation based on which class receives the most "votes."

### Predictions
I predicted that the Random Forest Classifier model will perform better because Logistic Regression is an adaptation of Linear Regression (a single variable), while Random Forest can account for multiple variables (multicollinearity). The dataset includes multiple variables that may contribute to the outcome, so the Random Forest Classifier seemed like it would be a better fit.

### Analysis
Both models performed equally well, as seen by their >99% training accuracy scores. Although the Random Forest Classifier has a slightly higher training accuracy score (99.74% vs 99.20%), it has a slightly lower testing accuracy score (99.09% vs 99.22%). Although initially surprising, these similar percentages seem to hint that only 1 of the available variables strongly contributes to the approval or disapproval of a loan.