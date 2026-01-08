# SENTIMENT-ANALYSIS-WITH-NLP

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: SAYEE WAGH

*INTERN ID*: CTIS0996

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

##DESCRIPTION

The objective of this task is to perform sentiment analysis on a dataset of customer reviews using Natural Language Processing (NLP) techniques. Sentiment analysis is used to determine whether a given piece of text expresses a positive or negative opinion. This technique is widely used by organizations to understand customer feedback, improve products, and enhance user experience.

In this task, a dataset containing customer review texts and their corresponding sentiments is used. The first step involves data preprocessing, which is an important part of NLP. The raw text data is cleaned by converting all text to lowercase, removing punctuation, numbers, and unnecessary spaces. This helps in reducing noise and makes the text suitable for further analysis.

After preprocessing, the text data is converted into numerical form using TF-IDF (Term Frequency–Inverse Document Frequency) vectorization. TF-IDF assigns importance to words based on how frequently they appear in a review and how unique they are across the dataset. This transformation is necessary because machine learning algorithms work only with numerical data.

Once the text is vectorized, the dataset is divided into training and testing sets. The training data is used to build the machine learning model, while the testing data is used to evaluate its performance. Logistic Regression is used as the classification algorithm in this task because it is simple, efficient, and well-suited for binary classification problems such as sentiment analysis.

After training the model, predictions are made on the test data. The performance of the model is evaluated using metrics such as accuracy, confusion matrix, precision, recall, and F1-score. These evaluation metrics help in understanding how well the model classifies customer reviews into positive and negative sentiments.

The entire implementation is performed using Python in a Jupyter Notebook, which allows step-by-step execution and clear presentation of results. This task provides hands-on experience with text preprocessing, feature extraction, machine learning modeling, and evaluation, making it a strong introduction to practical NLP applications.
