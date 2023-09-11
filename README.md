# Pokemon-Data-Mining
Data Mining Project Proposal

Group Members: Yuet Ho, Mir Shahiduzzaman, Abby Fontana, Ari Markos, and Tanvir Ahmed
 
Abstract
Goal: Given an input pokemon, how can we classify what its type is?
As a Pokemon research team, we looked into the most ethical way to classify the type of Pokemon based on its stats. We first split the dataset into 6 datasets, each with their own attributes. We then removed unhelpful data in determining the type and selected the best K value for our models. The next step was for us to run the models. The first model was Naive Bayes, for which we used Guassian, Bernoulli, and Multinomial. We found Guassian to be least effective compared to the other classifiers in the Naive Bayes. The Bernoulli Chi-Squared’s highest accuracy was 52%. The Multinomial provided the second highest accuracy with the Chi Square feature selection yielding an accuracy of 51%. We also used a decision tree. After optimizing and trimming, we learned the most accurate tree was the gini tree, with an accuracy of 47%. As for the K Nearest Neighbor, it provided the least accurate results, mainly due to the datasets having a high number of data points. While completing the ensemble, we were able to increase the accuracy for each, but only by 0.01 for Multinomial, 0.04 for the decision tree, and 0.02 for the decision tree using the random forest classifier. As a result, we concluded that we cannot classify pokemon solely based on its stats, but we hypothesized that it would be possible given more data, such as color and appearance.

Data Set: Complete Pokemon Dataset (Updated 16.04.21)
	Our data set is a complete set of data on the 1028 Pokemon, which are creatures in a popular video game series. These creatures come in various shapes, sizes, and types and our data including Pokedex number, English name, German name, Japanese name, which generation the Pokemon was introduced in, whether the Pokemon is legendary, sub-legendary, or mythical or not, species, and much more. Overall, there are 52 different features available for each pokemon. These different features along with the size of our data set should be enough to do analysis on.
