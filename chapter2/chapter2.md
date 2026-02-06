Conceptual
1. For each of parts(a) through (d), indicate whether we would generally expect the performance of a flexible statistical learning method to be better or worse than an inflexible method. Justify your answer.

a. The sample size, n, is extremely large, and the number of predictors p is small
Ans: With a large sample size and relatively small predictors or independent features, a flexible statistical method would generally improve performance, dependent on whether the dataset is non-linear. With a large dataset, variance is generally reduced while a strong but few predictors eliminate noise, therefore, the performance of a flexible statistical learning method will be better than an inflexible statistical learning method. I'd suggest using tree-based models like boosted trees or random forests for modelling
b. Ans: The number of predictors p is exxtremely large, and the number of observations n is small
Ans: The performance of the statistical learning method is dependent on the quality of the predictors, but generally, a small dataset with extremely large predictors, will result in a worse performance for a flexible statistical learning method as compared to an inflexible slm, since the fslm is very likely to overfit the training data resulting in high variance. The best remedy will be to use regularization or dropouts to managing issues relating to high variance. And if linearity is established, an inflexible slm is the best slm to use
c. The relationship between the predictors and response is highly non-linear
Ans: fslm perform on non-linear datasets compared to inflexible slm because of their ability to learn very complex functions as compared to inflexible slm. If the end goal is prediction, a neural network will be the most appropriate choose else a boosted or random forest would be best
d. The variance of the error tersm, i.e var_squared = Var(epsilon), is extremely high
Ans: If the variance of the error term is extremely large, an inflexible slm would perform better than a fslm because fslm is generally associated with high variance because they model the training set very well, and in the process, learn all the noise associated with the dataset, making it difficult to generalize or perform well on the test set, resulting in overfitting.

2. Explain whether each scenario is a classification or regression problem, and indicate whether we are most interested in inference or prediction. Finally, provide n and p.

a. We collect a set of data on the top 500 firms in the US. For each firm we record profit, number of employees, industry and the CEO salary. We are interested in understanding which factors affect CEO salary.
Ans: This is a regression problem because salary is quantitative in nature. We are also interested in inference between we want to understand the underlying factors which affect CEO salary and not just predict salaries. n = 500 top firms, while p(predictors) = profit, number of employees, industry salary

b. We are considering launching a new product and wish to know whether it will be a success or a failure. We collect data on 20 similar products that were previously launched. For each product, we have recorded whether it was a success or failure, price charged for the product, marketing bufget, competition price, and ten other variables.
Ans: This is a classification problem, a binary classification problem to be precise because we only have two possible outcomes, whether the product will be a success or failure. It is also a prediction problem, because we are interested in predicting success or failure, not understand casual relationships. n = 20, p = price, marketing budget, competition price, ten other variables.

c. We are interested in predicting the % change in the USD/Euro exchange rate in relation to the weekly changes in the world stock markets. Hence we collect weekly data for all of 2012. For each week we record the % change in the US/Euro, the % change in the US market, the % change in the British market, and the % change in the German market
Ans: This is a regression problem because the % change in the USD/Euro exchange is generally quantitative in nature. This is prediction based assignment also because our area of interest is predicting the % change and not inferring about what affects or informs the percentage change. n = 52, p = % change in the US market, the % change in the British market and the % change in the German market

3. You will now think of some real-life applications for statistical learning.
a. Describe three real-life applications in which classification or regression might be useful. Describe the response, as well as the predictions. Is the goal of each application inference or prediction? Explain your answer.
Ans: 1. Productivity Analyzer: 
    - Classification: Determine whether your day was productive or unproductive
    - Inference: understand the drivers of productivity
    - Predictors: Social media time, Hours of sleep, Extra curricular activities, Workout time, Quiet time
    The productivity analyzer is a classification problem that seeks to identify whether a an individual's day is productive or not, but the goal of the project, is geared towards understanding how predictors such as hours of sleep and social media time influence productivity.

    2. Data jobs salary analyzer:
    - Regression: Determine the salary of data professionals
    - Inference: understand the drivers of salary for data professionals
    - Predictors: years of experience, educational background, size of company, age, gender, title

    3. Student final grade predictor:
    - Regression: Determine the final CGPA of tetiary students
    - Prediction: predict the final CGPA of students 
    - Predictors: study time, social media time, hours of sleep, previous GPA
    