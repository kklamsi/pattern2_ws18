<h1>Topic: Advanced Feature Selection Algorithms</h1>

<FONT COLOR="#FF0000">Änderung: KNN zur Classification</FONT>

# Report
Gliederung:
1. Introduction/Motivation
2. Data set
3. Methods
4. Results
5. Discussion
6. Conclusion

Deadline: 15.02.2019

# Goal
Compare the performance of three different Feature Selection Algorithms based on a Neural Network whereas a smaller number of features is priorized.
The parameters of the Neural Network are adopted from the paper 'Short-Term Memory Mechanisms in Neural Network Learning of Robot Navigation Tasks: A Case Study' (Ananda et al., 2009).
The observed Feature Selection Algorithms are

1. Linear Discriminant Analysis

2. GreedyStepwise: Performs a greedy forward or backward search through the space of attribute subsets. http://weka.sourceforge.net/doc.dev/weka/attributeSelection/GreedyStepwise.html

3. Correlation Feature Selection

4. Randomized Feature Selection

# Data
As data we take the 'Wall-Following Robot Navigation Data Data Set' from https://archive.ics.uci.edu/ml/datasets/Wall-Following+Robot+Navigation+Data.
Within the data set there exist 24 attributes (features) from sensors around the robot.

# Implementation
Weka
https://www.cs.waikato.ac.nz/ml/weka/downloading.html

# Evaluation
The evaluation is based on the performance of the Neural Network.

NN Parameter:
For  the  MLP  network,  preliminary  tests  were  made
with different numbers of hidden neurons to find out the
minimum value that enables a suitable class separation.
It  was  found  that q =  6  is  that  minimum  value.  The
output  layer  consists  of c =  4  neurons  with  logistics
activation function. The MLP is trained for 500 epochs
with a learning rate set to η = 0.05.

Other measures?
