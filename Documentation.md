# Job-Hiring-Based-on-Personality-Education-Experience-and-Age
Supervised Learning: Decision Tree Classifier on topic Job Hiring Based on Personality, Education, Experience and Age


- [Introduction](#introduction)
- [Problem statement](#problem-statement)
- [Objectives](#objectives)
- [How to Deploy Model](#how-to-deploy-model)
- [Used Dataset](#used-dataset)
- [Data Preparation](#data-preparation)
- [Tools](#tools)
- [Programming Language](#programming-language)
- [Conclusion](#conclusion)


## Introduction
Employers are continually seeking for methods to streamline their hiring procedures and find the best applicants for their organisations in today's fast-paced and ever-changing employment market. Our AI model makes use of the most recent developments in machine learning and natural language processing to analyse a candidate's personality traits, educational history, professional experience, and age and offer insightful information about their fit for a given post.

Employers may analyse a big pool of candidates fast and correctly using our AI model, and then decide who to invite for interviews or offer employment openings based on data. As the AI model employs objective criteria to evaluate each candidate, this not only saves time and money but also assures that the recruiting process is fair and impartial.

Our AI model, which was trained to find patterns and correlations between many elements that affect work performance, is based on a vast dataset of information about jobs. Our AI model can give you useful insights to help you reach your objectives, whether you're an employer trying to recruit the top applicants or a job seeker looking to find the ideal employment match.

## Problem Statement
1) The traditional hiring process is time-consuming and expensive, resulting in a slow hiring process and a higher hiring price.
2) Hiring is also a process that is subject to bias and inconsistency because recruiters are human with vulnerability and rely on subjective judgments.
3) During interviews, candidates may misrepresent themselves due to nervousness. It is therefore difficult for the recruiter to determine their true personality traits and characteristics.


## Objectives
1) To develop an A.I. Model to accurately predict job hiring based on personality test results
2) To reduce the time and cost associated with the hiring process by automating the personality testing and job hiring probability prediction process
3) To minimize the bias and inconsistencies in job recruitment process by using objectives measure of personality traits and characteristics.

## How to Deploy Model
To deploy the Decision Tree Classifier model for job hiring based on personality, education, experience, and age, you will need to prepare the environment, load the dataset, split the data, train the model, test the model, save the model, and deploy the model in a way that suits your requirements.
1. Prepare Environment – For our model, we use Google Collab as IDE. 

![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deploy1.png)
2. Load the datasets – Import the necessary libraries and load the datasets that have been downloaded and read it using pd.read_excel(file_path). 

![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deploy2.png)
3. Data Preparation
	1. Drop unwanted columns 

	![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deploy3i.png)
	
	2. Feature Selection

	![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deploy3ii.png)
4. Define hyperparameter for search over to increase the model accuracy 

![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deploy4.png)
5. Split the data – Split the dataset into training and testing data using the train_test_split() function from the scikit-learn library. 

	![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deploy5i.png) 

	![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deploy5ii.png)

6. Train the model – Create an instance of the DecisionTreeClassifier class from the scikit-learn library and fit the training data to the model using the fit() function. 

![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deploy6.png)
7. Test the model – Test the trained model on the testing data using the predict() function and evaluate the model's performance using metrics such as accuracy, precision, recall, and F1-score. 

![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deploy7.png)

Result:

![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/deployresult.png)

## Used dataset
Our model used dataset from Mendeley Data named the data of HEXACO personality traits and job search outcomes that you can find it in https://data.mendeley.com/datasets/p9hwfmfcz5/3 . The data size is collected from 773 Vietnamese university undergraduate. The dataset consists of 93 columns, each representing a different feature. The features are:
1) Gender: 1 for Male and 2 for Female. 
2) Married: 1 for Yes and 2 for No
3) Age: 1 for between 20-21, 2 for between 22-23, 3 for between 24-25, 5 for above 25
4) Qualifications: 1 for finance, 2 for business, 3 for accounting, 4 for engineering, 5 for other.
5) Experience: 1 for under 1 year, 2 for 1-2 years, 3 for over 2 years.
6) Honesty1-Honesty10: Survey questions asking the applicant to rate themselves on 1-5 scale how honest they are.
7) Emotion1-Emotion8: Survey questions asking the applicant to rate themselves on 1-5 scale how good they are in handling their emotion.
8) Extravert2-Extravert10: Survey questions asking the applicant to rate themselves on 1-5 scale how extroverted they are.
9) Agreeable1-Agreeable10: Survey questions asking the applicant to rate themselves on 1-5 scale how agreeable they are.
10) Conscientious1-Conscientious8: Survey question asking the applicant to rate themselves on 1-8 scale how careful attention to detail, thoroughness, and a strong work ethic they are
11) Openness1-Openness10: Survey questions asking the applicant to rate themselves on a 1-5 scale on how open-minded they are
12) Clarity1-Clarity4: Survey questions asking the applicant to rate themselves on a 1-5 scale on how clear their communication is
13) Size1-Size4: Survey questions asking the applicant to rate themselves on a 1-5 scale on how well they work in different team sizes
14) Strength1-Strength3: Survey questions asking the applicant to rate themselves on a 1-5 scale on their personal strengths
15) Comfort1-Comfort6: Survey questions asking the applicant to rate themselves on a 1-5 scale on how comfortable they are in different situations
16) Proactive1-Proactive10: Survey questions asking the applicant to rate themselves on a 1-5 scale on how proactive they are
17) Behavior1-Behavior5: Survey questions asking the applicant to rate themselves on a 1-5 scale on how they would behave in different situations
18) Interview1-Interview2: Survey questions asking the applicant to rate how they felt about the interview process
19) Offer1-Offer2: Recruiter will give candidates scale from 1-5 how likely they will get a job offer.

Scale:
* 1: Strongly Disagree
* 2: Disagree
* 3: Neutral
* 4: Agree
* 5: Strongly Agree

The target variable is Offer1-Offer2, indicating whether or not the applicant was offered a job. The decision tree classifier will use the other 92 features to predict whether or not an applicant will be offered a job based on their personality, education, experience, and age

## Data Preparation
The dataset then being checked for any null or wrong format cell. 

![alt text](https://github.com/UlamKetum/Job-Hiring-Based-on-Personality-Education-Experience-and-Age/blob/main/content/dataprep.png)
 
Figure above shows the data is complete, no null value, every cell is in integer value, and after thorough data view by researchers every cell holds a value that are in scale of the description from data collector.

Researchers then find the average or mean for each category of personality and change and new columns for average of each category in the dataset. The new column are such.
1) Ahonesty: Average of Honesty1-Honesty10
2) Aemotion: Average of Emotion1-Emotion8
3) Aextravert: Average of Extravert2-Extravert10
4) Aagreeable: Average of Agreeable1-Agreeable10
5) Aconscientious: Average of Conscientious1-Conscientious8
6) Aopenness: Average of Openness1-Openness10
7) Aclarity: Average of Clarity1-Clarity4
8) Asize: Average of Size1-Size4
9) Astrength: Average of Strength1-Strength3
10) Acomfort: Average of Comfort1-Comfort6
11) Aproactive: Average of Proactive1-Proactive10
12) Abehavior: Average of Behavior1-Behavior5
13) Ainterview: Average of Interview1-Interview2
14) Aoffer: Average of Offer1-Offer2
15) Classification : If Aoffer is 4 and above then Classification set as High, else Low. Meaning high probability of being offer a job and low probability of being offer a job.

## Tools
Google collab as our IDE in running model

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
