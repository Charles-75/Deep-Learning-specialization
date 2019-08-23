# Deep-Learning-specialization

This repository gathers all programming exercices from the Deep Learning specialization course available on Coursera (https://www.coursera.org/specializations/deep-learning) and taught by the well famous Andrew-Ng, ex chief-scientist at Baidu and AI researcher.  
  
Those exercices have been done in Python using several data science libraries and frameworks such as numpy for matrix/vectors computations and tensorflow to build production neural network models.  

## How to download all Coursera reference files?

You will need extra files if you want to work on those jupyter notebooks in local (usually some helper functions, images, etc.).  
Follow the process below to retrieve it : 

1. Open a online jupyter notebook, and then click `File > Open ...`
2. Launch new terminal instance: `New > Terminal`
3. tarball the folder:
```shell
tar czvhf coursera.tar.gz *
```
3. a. split it (usually this file might be too large for your instance to allow download)
```shell
split -b 100M -d coursera.tar.gz coursera.
```
4. Go to view in 2.
5. Download the file(s) by selecting it (square) then clicking on `Download`.

6. if you split the file, join them:
```shell
cat coursera.* > coursera.tar.gz
```
7. Extract files:
```shell
tar xzvf coursera.tar.gz
```
