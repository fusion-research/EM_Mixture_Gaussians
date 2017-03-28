# EM_Mixture_Gaussians
Implementation of the Expectation-Maximization Algorithm for a Mixture of Gaussians for the wine data set from the UCI repository which can also be found at: https://archive.ics.uci.edu/ml/datasets/Wine. 

To run this program do as follows.

python gaussmix.py <# number of components> <name of data file> <name of output file>

The data file should be in the same directory of gaussmix.py and as where it is being run from.

An example is as follows:

python gaussmix.py 3 wine.train.txt output.csv

The result of running the program will be an output file with the component priors and component features means and variances.

<# of clusters> <# of features>
<clust1. prior> <clust1. mean1> <clust1. mean2>... <clust1. var1>...
<clust2. prior> <clust2. mean1> <clust2. mean2>... <clust2. var1>...

