# Intro
normal subjects stratification with hcp data.

# Dataset 
HCP, 1003 subjs, ica conn, dims: 50 100 200 300 

# Sample conns
n_components = 300
![alt text](https://github.com/kli30/hierarchy/blob/master/conn_samples_4subjs_net300.png)

# Data projections and clusters

## Hierachical clustering

### P: 30
![alt text](https://github.com/kli30/hierarchy/blob/master/hrc-p-30.png)
### P: 100
![alt text](https://github.com/kli30/hierarchy/blob/master/hrc-p-100.png)

<!--### P: 300
![alt text](https://github.com/kli30/hierarchy/blob/master/hrc-p-300.png)
-->

## Root node
![alt text](https://github.com/kli30/hierarchy/blob/master/cmp_subj_root.png)
## Left leaf of root
![alt text](https://github.com/kli30/hierarchy/blob/master/cmp_subj_00.png)
## Right leaf of root
![alt text](https://github.com/kli30/hierarchy/blob/master/cmp_subj_01.png)
## Connectivity for both leaves of root
![alt text](https://github.com/kli30/hierarchy/blob/master/conn_root.png)

## check with lower dims
### dim = 200
![alt text](https://github.com/kli30/hierarchy/blob/master/check_split_dim200.png)
### dim = 100
![alt text](https://github.com/kli30/hierarchy/blob/master/check_split_dim100.png)
### dim = 50
![alt text](https://github.com/kli30/hierarchy/blob/master/check_split_dim50.png)

## validation test, 10-07-2019
random seperation into two datasets, shuffle 100 times, check the resultant patterns and clustering
![alt text](https://github.com/kli30/hierarchy/blob/master/perfect_seperation.png)

# TODOs
1. link to phenotypes (gender/family info)
2. cluster numbers
3. Deep models to build from bottom.
