# Job-Hiring-Based-on-Personality-Education-Experience-and-Age
Supervised Learning: Decision Tree Classifier on topic Job Hiring Based on Personality, Education, Experience and Age

## Introduction
Employers are continually seeking for methods to streamline their hiring procedures and find the best applicants for their organisations in today's fast-paced and ever-changing employment market. Our AI model makes use of the most recent developments in machine learning and natural language processing to analyse a candidate's personality traits, educational history, professional experience, and age and offer insightful information about their fit for a given post.
Employers may analyse a big pool of candidates fast and correctly using our AI model, and then decide who to invite for interviews or offer employment openings based on data. As the AI model employs objective criteria to evaluate each candidate, this not only saves time and money but also assures that the recruiting process is fair and impartial.
Our AI model, which was trained to find patterns and correlations between many elements that affect work performance, is based on a vast dataset of information about jobs. Our AI model can give you useful insights to help you reach your objectives, whether you're an employer trying to recruit the top applicants or a job seeker looking to find the ideal employment match.

## How to Deploy Model
To deploy the Decision Tree Classifier model for job hiring based on personality, education, experience, and age, you will need to prepare the environment, load the dataset, split the data, train the model, test the model, save the model, and deploy the model in a way that suits your requirements.
1.	Prepare Environment – For our model, we use Google Collab as IDE.
2.	Load the datasets – Import the necessary libraries and load the datasets that have been downloaded and read it using pd.read_excel(file_path).
3.	Split the data – Split the dataset into training and testing data using the train_test_split() function from the scikit-learn library.
4.	Train the model – Create an instance of the DecisionTreeClassifier class from the scikit-learn library and fit the training data to the model using the fit() function.
5.	Test the model – Test the trained model on the testing data using the predict() function and evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score.
6.	Save the model and Deploy the model.

## Used Dataset
Our model used dataset from Mendeley Data named the data of HEXACO personality traits and job search outcomes that you can find it in https://data.mendeley.com/datasets/p9hwfmfcz5/3 .
We also do data preparation in changing gender variable 1 to male while 2 to female. There is attribute gender, married, age, qualification, experience, honesty1-10, emotion1-8, Extravert 1-9, Agreeable1-8, Conscientiuos1-8, Openness1-8, Clarity1-4, Size1-4, Strenght1-3, Comfort1-6, Proactive1-9, Behaviour1-7, Interview1-2, Offer1-2.
For honesty1-10, emotion1-8, Extravert 1-9, Agreeable1-8, Conscientiuos1-8, Openness1-8, Clarity1-4, Size1-4, Strenght1-3, Comfort1-6, Proactive1-9, Behaviour1-7, Interview1-2, Offer1-2, we do calculation by calculate their average which mean.

## Tools
Google collab as our IDE in running model.

## Programming Language
Python.
Why we use Python than others?. 
First off, Python is a very flexible language with a vast selection of modules and frameworks made expressly for AI and machine learning development. For instance, widely used frameworks like TensorFlow, PyTorch, and Keras make it simple to create and train sophisticated neural networks, while libraries like NumPy, Pandas, and SciPy offer strong data processing and manipulation capabilities.
Additionally, Python has robust support for data science and visualisation, both of which are essential for creating powerful AI models. With the use of libraries like Matplotlib and Seaborn, developers can quickly produce visualisations that aid in the comprehension and analysis of data as well as the dissemination of insights to stakeholders.
In conclusion, Python is a well-liked option for building AI models because of its adaptability, simplicity, strong community support, and potent data science and visualisation skills.


## Conclusion
In conclusion, employers trying to find the best applicants for their companies can benefit from using an AI model for recruiting jobs based on personality, education, experience, and age. This AI model can rapidly and correctly assess a huge pool of candidates and make data-driven judgements about who to invite for interviews or offer employment openings by utilising the most recent developments in machine learning and natural language processing.
Additionally, the AI model makes sure that the recruiting procedure is impartial and fair by evaluating each candidate according to objective standards. This ensures that candidates are only assessed based on their qualifications and appropriateness for the position, helping to avoid unconscious prejudices.
Due to its adaptability, simplicity, strong community support, and potent data science and visualisation capabilities, Python is one of the most widely used programming languages for developing AI models. Python enables developers to quickly prototype and experiment with new models while having easy access to a large choice of libraries and frameworks created expressly for machine learning and AI development.
Generally speaking, an AI model for recruiting based on personality, education, experience, and age is a useful tool for both employers and job seekers alike, aiding in streamlining the hiring process, removing prejudice, and identifying the best applicant for the position.
