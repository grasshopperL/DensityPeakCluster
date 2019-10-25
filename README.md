# DensityPeakCluster

Python Code For 'Clustering By Fast Search And Find Of Density Peaks' In Science 2014

## Introduction

HAHAHA, I don't want to write it  


## How to Use
  
Step0: If your data is not the distance between points but the points' vector, write you distance builder in distance like distance_builder_data_spiral.py.  
Step1: Change the data file in step1_choose_center.py, then run it to choose cluster threshold.  
Step2: Change the data file and threshold in step2_cluster.py, then run it.  
```python
python distance_builder_data_[datename].py
python step1_choose_center.py
python step2_cluster.py
```

## Dependencies
- [NumPy](http://www.numpy.org): normal computing v-1.17.2 
- [Matplotlib](http://matplotlib.sourceforge.net/): For plotting data to choose threshold v-3.1.1
- [Scikit-Learn](https://github.com/scikit-learn/scikit-learn): use for mds to plot result v-0.21.3

## Reference
- [Clustering by fast search and find of density peaks](http://www.sciencemag.org/content/344/6191/1492.full)

