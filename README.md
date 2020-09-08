# Deep-Learning-specialization

This repository gathers all programming exercices from the **Deep Learning specialization** course available on Coursera (https://www.coursera.org/specializations/deep-learning) and taught by the well famous Andrew-Ng, ex chief-scientist at Baidu and AI researcher.  

## Stack

Those exercices have been done in **Python** using several data science libraries and deep learning frameworks such as :  

*  **Numpy**, mostly for matrix/vectors computations or basic mathematical operations. Sometimes it is used to build Neural Networks (NN) from scratch in those exercices. Adding to that, **Matplotlib** and **Scipy** are often used. 
*  **Tensorflow** 1.14, in low level API in order to have full control in building production NN models. 
*  **Keras** 2.2.4, high level API which allows to iterate quicker by building NN models much faster. 

## How to download all Coursera reference files?

You will need extra files if you want to work on those **jupyter notebooks in local** (often need to add helper functions, images, etc.).  
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
