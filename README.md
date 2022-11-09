# ASSIGNMENT5
NAME: NAMBURI VENKATA GOPALA KRISHNA SWAMY 
ID:700719027
QUESTION-1: In this question we have applied the principal component analysis in the cc dataset in which the data is found 
after that we applied the k-means algorithm on the result of pca and reported the observation like silhouette score is improved or not in my view compared to k-means is having high silhoutte score compared to the after applied of all the methods 


QUESTION-2: similarly using pd_speech_features.csv we have performed scaling and after applied pca wuth k=3 and used svm to get the performance 
This is about the second question 


QUESTION-3: Here we applied linear discriminant analysis on the data of iris.csv and to reduce the dimentionality to the value k=2 and also the plot graph is mentioned in the solution in detail 


QUESTION4: Briefly identify the difference between PCA and LDA?
ANSWER: Maximizing variance in a lower dimension is the goal of both LDA and PCA, which both use on linear transformations. 
A supervised learning method is LDA, whereas PCA is an unsupervised learning algorithm. 
This indicates that whereas LDA discovers paths of maximum class separability, PCA discovers directions of maximum variance regardless of class labels


1)PCA
It actually means the Principal components, or linear combinations of the original variables, are used to condense the characteristics into a more manageable group of orthogonal variables.
 The highest amount of data variability is captured by the first component, followed by the second and third, and so on.

 2)LDA
 Maximizing the variation across the various categories while limiting the variance inside the class is the goal of LDA, 
 which identifies the linear discriminants.

 Which approach should you employ? That depends on the type of data you're using and the objectives you have.
 LDA is definitely your best option if you're working with labeled data and want to develop a low-dimensional representation that maximizes class separability. 
 PCA might be a preferable option, though, if your only concern is locating a low-dimensional representation that captures as much information as possible or 
 if you're dealing with unlabeled data.

Generally speaking, it's always worthwhile to test both strategies on your dataset to see which one produces the best results.
