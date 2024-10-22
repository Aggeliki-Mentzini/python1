# python1
Learning from https://www.udemy.com/course/master-data-science-in-python/learn/lecture/29367640?start=75#overview and https://developers.google.com/machine-learning/intro-to-ml/what-is-ml 


![image](https://github.com/user-attachments/assets/623e4b9f-743b-4515-979f-6a3bad556731)


![image](https://github.com/user-attachments/assets/5f126332-594b-4513-b0f1-9e851c4d10da)



Learning objectives:
- Understand the different types of machine learning.
- Understand the key concepts of supervised machine learning.
- Learn how solving problems with ML is different from traditional approaches.

Machine learning (ML) powers some of the most important technologies we use, from translation apps to autonomous vehicles. This course explains the core concepts behind ML.

ML offers a new way to solve problems, answer complex questions, and create new content. ML can predict the weather, estimate travel times, recommend songs, auto-complete sentences, summarize articles, and generate never-seen-before images.

In basic terms, ML is the process of training a piece of software, called a model, to make useful predictions or generate content from data.

For example, suppose we wanted to create an app to predict rainfall. We could use either a traditional approach or an ML approach. Using a traditional approach, we'd create a physics-based representation of the Earth's atmosphere and surface, computing massive amounts of fluid dynamics equations. This is incredibly difficult.

Using an ML approach, we would give an ML model enormous amounts of weather data until the ML model eventually learned the mathematical relationship between weather patterns that produce differing amounts of rain. We would then give the model the current weather data, and it would predict the amount of rain.

Types of ML Systems
ML systems fall into one or more of the following categories based on how they learn to make predictions or generate content:

Supervised learning
Unsupervised learning
Reinforcement learning
Generative AI
Supervised learning
Supervised learning models can make predictions after seeing lots of data with the correct answers and then discovering the connections between the elements in the data that produce the correct answers. This is like a student learning new material by studying old exams that contain both questions and answers. Once the student has trained on enough old exams, the student is well prepared to take a new exam. These ML systems are "supervised" in the sense that a human gives the ML system data with the known correct results.

Two of the most common use cases for supervised learning are regression and classification.

Regression
A regression model predicts a numeric value. For example, a weather model that predicts the amount of rain, in inches or millimeters, is a regression model.

See the table below for more examples of regression models:

Scenario	Possible input data	Numeric prediction
Future house price	Square footage, zip code, number of bedrooms and bathrooms, lot size, mortgage interest rate, property tax rate, construction costs, and number of homes for sale in the area.	The price of the home.
Future ride time	Historical traffic conditions (gathered from smartphones, traffic sensors, ride-hailing and other navigation applications), distance from destination, and weather conditions.	The time in minutes and seconds to arrive at a destination.
Classification
Classification models predict the likelihood that something belongs to a category. Unlike regression models, whose output is a number, classification models output a value that states whether or not something belongs to a particular category. For example, classification models are used to predict if an email is spam or if a photo contains a cat.

Classification models are divided into two groups: binary classification and multiclass classification. Binary classification models output a value from a class that contains only two values, for example, a model that outputs either rain or no rain. Multiclass classification models output a value from a class that contains more than two values, for example, a model that can output either rain, hail, snow, or sleet.


Learning objectives:
- Explain a loss function and how it works.
- Define and describe how gradient descent finds the optimal model parameters.
- Describe how to tune hyperparameters to efficiently train a linear model.
