# Recommendations with IBM

## Contents

* Installation
* Motivation
* Detailed Analysis
* Results
* Licensing and Acknowledgments

### Installation

Basic [Anaconda](https://www.anaconda.com/) installation would be enough to run this code. The following packages have been used to create this notebook.

| Library | Usage |
| ----------------- | ----------- |
|Pandas|to handle and manipulate data|
| Numpy | to perform numpy array operations |
| Matplotlib | for data visualization |

### Motivation

This project is fascilitated to understand user interactions with articles on the IBM Watson Studio Platform and then recommend new articles that would be most suited for that user.

### Detailed Analysis

We try out various approaches to this problem.

* Rank based recommendation
    Based on the popularity of an article we make a decision if the article can be recommended or not. This is based on the past data of the article interactions with other users. 
* User bases collaborative filtering
    Rank based filtering fails to find the best possible articles that a specific user might like. So in addition to the best possible article we would like to group the set of users to based on their article interaction data. We find the most popular articles read by those group of users and recommend them among the users that fall in to the same group of people.

### Results

Result is that the user gets articles recommended to them based on the reading experience of their closest neighbours. If a user is new to the platform they will be suggested the top articles before capturing and personalizing the recommendation to the new user.

Many improvements can be made on this by taking into account language, geography, cultural reads as well as taking feedback from the user about a suggestion.

## Licensing and Acknowledgements

This code is part of the Udacity project for data science nanodegree. The data has been provided by the IBM Watson Studio platform and you can become a member of the community [IBM Watson Studio](https://dataplatform.cloud.ibm.com/loginhttps://dataplatform.cloud.ibm.com/login) to gain a better understanding of the data. I don't hold rights for the data. Feel free to use the code.