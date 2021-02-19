# customer-segmentation-using-k-means

## Overview 

Customer Segmentation is the process of division of customer base into several
groups of individuals that share a similarity in different ways that are relevant to
marketing such as gender, age, interests, and miscellaneous spending habits. In the first
step of this data science project, we will perform data exploration. We will import the
essential packages required for this role and then read our data. Finally, we will go
through the input data to gain necessary insights about it.

#### K-Means Clustering:

K-Means algorithm is an iterative algorithm that tries to partition the dataset into K
pre-defined distinct non-overlapping subgroups (clusters) where each data point belongs
to only one group. It tries to make the intra-cluster data points as similar as possible
while also keeping the clusters as different (far) as possible. It assigns data points to a
cluster such that the sum of the squared distance between the data points and the
cluster’s centroid is at the minimum. The less variation we have within clusters, the
more homogeneous the data points are within the same cluster.
We then proceeded to perform K-means Clustering which will create different
clusters to group similar spending activity based on their age and annual income. KMeans Clustering selects random values from the data and forms clusters assigned. The
closest values from the centre of each cluster were taken to update the cluster and
reshape the plot (just like k-NN). The closest values are based on Euclidean Distance.

This is the code for Customer Segmentation Project made for [EXPOSYS DATA LABS](http://www.exposysdata.com/), Bengaluru.


## Clone Repository
Clone this Repository using,

	git clone https://github.com/mayursrt/customer-segmentation-using-k-means.git


## Usage
Install `jupyter` from [here](http://jupyter.readthedocs.io/en/latest/install.html) or use

	pip install jupyter

After installing jupyter notebook Just run `jupyter notebook` in terminal and you can visit the notebook in your web browser.


## Create Environment

Create an environment using the `requirements.txt` using pip by using following command so you dont have to install dependencies one by one,


	pip -r requirements.txt

If you need to use conda to create the environment,
Read conda docs on managing environments [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)


## Dependencies

* [Pandas](https://pandas.pydata.org/docs/)
* [NumPy](https://numpy.org/devdocs/user/index.html)
* [Matplotlib](https://matplotlib.org/3.3.3/contents.html)
* [Seaborn](https://seaborn.pydata.org/)
* [Sklearn](https://scikit-learn.org/stable/)

Install missing dependencies using,

	pip install pandas numpy matplotlib seaborn sklearn


