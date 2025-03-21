# Applied ML for Scientists and Engineers

While most AI research focuses on applying deep learning to unstructured data such as text and images, many real-world AI applications involve applying machine learning to structured, tabular data. This course's objective is to provide students with practical, hands-on experience with state-of-the-art machine learning tools widely used in industry to solve science and engineering problems based on structured, tabular data.  

On completion of this course students will:  

* Implement complete machine learning pipelines using Scikit-Learn to solve supervised and unsupervised learning problems with a variety of techniques; 
* Understand various failure modes that can arise when training machine learning pipelines and be able to recognize and troubleshoot these failure modes in their own work; 
* Develop, train, and deploy complete machine learning applications.This course covers the basic theory behind ML algorithms but the majority of the focus is on hands-on examples using [Scikit Learn](https://scikit-learn.org/stable/index.html).

## Learning Objectives

### Capabilities (knowledge & understanding): 
 
* Understand the distinct types of machine learning problems that exist in practice; understand the basic parts of typical machine learning solutions. 
* Understand the limitations of linear models; understand the trade-offs of various non-linear models. 
* Understand failure modes that are encountered when building machine learning pipelines. 
 
### Competencies (skills):  
 
* Be able to implement a complete machine learning workflow using Scikit-Learn to solve supervised and unsupervised learning problems using linear models.  
* Train, validate, and test machine learning pipelines using non-linear models with [Scikit Learn](https://scikit-learn.org/stable/index.html). 
* Analyze and ‘troubleshoot’ failure modes in their own work. 

## Lecture Materials

### Week 1

#### The Machine Learning Landscape ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/EWo8HoVvDINJoDmQZzRbdeMBrUru9WCO6-6ZMJarjQb9Yg?e=6mjSEU))

The initial lecture provides a high-level overview of the machine learning (ML) landscape and addresses the following questions.  
 
* What is ML? 
* Why use ML? 
* What are the several types of ML systems? 
* What are some of the main challenges of applying ML in practice? 
 
**Required reading:**

Required readings are expected to be completed *before* arriving in class.
 
* Chapter 1 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 1 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/)

### Week 2

#### End-to-End Machine Learning Project ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/EaAqGRo1FpJLnx8mxyhpY3IBVnnCIZP-V10MuIvP9vr1-A?e=lM6SjS)) 
 
In this lecture, we will define and discuss the steps for any applied ML project by working through an end-to-end ML project using a real-world dataset as a group.  
 
1. Framing the problem 
2. Getting the data 
3. Exploratory data analysis 
4. Preparing the data for ML algorithms 
5. Selecting promising ML algorithms and training 
6. Tuning ML algorithms for performance 
7. Deploying tuned ML algorithms 
 
The goal is to provide students with a roadmap or checklist that they can apply to most any ML project. Subsequent lectures will focus on various steps defined above.  
 
**Required reading:**

* Chapter 2 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Appendix A of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| Get the Data | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2a.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2a.ipynb) |
| Exploratory Analysis | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2b.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2b.ipynb) |
| Preparing Data for ML | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2c.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2c.ipynb) |
| Training Models | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2d.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2d.ipynb) |
| Fine-tuning Models | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2e.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-2e.ipynb) |

### Week 3

#### Classification ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/Ef0qvvwoIQNCgt0KzUbpJDUB5j27rXuuMwEvXpKKBL89zQ?e=DNuiOX))
 
In this lecture we will cover the key ideas of one of the major learning tasks performed by supervised ML systems: classification.  
 
* Differentiate between several types of classification: binary and multi-class classification; multi-output and multi-label classification; soft vs hard classification. 
* Selecting an appropriate performance metric is a critical early step in developing a classification system.  
* Discuss the importance of calibrating predicted class probabilities. 
 
**Required reading:**

* Chapter 3 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
* Chapter 2 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/) 

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| Binary Classification | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3a.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3a.ipynb) |
| Performance Metrics | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3b.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3b.ipynb) |
| Multiclass Classification | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3c.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3c.ipynb) |
| Multilabel Classification | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3d.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3d.ipynb) |
| Multioutput Classification | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3e.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3e.ipynb) |
| Calibration | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3f.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3f.ipynb) |
| End-to-end Classification | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3g.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-3g.ipynb) |

### Week 4

#### Training Models, part I ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/EVGb6b2kAABAuSkrAJd5Ps0BPlT3KlrCVOilkMN0K_stKg?e=71LcoN)) 
 
This lecture provides an in-depth discussion of the process of training ML models using stochastic gradient descent. The process will be illustrated using various linear regression models. 
 
* Linear regression 
* Polynomial regression 
* Regularized linear regression (Ridge, LASSO, and ElasticNet). 
 
**Required reading:**

