# DeepGlut
![Author](https://img.shields.io/badge/author-urmisen-orange)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/urmisen/Thesis)
[![Stars](https://img.shields.io/github/stars/urmisen/Thesis.svg?style=social)](https://github.com/urmisen/Thesis/stargazers)

# Author: Urmi Sen

Department of Computer Science & Engineering, </br>
Rajshahi University of Engineering & Technology (RUET) </br>
Website: https://urmisen.github.io/ </br>
Linkedin: https://www.linkedin.com/in/urmi-sen-78a821149/ </br>
Email: urmisen1202@gmail.com <br>

<hr>

## Project Description
This study is about the Post Translational Modifications(PTM) about proteins. Here we are  trying to identify Acetylation sites in proteins, where Acetylation is a kind of Lysine Post Translational Modifications. This is the code repository of my paper entitled "DeepGlut: A Deep Learning Framework for Prediction of Glutarylation Sites in Proteins".

## Aurhos
Urmi Sen and Md. Al Mehedi Hasan

## Methodology
### Dataset Description:

![Alt Text](https://github.com/urmisen/DeepGlut/blob/master/data_des.PNG)

The dataset in given in this repository, but to work with the latest dataset please download dataset from the following links. <br>
1. http://plmd.biocuckoo.org/download.php
2. https://dx.doi.org/10.1016/j.ab.2018.04.005

### Data Imbalanced Ratio:

imbalanced ratio = 3498/590
                 = 5.93 : 1

![Alt Text](https://github.com/urmisen/DeepGlut/blob/master/ratio.PNG)

## Feature Construction
### One-hot Encoding
![Alt Text](https://github.com/urmisen/DeepGlut/blob/master/one_hot.PNG)

## Model Implementation
### Convolutional Neural network(CNN)
![Alt Text](https://github.com/urmisen/DeepGlut/blob/master/model.PNG)

## Classification
### whole Classification Process
![Alt Text](https://github.com/urmisen/DeepGlut/blob/master/classification.PNG)
## Results
####  performance measurement on independent test set

|   __Accuracy__   |   __Precision__   |   __Sensitivity__   |    __AUC__    |
|------------------|-------------------|---------------------|---------------|
| 0.7254           | 0.76              | 0.67                | 0.7585        |

####  performance measurement for 10 fold cross validation

|   __Accuracy__   |   __Precision__   |   __Sensitivity__   |    __AUC__    |
|------------------|-------------------|---------------------|---------------|
| 0.7616           | 0.7267            | 0.8494              | 0.8383        |



## Conclusion:
If you like this repository and please put a star. This will keep me motivated to work more on these. 
