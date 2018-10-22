<h1>Topic: Advanced Feature Selection Algorithms</h1>

# Goal
Compare the performance of three different Feature Selection Algorithms based on a Neural Network whereas a smaller number of features is priorized.
The parameters of the Neural Network are adopted from the paper 'Short-Term Memory Mechanisms in Neural Network Learning of Robot Navigation Tasks: A Case Study' (Ananda et al., 2009).
The observed Feature Selection Algorithms are

1. Linear Discriminant Analysis

2. GreedyStepwise: Performs a greedy forward or backward search through the space of attribute subsets. http://weka.sourceforge.net/doc.dev/weka/attributeSelection/GreedyStepwise.html

3. 

4. 

# Data
As data we take the 'Wall-Following Robot Navigation Data Data Set' from https://archive.ics.uci.edu/ml/datasets/Wall-Following+Robot+Navigation+Data.
Within the data set there exist 24 attributes (features) from sensors around the robot.

# Implementation
Weka
https://www.cs.waikato.ac.nz/ml/weka/downloading.html

# Evaluation
The evaluation is based on the performance of the Neural Network.

Other measures?
