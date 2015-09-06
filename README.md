# twitter_graph
Discover Social Circles in Twitter Ego Network

In this notebook, we look into the first degree social-network of the given-user and explore the social-structure within the ego-network. i.e. We look at the given-user's friends and study the network between his friends. Given user is called as 'ego' and his friends are 'alters' and objective is to identify communities/clusters in given user's ego network.

(1) Connect to Twitter API and build ego-network (network of connections between given user's friends) (2) Identify top-influencers in the ego-network by running PageRank algorithm on Markov Transition matrix (3) Explore the network-structure with help of clustering algorithms to identify clusters of interest (4) Recommend Who-to-Follow on the basis of meaningful Clusters from previous step (5) Visualization: Visualize clusters in 2 dimensions and look for actionable surprises (Using Principal Component Analsyis, multi-dimensional data is reduced to 2 dimensions)

More details here:
1. Interactive-Graphics: https://balaca.shinyapps.io/Twitter_Graph
2. PageRank and Clustering in Ego-Network: http://nbviewer.ipython.org/github/balaca/twitter_graph/blob/master/1.%20TwitterAPI_Pagerank_Clustering.ipynb
3. Visualising Data: http://nbviewer.ipython.org/github/balaca/twitter_graph/blob/master/2.%20Visualise_Data.ipynb
