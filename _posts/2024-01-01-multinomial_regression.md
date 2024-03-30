---
title: Multinomial Logical Regression - Python
layout: post
post-image: "https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/Confusion_matrix.png"
description: This project embarks on a thorough sentiment analysis journey using Python, focusing on an Amazon book dataset. The endeavor commences by evaluating the accuracy of the multinomial Regression model, supported by a meticulous presentation of the Confusion Matrix, enriching the analysis with profound insights into the predictive capabilities.This succinct portrayal encapsulates the pivotal stages and accomplishments within the sentiment analysis project, leveraging the expansive Amazon book dataset.
tags:
- jekyll
- informative
- technology
---

Furthermore, the analysis is enriched with profound insights into the predictive capabilities of the Multinomial Regression model. This involves examining the precision, recall, F1-score, and other performance metrics derived from the Confusion Matrix. These metrics offer valuable insights into the model's ability to correctly identify positive and negative sentiment in the book reviews.

{:target="blank"}
###### Source Code : [`Jekyll Docs`](https://jekyllrb.com/docs/)

## Multinomial Regression
#### Step 1: Identifying Variables

The first step involved identifying the variables essential for the multinomial regression analysis. This includes selecting predictor variables (features) that could potentially influence the rating of books, as well as the target variable, which in this case is the book rating.

#### Step 2: Data Preparation

Data preparation was crucial for ensuring the quality and suitability of the dataset for analysis. This included removing stopwords and punctuation from the text data to clean and streamline the text for analysis. Additionally, TF/IDF vectorization was applied to convert the text data into numerical vectors, which could be used as input for the regression model.

#### Step 3: Datasets

The dataset was divided into two subsets: the training dataset and the test dataset. The training dataset was used to train the multinomial regression model, while the test dataset was reserved for evaluating the model's performance.

#### Step 4: Predictive Analysis

In this step, the multinomial regression model was trained using the training dataset. The model learned the relationships between the predictor variables and the book ratings. Once trained, the model was used to predict the ratings of books in the test dataset.
<li> True Positive (TP): Identified 92633 instances correctly. </li>
<li> False Positive (FP): Totalled 37315, comprising errors in positive prediction.</li>
<li>False Negative (FN): Totalled 7317, indicating missed positive identifications.</li>
<li>These metrics collectively represent the performance of the classification model in predicting positive instances.</li>
<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/conf_matrix_calc.png" width="480" height="259" frameborder="0"></image>
<li>Precision: 71% of positive predictions were correct.</li>
<li>Recall: 93% of actual positives were identified.</li>
<li>F1 Score: Balanced at 0.81, considering precision and recall.</li>
<li>Overall Accuracy: Classified 65% of instances correctly.</li>
<li>Support: Dataset contains 99950 instances, with a total test sample of 169229.</li>

<image src="https://raw.githubusercontent.com/hemabhaskar/portfolio/gh-pages/assets/images/class_report.png" width="480" height="1500" frameborder="0"></image>

#### Step 5: Model Evaluation

The performance of the multinomial regression model was evaluated using various metrics, including the classification report and confusion matrix. These metrics provided insights into the model's precision, recall, and overall accuracy in predicting book ratings.

#### Step 6: Overall Findings

Upon evaluating the model, it was observed that the model performed well in predicting books with a 5-star rating, achieving a precision of 71%. However, approximately 29% of books that were not actually rated 5 stars were incorrectly classified as such. The model also demonstrated a high recall rate of 93%, indicating that it effectively captured a large proportion of actual 5-star rated books. Overall, the model showed promise in identifying 5-star rated books but may not be as accurate for predicting other ratings.