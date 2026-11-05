# econ3916-lab13-multivariate-ols

Lab 13: Multivariate OLS
Objective
I used a simulated payroll example to see what controlling for another variable actually does to a regression coefficient and I also checked what happens when a bad control is added
Main results
The simple regression gave a training coefficient of about 4.89 even though the true effect was 3

After controlling for experience the coefficient fell to about 3.01 and the Frisch-Waugh-Lovell residual regression gave the same answer

When manager rating was also controlled for the estimate moved away from the truth and fell to about 2.51 so adding more controls was not automatically better

The interaction model showed that the training slope can be different across groups and the challenge also showed positive omitted variable bias when ability was left out of an education and wage regression
Main takeaway
A regression coefficient always depends on what else is in the model and controlling for something means comparing observations after removing the part explained by that control so the choice of controls has to come from the question and how the variables are related
