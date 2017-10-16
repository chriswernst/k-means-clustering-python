## K-means Clustering in Python
###### October 2017

###
###

### Overview

###### In this README, we'll walk through the `kMeansClustering.py` example code to show how the algorithm works. This code is courtesy of Udacity's Robotics Nanodegree.

###

![alt text](https://d17h27t6h515a5.cloudfront.net/topher/2017/July/59611b02_screen-shot-2017-07-08-at-10.48.32-am/screen-shot-2017-07-08-at-10.48.32-am.png)

###
###

[**Here is a very cool tool, built by Naftali Harris, for helping to visualize k-means clustering!**](https://www.naftaliharris.com/blog/visualizing-k-means-clustering/)

K-Means Clustering is an appropriate clustering algorithm if you are aware of your dataspace and have a rough idea of the number of clusters.

Remember, with K-Means, we:

**1.** Choose the number of k-means
**2.** Define the convergence / termination criteria (stability of solution / number of iterations)
**3.** Select the initial centroid locations, or randomly generate them
**4.** Calculate the distance of each datapoint to each of the centroids
**5.** Assign each of the datapoints to one of the centroids(clusters) based upon closest proximity
**6.** Recompute the centroid based on the datapoints that belong to it
**7.** Loop back to **Step 4** until convergence / termination criteria is met

###


###

If you are unsure of the number of clusters, it is best to use a different clustering solution! Such as DBSCAN!

***README IN PROGRES***