# Data Science Reflective Task

**Author - Rashrav Shrestha**
 

I was fascinated by Jupyter Notebook's features from the moment I was introduced to it. I loved the simplicity of programming in the browser. It used Python as the programming language, a language that was unfamiliar to me at first. The notebook consisted of a mix of code, visualization, and text all put together in a single web page which created an interactive and presentable learning experience. Jupyter notebook also provided a rich set of interactive computing and visualization tools which allowed me to show my whole thought process and tell a story when working on the portfolio tasks. In comparison to other IDE like PyCharm, Notebook seems to excel at producing visually appealing pieces of code, visualization, and text explanation. Furthermore, Notebook files are easily reproducible and can be shared easily. I also noticed that Jupyter notebook was also ideal for running machine learning projects as we frequently need to inspect the data and it is comparatively difficult in environments like Visual Studio code and the Terminal. The Jupyter notebook makes it quite easy to inspect the data.

In the starting weeks of this unit, I got introduced to various libraries of Python like NumPy(provided multi-dimensional arrays), Pandas(Data frames), Matplotlib(Graphs and Plot), and Scikit-learn (Machine learning library). I was also introduced to basic Data Science Workflow which involved the CRISP-DM methodology. It was the standard procedure followed by data mining experts which included the process of Data understanding, Data Preparation, Modeling, Evaluation, and Deployment. Getting familiar with this methodology was essential to kickstart my journey into data science. For all the portfolio tasks, this methodology workflow process was implemented. On the other note, Machine learning is all over the place nowadays in terms of the media and so forth but I wasn't able to wrap my head around the topic at all until I took this unit. The unit helped get a feel of how machine learning models were trained and evaluated. I was introduced to simple supervised machine learning models like Linear regression to more advanced models like Decision trees and K-nearest neighbors. I was also introduced to various unsupervised learning models such as k-means clustering. I could see myself using these in various real-life problems. We can implement it in speech recognition by training the model using voice samples from various participants and finally test the results using new samples and evaluate how it performed. The more samples used to train the model, the better the outcome would be. Another instance where I can think of using this is to divide customer segments into groups using unsupervised learning by using clustering algorithms. They may help me find different market segments hidden within data and will help us make marketing decisions based on the results.

I decided to choose the Titanic dataset because the dataset had a lot of irrelevant, missing values and required some sort of data exploration and preparation before moving on to the modeling and evaluation part.  I wanted to include all steps of the data science workflow process which involved the process of Data Exploration, Preparation, Modeling, and Evaluation. Upon completing the data preprocessing part, various machine learning models were trained and their performances were evaluated. The size of the dataset was also appropriate as it wasn't too big or too small. This leads me to choose this as my dataset for Portfolio 4.

The aim of Portfolio 4 was to predict the survivability of the passengers. Binary classification algorithms were used as we were needed to predict if the passenger survived or not.  I was only allowed to choose supervised machine learning models as the unsupervised learning models weren't suitable to use in this scenario. I first started with a Simple Logistic Regression as a baseline model because it had the lowest complexity. Then, I proceeded with various other classification algorithms that were introduced in the lecture which included Gaussian Naïve Bayes, K-Nearest Neighbor, Decision tree Classifier, and Random Forest. I incorporated them into a function and fitted them using a training set of 80% and a testing set of 20% following the rule of thumb. Choosing the optimal value in K-Nearest Neighbor Classifier was a process of trial and error, same with choosing the n_estimator for the Random Forest classifier.

Most of the results were consistent with my intuitive expectation as I expected higher accuracy from the advanced model than the baseline model. That was true for some models such as Random Forest Classifier and K-Nearest Neighbors as they had the highest accuracy score, but the accuracy score of Gaussian NB and Decision Tree was lower than that of the Logistic Regression Model. Decision Tree seems to be the least accurate model for Testing Data But it had the highest accuracy on the training data. Upon researching, I found out that decision trees work well with the data used to train them, but they aren't flexible when it comes to classifying new samples. On the other hand, The Random Forest Classifier seemed to have performed better because it is an extension of the decision tree as it consists of several decision trees on various subsets and uses the average to improve predictive accuracy. That is exactly what the Random Forest Classifier did in our model. The K-Nearest Neighbor initially had a lower accuracy score than the Logistic Regression model when the K-value was different. However, upon finding the optimal k-value through the process of trial and error, the accuracy score increased. 

In conclusion, the portfolio tasks allowed me to implement these machine learning models on real-world datasets. Upon completing these tasks, I am able to implement data science methods which are most appropriate for real-world datasets, train the model and interpret the final results. 


**Word Count: 955**