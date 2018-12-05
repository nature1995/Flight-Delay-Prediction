# Flight-Delay-Prediction

This repo is 2018 Fall EE608 Final Project: Flight Delay Prediction

### Team Member: 

Ziran Gong zgong5@stevens.edu Yuqing Luo yluo27@stevens.edu Bowen Li bli50@stevens.edu

### Dataset

Due to the size, I upload all the dataset to google drive.  
In this project, we use part of data which is the first month.  
We use the first 3 week to predick the last week in this month.

https://drive.google.com/drive/folders/1LDDwiQW-74P5NFDTEpCAfETxSIBNu7cC?usp=sharing

### Web Page

https://sites.google.com/view/ee608

### Install

#### Step1:

1.1 Install Anaconda

<div class="homepage__button_row">
  <a href="https://www.anaconda.com/download/#windows">Windows</a>&nbsp  
  <a href="https://www.anaconda.com/download/#macos">macOS</a>&nbsp  
  <a href="https://www.anaconda.com/download/#linux">Linux</a>&nbsp  
</div><br>

1.2 Create Python3.6 environment
```
conda create -n ee608 python=3.6
```
#### Step2:

2.1 Install Jupyter Notebook & JupyterLab 

2.2 Install python package 

Search and apply the package name below on Anaconda 

**Or**

Using Anaconda Prompt
```sh
conda install package-name
```
* visualization: `matplolib, seaborn, basemap`
* data manipulation: `pandas, numpy`
* modeling: `scikit-learn, scipy`

2.3 Install other package

Search and apply the package name below on Anaconda

* `pydot, python-graphviz, pillow`

#### Step3:

3.1 Start JupyterLab  

### Run code  
**Flight delay prediction**

Use `Shift + Enter` to run code step by step.  
Then, you can get the result of each process in the middle of the operation.  
After run it to the final step, you can get the flight delay prediction result for two model.


**Airlines Rank & Recommandation**

Use `Shift + Enter` to run code step by step.   
Then, you can get the results in the data processing process.  
Finally, you can get the rank histogram and the recommandation.

### Conclusion

* Data analysis algorithms are applied to predict flight delay.

* Airlines are ranked  for recommendation purpose. 

* After modeling with two methods, model 2 with ridge regression and regularization is the wining method with MSE (54.99).

* Include almost all the factors to rank airline for users.