* Chapter 4 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 2 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/) 

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| Linear Regression with NumPy | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1a.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1a.ipynb) |
| Linear Regression with Scikit-Learn |  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1b.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1b.ipynb) |
| Data Preprocessing |  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1c.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1c.ipynb) |
| Polynomial Regression |  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1d.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1d.ipynb) |
| Regularized Linear Regression |  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1e.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-1e.ipynb) |

#### Trainging Models, part II ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/EVGb6b2kAABAuSkrAJd5Ps0BPlT3KlrCVOilkMN0K_stKg?e=71LcoN)) 
 
Review the key ideas presented in the previous lecture but this time using logistic and softmax regression (with and without regularization) to illustrate the training process.

**Required reading:**

* Chapter 4 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 2 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/) 

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| Logistic Regression with Numpy | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-2a.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-2a.ipynb) |
| Softmax Regression with Numpy | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-2b.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-2b.ipynb) |
| Logistic Regression with Scikit-Learn | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-2c.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-2c.ipynb) |
| Softmax Regression with Scikit-Learn | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-2d.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-4-part-2d.ipynb) |

### Week 5

#### Support Vector Machines ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/EYVl3sggch1HqEKHZO8O9t4BpXwFB3NCMCM0tLue6H0T8Q?e=OVJ6pP)) 
 
In this lecture we will cover both linear and non-linear support vector machines (SVMs) and see how to apply these algorithms to solve both classification and regression tasks.  
 
**Required reading:**

* Chapter 5 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 3 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/)

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| SVMs (Classification) | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-5a.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-5a.ipynb)

## Week 6

#### Decision Trees ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/ERMDJZ6MYP9DrxSm2EIbjA8BTGg9Z3-LG5KB4JMyVUFDNQ?e=9RrsdZ)) 
 
Tree-based models such as random forests and gradient-boosted trees are state-of-the-art ML methods for tabular data. But before we can cover these state-of-the-art methods, we need to discuss decision trees in detail. This lecture will focus on the key ideas behind decision tree implementation and how to tune decision trees to avoid overfitting. 
 
**Required reading:**

* Chapter 6 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 3 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/) 

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| Decision Trees (Classification) | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-7a.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-7a.ipynb) |
| Decision Trees (Regression) | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-7b.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-7b.ipynb) |

### Week 7

#### Ensemble Methods, part I ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/EfOwBOSsVVFBl8GkX23wsHwB49JB0jCao1IZbIIiBT_6cw?e=j1Jyzo)) 
 
Ensemble, tree-based models such as random forests and gradient-boosted trees are state-of-the-art ML methods for tabular data. In this lecture we will cover these approaches in detail. We will discuss the key ideas behind ensemble methods such as voting, bagging, and pasting and how to implement these approaches in practice to solve classification and regression tasks via random forests. 
 
**Required reading:**

* Chapter 7 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 3 and 7 of ML with PyTorch and Sklearn 

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| Ensemble Methods, part I |  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-8-part-1a.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-8-part-1a.ipynb) |

### Week 8

#### Ensemble Methods, part II ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/EZgXMV7npzlKrfWH1A8v2loBMPlAkYLOFpD6iOBw27A81w?e=Ni0dY0))
 
This lecture continues covering tree-based ensemble techniques with an in-depth discussion of gradient boosted trees. Gradient boosted trees are the most widely used ML algorithms in industry and continue to deliver state-of-the-art performance on tabular data problems and time-series forecasting problems. Two popular implementations of gradient boosted trees will be discussed: XGBoost and CatBoost. 
 
**Required reading:**

* Chapter 7 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 3 and [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/)

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| Boosting Methods (Scikit-Learn) |  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-8-part-2a.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-8-part-2a.ipynb) |
| Boosting Methods (CatBoost, LightGBM, XGBoost) |  [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-8-part-2b.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/lecture-8-part-2b.ipynb) |

### Week 9

#### Dimensionality Reduction ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/EbBg__P2wu5Gp4BZ3iMcv-0BlVAa3j2SWz7rJjRj5udBZQ?e=IDyQTX)) 
 
Many ML systems suffer from the curse of dimensionality: the training time of many ML systems increases rapidly as the number of features in the dataset increases. This lecture covers the key ideas of dimensionality reduction and various algorithms for performing dimensionality reduction such as Principal Components Analysis (PCA), Locally Linear Embedding (LLE), et al. Tradeoffs between the various methods will be discussed. 
 
**Required reading:**

* Chapter 8 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 5 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/)

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| Dimensionality Reduction | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/module-3-lecture-1.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/module-3-lecture-1.ipynb)

### Week 10

#### Unsupervised Learning Techniques ([Slides](https://kaust-my.sharepoint.com/:p:/g/personal/pughdr_kaust_edu_sa/EV1cUHcyAwtHqWsr4IdidxUBRclSLycFCPQusvkHJ48XdA?e=X034dA)) 
 
