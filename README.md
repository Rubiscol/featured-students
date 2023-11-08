# featured-students
This is an official implementation for our paper "Featured students: How to enforce models behave more differently in medical 
anomaly". The code will be released once accepted.

**An overview of our featured students:**
<p align="center">
  <img width="460"  src="https://github.com/Rubiscol/featured-students/blob/main/images/overview.png">
</p>


The model undergoing training is referred to as a junior student, while models that have completed training are considered senior students. Under the explicit constraint, a junior student learns from an intermediate feature path distinct from all its seniors. During the inference phase, a gradient-guided discrepancy integrates both forward and backward information into the discrepancy calculation.

**A simpe illustraition of the explicict constraint:**
<div align="center">
  <img width="460"  src="https://github.com/Rubiscol/featured-students/blob/main/images/Picture5.png">
</div>

**Visualization results**
<div align="center">
  <img width="460"  src="https://github.com/Rubiscol/featured-students/blob/main/images/visual.png">
</div>
