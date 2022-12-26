# 🗞 Fake News Prediction

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Introduction

Fake news, or disinformation, is a growing problem in today's society. It can spread quickly through social media and other online platforms, leading to confusion, mistrust, and even harm. In an effort to combat this issue, the use of machine learning techniques for fake news detection has gained popularity. However, detecting fake news is a complex task that involves understanding the context, content, and intent of the information being shared.

<img src = "https://github.com/suhasmaddali/Images/blob/main/Newspaper%20fake%20news%20repository%20image.jpg" width = 1000 height = "600"/>

## Challenges

There is a lot of text received by people in the form of media and news. Understanding the text and giving it a vectorial representation before they could be used for machine learning reduces the spread of fake news. However, there are challenges that arise when trying to build an end-to-end machine learning system which is capable of accurately predicting fake news. Below are some challenges that are faced for designing a fake news classifier:

1. Lack of high-quality labeled data
2. Evolving nature of fake news
3. Bias in the data
4. Limited generalizability
5. Ethical considerations

## Exploratory Data Analysis (EDA)

It is a method at which we explore the data to find meaningful patterns and insights. As a result, these insights could be reported to the business or the data could be modified to accurately represent the real-world scenario. Exploratory Data Analysis (EDA) was performed to understand the number of fake news rows. The count for all the topics of articles were generated before classifying whether a given text is fake or real. Missing values were also identified.

## Constraints

The model should be able to handle a diverse range of news articles, including those with different writing styles, language, and formats. It should also be able to adapt to changes in the way fake news is presented over time.

## Evaluation

The performance of the model will be evaluated using standard classification metrics, such as precision, recall, and f1-score. The model will also be tested for its ability to generalize to unseen news articles.

* [__Accuracy__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html)
* [__Precision__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_score.html)
* [__Recall__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.recall_score.html)
* [__F1 Score__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html)
* [__Classification Report__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html)
* [__Confusion Matrix__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html)
