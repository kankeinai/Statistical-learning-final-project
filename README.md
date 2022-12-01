# Statistical learning final project

In this project, I am going to analyse how theorem
$$C_1 \frac{d + \log{(1/ \delta)}}{\epsilon} \leq m_H(\epsilon, \delta) \leq C_2 \frac{d\log{(1/\epsilon)} + \log{(1/\delta)}}{\epsilon}$$
is applicable as bound for sample size to have loss less than $\epsilon$ with probability $1-\delta$.

For this I will generate synthetic data and conduct a series of experiments. I also will try out it on a real dataset, namely, Hear disease dataset.

List of files:
– Heart_Disease_Prediction.csv - dataset with real data
- Statisctical_learning.ipynb - source code with all experiments

In order to see the results of the experiments, you can just open Statisctical_learning.ipynb and look through the output and my comments in jupyter notebook. Or you can run all the experiments on your own, but note that it will take some time.

Needed packages:
- numpy, pandas, matplotlib, sklearn, collections

Language:
Python
