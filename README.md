# 4th_team_project_ML_with_ANN
## IBM HR Analytics Employee Attrition & Performance

### Problem statement
Hiring and retaining employees are extremely complex tasks that require capital, time and skills.

Small business owners spend 40% of their working hours on tasks that do not generate any income such as hiring.

Companies spend 15-20% of the employee's salary to recruit a new candidate.

An average company loses anywhere between 1-2.5% of their total revenue on the time it takes to bring a new hire up to speed.

Hiring a new employee costs an average of $7645(0-500 corporation).

It takes 52 days on average to fill a position.

Source: https://toggl.com/blog/cost-of-hiring-an-employee

### Objective
Conduct an analysis to identify important factors that might be influential in determining which employee might leave the firm and who may not and develop a model that can predict whether a person quits or stays.

### Role
Worked 21 hours a week as a data scientist within a team of 4 to produce visualizations of employee attrition and develop a model that could predict which employees are more likely to quit.

### Data
The dataset is unbalanced (83.88% vs 16.12%).
We used out of the most popular Python packages in Data Science and ML as NumPy, Pandas, Matplotlib, Feature-engine, SciPy and Scikit-learn to obtain, extract, and clean the data.

### Models and Tools Used
This project was completed using popular Machine Learning algorithms and Artificial Neural Networks.

### Results
1. Results from the analysis found that the decision to quit is influenced by very different factors, both personal factors (age, marital status, gender) and financial factors such as monthly income, salary growth rate, the ability to own shares in the company, also the level of job satisfaction, relationships, environment, working conditions (overtime).
2. We found hyperparameters through a Grid Search CV and specified regularization parameters ('class_weight') for Machine Learning models and also tried to find optimal hyperparameters for ANN through loops. Among all tested models, ANN with three Dense layer and 256 neurons in each layer with batch_size = 1 and SGD optimizer showed the best results: accuracy on train set = 90%, on test set = 87%. 

In next version of this project I'll use other technique of Feature Selection and maybe obtain other results of performance.
