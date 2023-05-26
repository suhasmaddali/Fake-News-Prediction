# 🗞 Fake News Prediction

[![](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=darkgreen)](https://www.python.org)  [![](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white)](https://www.tensorflow.org) [![](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/) [![](https://img.shields.io/badge/SciPy-654FF0?style=for-the-badge&logo=SciPy&logoColor=white)](https://www.scipy.org) [![](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org) [![](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)  [![](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com) [![](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)](https://keras.io) [![](https://img.shields.io/badge/conda-342B029.svg?&style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)

## Introduction

__Fake news__, or disinformation, is a growing problem in today's society. It can spread quickly through __social media__ and other online platforms, leading to confusion, mistrust, and even harm. In an effort to combat this issue, the use of __machine learning techniques__ for fake news detection has gained popularity. However, detecting fake news is a complex task that involves understanding the context, content, and intent of the information being shared.

<img src = "https://github.com/suhasmaddali/Images/blob/main/Newspaper%20fake%20news%20repository%20image.jpg" width = 1000 height = "600"/>

## Challenges

There is a lot of text received by people in the form of __media__ and __news__. Understanding the text and giving it a vectorial representation before they could be used for machine learning reduces the spread of fake news. However, there are challenges that arise when trying to build an __end-to-end machine learning system__ which is capable of accurately predicting fake news. Below are some challenges that are faced for designing a fake news classifier:

1. Lack of high-quality labeled data
2. Evolving nature of fake news
3. Bias in the data
4. Limited generalizability
5. Ethical considerations

## Exploratory Data Analysis (EDA)

__Exploratory Data Analysis (EDA)__ is a critical process that allows us to delve into data to uncover meaningful patterns and gain valuable insights. These insights can be instrumental in informing business decisions or enabling data modification to more accurately mirror real-world situations. EDA was employed specifically to discern the quantity of 'fake news' entries within the data. By first enumerating the topics of all articles, it laid the groundwork for classifying texts as either real or fake. Furthermore, the EDA process was crucial in identifying any missing values within the data set.

We have successfully loaded a dataframe containing verified news stories. A preview of the first five entries in this data offers a glimpse into the type of information it houses. One notable feature is the 'subject' category, which provides insight into the topics of the news stories. Additionally, the dataframe includes a 'date' field, indicating when each news piece was originally published.

<img src = "https://github.com/suhasmaddali/Fake-News-Prediction/blob/main/Images/True%20news%20df.jpg"/>

In a similar vein, we're keen on examining the dataset comprised of fake news. It appears to have similar columns to the true news dataset. For the purpose of conducting a comprehensive machine learning analysis, we plan to merge these two datasets together.

<img src = "https://github.com/suhasmaddali/Fake-News-Prediction/blob/main/Images/Fake%20news%20df.jpg"/>

A significant portion of our data is primarily made up of political news, with world news forming a smaller share. This distribution gives us a comprehensive understanding of the nature of our dataset, setting a solid foundation for our forthcoming machine learning analysis.

<img src = "https://github.com/suhasmaddali/Fake-News-Prediction/blob/main/Images/newstype%20countplot.jpg"/>

<img src = "https://github.com/suhasmaddali/Fake-News-Prediction/blob/main/Images/Subject%20countplot.jpg"/>

<img src = "https://github.com/suhasmaddali/Fake-News-Prediction/blob/main/Images/True%20vs%20fake%20news%20countplot.jpg"/>

__True news wordcloud:__

<img src = "https://github.com/suhasmaddali/Fake-News-Prediction/blob/main/Images/Fake%20news%20wordcloud.jpg"/>

__Fake news wordcloud:__

<img src = "https://github.com/suhasmaddali/Fake-News-Prediction/blob/main/Images/True%20news%20title.jpg"/>

## Constraints

The model should be able to handle a diverse range of news articles, including those with different writing styles, language, and formats. It should also be able to adapt to changes in the way fake news is presented over time.

## Evaluation

The __performance__ of the model will be evaluated using standard classification metrics, such as precision, recall, and f1-score. The model will also be tested for its ability to generalize to unseen news articles.

* [__Accuracy__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html)
* [__Precision__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_score.html)
* [__Recall__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.recall_score.html)
* [__F1 Score__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html)
* [__Classification Report__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html)
* [__Confusion Matrix__](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html)

## Outcomes

* Using machine learning for fake news classification can result in the creation of a model that can automatically identify fake news and flag it for further review or moderation. 
* This can help to reduce the spread of __false__ or __misleading information__ and protect the integrity of online content.
* In general, well-trained machine learning models can be effective at identifying fake news with a high degree of accuracy. 

## 👉 Directions to download the repository and run the notebook 

This is for the Washington Bike Demand Prediction repository. But the same steps could be followed for this repository. 

1. You'll have to download and install Git which could be used for cloning the repositories that are present. The link to download Git is https://git-scm.com/downloads.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(14).png" width = "600"/>
 
2. Once "Git" is downloaded and installed, you'll have to right-click on the location where you would like to download this repository. I would like to store it in the "Git Folder" location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(15).png" width = "600" />

3. If you have successfully installed Git, you'll get an option called "Gitbash Here" when you right-click on a particular location. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(16).png" width = "600" />


4. Once the Gitbash terminal opens, you'll need to write "Git clone" and then paste the link to the repository.
 
&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(18).png" width = "600" />

5. The link to the repository can be found when you click on "Code" (Green button) and then, there would be an HTML link just below. Therefore, the command to download a particular repository should be "Git clone HTML" where the HTML is replaced by the link to this repository. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(17).png" width = "600" />

6. After successfully downloading the repository, there should be a folder with the name of the repository as can be seen below.

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(19).png" width = "600" />

7. Once the repository is downloaded, go to the start button and search for "Anaconda Prompt" if you have anaconda installed. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(20).png" width = "600" />

8. Later, open the Jupyter notebook by writing "Jupyter notebook" in the Anaconda prompt. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(21).png" width = "600" />

9. Now the following would open with a list of directories. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(22).png" width = "600" />

10. Search for the location where you have downloaded the repository. Be sure to open that folder. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(12).png" width = "600" />

11. You might now run the .ipynb files present in the repository to open the notebook and the python code present in it. 

&emsp;&emsp; <img src = "https://github.com/suhasmaddali/Images/blob/main/Screenshot%20(13).png" width = "600" />

That's it, you should be able to read the code now. Thanks. 
