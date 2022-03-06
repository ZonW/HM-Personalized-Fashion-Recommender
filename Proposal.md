## 1. Introduction
Online shopping offers shoppers an extensive selection of products to browse through. But with too many choices, customers might not quickly find what interests them or what they are looking for, and ultimately, they might not make a purchase. To enhance the shopping experience, product recommendations are key. More importantly, helping customers make the right choices also has a positive implications for sustainability, as it reduces returns, and thereby minimizes emissions from transportation. This project is initiated by H&M as a Kaggle challenge to provide product recommendations based on previous purchases. For this project, we are given the purchase history of customers across time, along with supporting customer and product metadata. Our goal is to predict what articles each customer will purchase in the 7-day period immediately after the training data end date.  
## 2. Preliminary Literature Review    
A comprehensive review and classification of existing works on deep learning recommender models was performed by the article "Deep Learning Based Recommender System: A Survey and New Perspectives". The author classified deep learning based recommendation systems(RS) to two catagories: RS with neural building blocks and RS with deep hybrid models. The catagories are composed of different models like MLP, AE, RNN, CNN, GAN and RNN+CNN, AE+CNN respectively.     
![image](https://user-images.githubusercontent.com/95121369/156247844-1b2cb391-087d-4faa-8eda-7bbbb0c64dc7.png)  
The autor also discussed challenges of current RS researches and proposed future research directions. The propsed future research direction includes joint representation learning, more explainable models for both user and researchers, RS models with more layers, machine reasoning, etc.  
To the end, the author urged RS researching community to establish a standard dataset and hidden/blinded test set for better model evaluation. According to the study, the baseline and dataset of RS is not as standarized as the CV/NLP community, which will create an inconsistent reporting of scores, with each autor using his/her own dataset and evaluation method. Thus, there's seemingly no consensus on the general ranking of the models.  

## 3. Objectives and expected contributions  
We hereby posit two research questions, formalized in the following, and by leveraging a large H&M transactions and product dataset. We provide empirical evidence as well as theoretical grounding to answer these questions:

- Research Question 1 (RQ1): Using latest deep learning recommendation models to complete the competition.

- Research Question 2 (RQ2): Building a grade algorithm to exam our deep learning model based on competition evaluation.

We expect this work can make the following contributions:

- We provide a machine learning approach to identify customers shopping habits.

## 4. Methodology  
In this paper, we will use the dataset H&M provided, the transations from 2018/09/20 to 2020/09/21; the product with price and simple descriptions; 100k images of products.

## 5. Brief Project Schedule  
 
| Task                    | Assignee |
| ----------------------- | -------- |
| Data preprocessing      | a        |
| Constructing models     | a        |
| Model training          | a        |
| Performance evaluation  | a        |
| Research report writing | a        |

## 6. Links and references  
Project: https://github.com/ZonW/HM-Personalized-Fashion-Recommender  
Kaggle: https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations  
Reference: https://arxiv.org/abs/1707.07435
