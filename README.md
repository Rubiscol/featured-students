# featured-students
This is an official implementation for our paper "Featured students: How to enforce models behave more differently in medical 
anomaly". The code will be released once accepted.

An overview of our featured students: 
![alt text](https://github.com/Rubiscol/featured-students/blob/main/images/structure.png)
The model undergoing training is referred to as a junior student, while models that have completed training are considered senior students. Under the explicit constraint, a junior student learns from an intermediate feature path distinct from all its seniors. During the inference phase, a gradient-guided discrepancy integrates both forward and backward information into the discrepancy calculation.

A simpe illustraition of the explicict constraint
![alt text](https://github.com/Rubiscol/featured-students/blob/main/images/Picture5.png)

Visualization results：

![alt text](https://github.com/Rubiscol/featured-students/blob/main/images/visual.png)
