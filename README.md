# k-means-clustering

This is the k-means clustering algorithm implemented in Python with minimal help from libraries that directly implement it.

Please note that I used the following book as a guide: 

#### Machine Learning for Absolute Beginners: A Plain English Introduction (Second Edition) by Oliver Theobald
    
The model constructed below are based on the explanations provided in the book. 

   - One of the most popular unsupervised learning algorithms. 
   - Essentially this is the division of data into "k" clusters based on similar features. 
   - Select a centroid for each cluster 
   
Use Expectation-Maximization to estimate the centroids (cluster centers). So it is very similar to any other iterative method such as Jacobi, Gauss-Seidel, Gradient Descent, etc. where you pick a random point and choose a new point that is much closer to the actual answer. Repeat the process until it converges into a single value.
