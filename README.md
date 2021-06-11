# Recommendation Systems IBM

![IBM](images/IBM.png)

## Table of Contents
1. [Description](#description)
2. [Dependencies](#dependencies)
3. [Installing](#installation)
4. [File Descriptions](#exfiles)

<a name="descripton"></a>
## Description
Recommendation systems are one of the most successful and widespread applications of machine learning technologies in business. They play an essential role in helping users find products and content they care about while delivering a lot of value to bussinesses.

Before making recommendations of any kind, I clean the dataset and provide some visuals and descriptive statistics to help us get a better understanding of the data we are working with. The implemented recommendation systems are able to suggest articles on the IBM Watson studio platform to users(both recurring and new), as depicted by the image above. There are different approaches to recommendation system and three of them have been implemented in this project:

1. Rank-based recommendation for new users
> - recommend most popular articles
2. User-user based collaborative filtering for existing users
> - recommend articles based on what similar users liked
3. User-item based collaborative filtering for existing users
> - matrix factorization and singular value decoposition(SVD) to recommend articles based on the history of user-article interactions

<a name="dependencies"></a>
## Dependencies
This project requires Python 3.x and the following Python libraries installed:
- [Numpy](https://numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Matplotlib](https://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

<a name="installation"></a>
## Installing
To clone the git repository:
```
git clone https://github.com/HROlive/Recommendation-Systems-IBM.git
```

<a name="exfiles"></a>
## File Descriptions
In order to determine which articles to recommend to each user, I'll be performing a study of the following datasets:

* `/data/user-item-interactions` - This dataset contains user interactions.
* `/data/articles_community` - This dataset contains details about the articles.
* `Recommendations_Systems_IBM.ipynb` - data analysis and implementation of the recommendation systems.
