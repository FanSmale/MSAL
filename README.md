# MSAL
Active learning selects the most critical instances and obtains their labels through interaction with an oracle. 
Selecting either informative or representative unlabeled instances may result in sampling bias or cluster dependency. 
In this paper, we propose a multi-standard optimization active learning (MSAL) algorithm that considers the informativeness, representativeness, and diversity of instances. 
Informativeness is measured by the soft-max predicted entropy, whereas representativeness is measured by the probability density function obtained by a non-parametric estimation. 
The multiplex of the two is used as an optimization objective to reduce model uncertainty and explore the distribution of unlabeled data. 
Diversity is measured by the difference between the selected critical instances. 
This is used as a constraint to prevent the selection of instances that are too similar. 

The experiments were performed on Matlab R2017a software.

DOI:10.1109/ACCESS.2019.2914263

![image](https://github.com/FanSmale/MSAL/blob/master/framework.png)
