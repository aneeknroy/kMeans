Objectives:

1. Understand how K-Means works

2. Learn to read and write non-trivial Python code

Please save a copy of the notebook below in your own Google Drive and open it with Google Colab. The file is viewable only.

https://drive.google.com/file/d/1tmxKyMLeFn3Ch8HEBDO5p4Ni08XwuAb6/view?usp=sharing Links to an external site.

Please use the functions provided in the Jupyter Notebook above to implement Step 5 in the notebook.

The K-means algorithm is the most popular and yet simplest of all the clustering algorithms. Here is how it works:

Select the number of clusters  𝑘  that you think is the optimal number. 
Initialize  𝑘  points as "centroids" randomly within the space of our data.
Attribute each observation to its closest centroid.
Update the centroids to the center of all the attributed sets of observations.
To be implemented -> Repeat steps 3 and 4 a fixed number of times or until all of the centroids are stable (i.e. no longer change in step 4)
Write a Python function to implement the algorithm listed above.
