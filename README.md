# Salary Prediction (Python)
Lets predict some salaries based on historical Data

This is a simple project, where we will try to solve a business problem related to HR.
We want to use Machine learning technology and develop a model that predicts the salary when years of work experience , job type, Majors, industry type, degree and miles from metropolis is given.


# Process as per the 4D FrameWork
Define :- Discuss and lay down every aspect of your problem statement and know the challenges to be solved.
Discover :- Performed Basic EDA , Cleaned Data , Outlier Treatment  , Missing values imputation, normalization of the Dataset.
            For Visualization, i have used boxplot, distribution plot, scatter plot, violin plot, residual plot and regression plot to                 visualize the data and it's characteristics
            
Develop  :- Developed a Machine Learning BAseline model, so that we have something to compare our model with and we can go further to                   enhance our existing model. 
            Agorith Used : - Linear Regression, Polynomial Transformation, Ridge Regression and Random Forest
            
            Metrics Used :- Mean Squared Error (MSE) , R-Sqaured Error
            
# Libraries USed

Python 3.7 , Jupyter lab , Numpy , pandas, matplotlib,Scikit-Learn , statsmodel

# Business Problem to solve

This is a simple project, where we will try to solve a business problem related to HR.
We want to use Machine learning technology and develop a model that predicts the salary when years of work experience , job type, Majors, industry type, degree and miles from metropolis is given.
This data talks about different features, attributes which are helpful to understand the relatve salary for a particular Job. Now if we can somehow predict the correct salaries for any given job type, based on some specific and common Attributes, it can be a great help for the HR team in Recruiting new resources.
Hence, as per the tradition machine learning approach, we have the labeled dataset which tells us what salary is most offered for a job, and using that we can build a generalised model which can predict.


The features in this data set are described as below:
Years Experience: Total Years of experience
Job Type: The position held (CEO, CFO, CTO, Vice President, Manager, Janitor, junior and senior)
College Degree: Doctoral, Masters, Bachelors, High School, or None
College Major: Computer Science, Engineering, Literature , Biology, Business, Chemistry, Math, Physics
Industry: Auto, Finance,Education, Health, Oil, Service
Miles From Metropolis: How far is the Person staying from City Center.


# Summary
Applying second order polynomial transformation to the features gave the most accurate prediction with the least error when using a Linear Regression Model. The result was a mean squared error of 354 with the accuracy of 76%.