This lecture will cover the key ideas behind unsupervised learning techniques and will include an in-depth discussion of the K-means algorithm. Other approaches to unsupervised learning will be discussed such as DBSCAN, and Gaussian Mixture Models (GMMs).  
 
**Required reading:**

* Chapter 9 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 10 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/)

| **Tutorial** | **Open in Google Colab** | **Open in Kaggle** |
|--------------|:------------------------:|:------------------:|
| Unsupervised Learning | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/module-3-lecture-2.ipynb) | [![Kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://kaggle.com/kernels/welcome?src=https://github.com/davidrpugh/machine-learning-for-tabular-data/blob/main/notebooks/module-3-lecture-2.ipynb)

### Week 11

#### Introduction to Artificial Neural Networks (Slides)
 
While neural networks are not (yet?) state-of-the-art approach for most tabular data problems, an understanding of the key ideas of basic neural networks such as the multi-layer perceptron (MLP) is important. We will learn how to implement linear and logistic regression using MLPs as well as how to apply MLPs to tabular data problems. 
 
**Required reading:**

* Chapter 10 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 11 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/)

### Week 12

#### Fundamentals for DNN training and validation (Slides)
 
**Required reading:**

* Chapter 11 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 12 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/)

### Week 13

#### Optimizers, learning rates and batch sizes (Slides)
 
**Required reading:**

* Chapter 11 of [Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/) 
* Chapter 12 of [ML with PyTorch and Sklearn](https://www.oreilly.com/library/view/machine-learning-with/9781801819312/)

### Week 14

#### Deploying machine learning pipelines, part I (Slides) 
 
A trained ML system that is never deployed is one of little practical value. Deployment of ML systems presents some unique challenges that are rarely discussed in university courses. We will spend the last lecture of the course learning how to deploy ML algorithms culminating with students learning to embed and deploy their own ML systems as Gradio applications on HuggingFace Spaces. 

## Assessment

Student performance on the course will be assessed through participation in a Kaggle classroom competition. 

# Repository Organization

Repository organization is based on ideas from [_Good Enough Practices for Scientific Computing_](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1005510).

1. Put each project in its own directory, which is named after the project.
2. Put external scripts or compiled programs in the `bin` directory.
3. Put raw data and metadata in a `data` directory.
4. Put text documents associated with the project in the `doc` directory.
5. Put all Docker related files in the `docker` directory.
6. Install the Conda environment into an `env` directory. 
7. Put all notebooks in the `notebooks` directory.
8. Put files generated during cleanup and analysis in a `results` directory.
9. Put project source code in the `src` directory.
10. Name all files to reflect their content or function.

## Building the Conda environment

After adding any necessary dependencies that should be downloaded via `conda` to the 
`environment.yml` file and any dependencies that should be downloaded via `pip` to the 
`requirements.txt` file you create the Conda environment in a sub-directory `./env`of your project 
directory by running the following commands.

```bash
export ENV_PREFIX=$PWD/env
mamba env create --prefix $ENV_PREFIX --file environment.yml --force
```

Once the new environment has been created you can activate the environment with the following 
command.

```bash
conda activate $ENV_PREFIX
```

Note that the `ENV_PREFIX` directory is *not* under version control as it can always be re-created as 
necessary.

For your convenience these commands have been combined in a shell script `./bin/create-conda-env.sh`. 
Running the shell script will create the Conda environment, activate the Conda environment, and build 
JupyterLab with any additional extensions. The script should be run from the project root directory 
as follows. 

```bash
./bin/create-conda-env.sh
```

### Ibex

The most efficient way to build Conda environments on Ibex is to launch the environment creation script 
as a job on the debug partition via Slurm. For your convenience a Slurm job script 
`./bin/create-conda-env.sbatch` is included. The script should be run from the project root directory 
as follows.

```bash
sbatch ./bin/create-conda-env.sbatch
```

### Listing the full contents of the Conda environment

The list of explicit dependencies for the project are listed in the `environment.yml` file. To see 
the full lost of packages installed into the environment run the following command.

```bash
conda list --prefix $ENV_PREFIX
```

### Updating the Conda environment

If you add (remove) dependencies to (from) the `environment.yml` file or the `requirements.txt` file 
after the environment has already been created, then you can re-create the environment with the 
following command.

```bash
$ mamba env create --prefix $ENV_PREFIX --file environment.yml --force
```

## Using Docker

In order to build Docker images for your project and run containers with GPU acceleration you will 
need to install 
[Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/), 
[Docker Compose](https://docs.docker.com/compose/install/) and the 
[NVIDIA Docker runtime](https://github.com/NVIDIA/nvidia-docker).

Detailed instructions for using Docker to build and image and launch containers can be found in 
the `docker/README.md`.
