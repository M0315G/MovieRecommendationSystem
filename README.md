# Movie Recommendation System (from Scratch)

Recommendation Systems have been around us since a long time. They use various different approaches to build an effective recommendation system. This project is build on the approach of collaborative filtering. This recommendation system take input the ratings given by different users on various movies and outputs the recommendation for a user based on his/her watch history as well as that of his/her like beings.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install the software

```
1. Pandas package
2. Numpy package
3. Os package
4. Scipy package
```

### Walkhthrough of the code

To get started with the code, first install all the packages described above and download the two data files present in the GitHub Repo.

The description of each function is given below :
````
read_data() : This function will read the data from the data files into the panda dataframe for future use!
````
````
data_stats() : This function displays the stats for the present data. We display the frequency of ratings for each movie as well as the no of movies and users. Feel free to tweak the function to get out more stats from the data.
````
````
preprocess_data() : The dataframe created in the previous function contains a large no of zeros as there are many movies which are not rated by many users. This creates an unnecessary empty space into the matrix. Thus we preprocess it to reduce the memory component using scipy.
````
````
compute_cost() : This cost function.
````
````
grads() : Gradient descent is performed inside this function. The specifics about it is available in the comments of the code.
````
````
model() : This is the final compiled model. It calls every above function in their proper order and takes care of the hyperparameters. Run this function to get the final trained parameters.
````
````
predict() : This function is used for predicting the movie ratings for users and recommending them based on their watch history.
````

## Authors

* **Manish Gupta** - [M0315G](https://github.com/M0315G)
* **Ishan Tewari** - [M0315G](https://github.com/M0315G)
