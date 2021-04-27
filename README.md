# K-Nearest Neighbors:

The KNN algorithm assumes that similar things exist in close proximity. In other words, similar things are near to each other.
![image](https://user-images.githubusercontent.com/72427901/116254167-bf344300-a78e-11eb-89a0-6cc0ed61bcc7.png)
Notice in the image above that most of the time, similar data points are close to each other. The KNN algorithm hinges on this assumption being true enough for the algorithm to be useful. KNN captures the idea of similarity (sometimes called distance, proximity, or closeness) with some mathematics we might have learned in our childhood— calculating the distance between points on a graph.

# The Steps taken:
The data we got here was an 'Anonymized DataSource' hence columns weren't mentioned here. Hence firstly we standard scaler transformation so that we can make the data useble for algorithm. 

Based on the standardized data we will be making a new data frame and applied our algorithm on that data set.


# Choosing the right value of K: 

To select the K that’s right for your data, we run the KNN algorithm several times with different values of K and choose the K that reduces the number of errors we encounter while maintaining the algorithm’s ability to accurately make predictions when it’s given data it hasn’t seen before.

The graph that is plotted to visualise between the error rate and K value shows which value of K gives the minimum error and hance using that value in our model we got our best possible accuracy.


# Result/Conclusion: 
1. For (KNN.ipynb) : 96 % 
2. For (KNN_Project.ipynb) : 84 %
 
