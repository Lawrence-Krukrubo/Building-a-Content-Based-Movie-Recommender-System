# Building-a-Content-Based-Movie-Recommender-System.
## Applying Content-Based filtering and Matrix-Algebra to build a Movie-Recommender-System with Pandas.

### Definition of Recommender Systems:
Recommendation systems are a collection of algorithms used to recommend items to users based on information taken from the user. 
These systems have become ubiquitous, and can be commonly seen in online stores, movies databases and job finders. 
In this notebook, we will explore Content-based recommendation systems and implement a simple version of one using Python, Pandas library.

**Content Based Recommender Systems:**
A Content-based recommender system tries to recommend items to users, based on their profile. 
The user’s profile revolves around the user’s preferences and tastes, or based on the user ratings.

### Dependencies:
To follow along with this project, it's ideal to have the following library imported into a notebook in an IDE.
I used the Colab IDE for this project, but any IDE would suffice. 
All we need is Pandas and a good knowledge of matrix-Algebra.

* `import pandas as pd`


### Project Structure:

1. **Data Acquisition:**
We shall use a public data set for movie ratings from [Grouplens.org](https://grouplens.org/datasets/movielens/).
The `ratings.csv`and `movies.csv` data sets are available for your use in the root directory of this repo.

2. **Data Cleaning and Pre-processing:**
A summary of the tasks in this phase include:-
* Fixing missing values. 
* Assigning proper headers. 
* Removing irrelevant features. 
* Applying descriptive Statistical moments.
* One-Hot-Encoding categorical features and confirming proper data types.

3. **Content Based System:**
Tasks here include:-
* Creating User Profiles. 
* Extracting User's Preferences. 
* Learning the User Profile via Matrix-Algebra. 
* Building Recommendations.
* Deploying the Recommender System.

### Summary:
#### Pros and Cons of Content-Based Recommender Systems.

**Pros:**
* Learns user’s preferences
* Highly personalized for the user

**Cons:**
* Doesn’t take into account what others think of the item, so low-quality item recommendations might happen
* Extracting data is not always intuitive
* Determining what characteristics of the item the user dislikes or likes is not always obvious
* No new genre of movies will ever get recommended to the user, except the user rates or indicates his/her preference for that genre.

A better solution is a **Hybrid-Recommender-System** that combines both Content-Based-Filtering and Collaborative-Filtering to proffer personalised as well as generally popular and preferred movies by Users who are similar to the User.

### Further Insights:
Kindly see my article on this Project in The Medium. I have spent some time explaining all the codes and processes to build a Recommender System using only Pandas. 
* [link](https://medium.com/towards-artificial-intelligence/building-a-recommender-system-with-pandas-1ca0bb03fdce)

### License:
Items in this repo abide under the MIT License as seen in the root directory
