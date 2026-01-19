<h1>Classifying Phishing Websites with ML/AI</h1>



<h2>Description</h2>

Developed a machine learning model to classify websites as legitimate or phishing by training on labeled URL features. Evaluated the model by predicting classifications on a separate test dataset and measuring performance using accuracy and other metrics.

<br />

<h2>Phases of project</h2>
n this Python project, I built a machine-learning model that can determine if a website is phishing based upon the properties of a website (e.g. Insecure features, high URL character complexity) with an 89% accuracy score—nothing to write home about, but not terrible considering this was my first time building an AI model from the ground up.

This project consists of 5 Phases:

- Phase I - Preparing the Test Data: This phase of the project entails the cleaning of the training data that was pulled from APWG's Phishing Attack Trends Report , including removing data points that have too much missing information, imputing missing data, and encoding certain features.
- Phase II/ III - Exploratory Data Analysis & Feature Selection: Phase II & III were conducted at the same time due to the results of Phase II directly affecting Phase III. This section of the project focuses on conducting an exploratory analysis of different columns in the dataset; including but not limited to identifying outliers, visualizing the dataset, and recursive feature elimination.
- Phase IV - Exploratory Data Analysis & Feature Selection using Decision Trees: After preparing the data, all 37 features were used to train a decision tree classifier model. This model was used to identify the 7 most important features in the dataset. By isolating the 7 most impactful features, and eliminating everything else, we can greatly reduce the "noise" in the dataset that may negatively impact the final model's performance.
- Phase V - Model Building and Prediction: The 5th and final phase of this project involves selecting the type of AI model with the best performance. Phase V compares the performance of 4 different models that were all trained on the seven features that were selected in Phase IV: Decision Tree Classifier, Random Forest Classifier, Support Vector Machine (SVM), and MLP Regressor. In the end, the Random Forest Classifier model had the best performance, so it was selected as the production model.

<h2>Environments and Languages Used</h2>

- <b>Juniper Notebooks</b>
- <b>Google Colab</b>
- <b>Python</b>

<h2>Project:</h2>
Refer to folder

