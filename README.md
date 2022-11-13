# Quora-Duplicate-Question-Pairs-Identification

![Quora Duplicate Questions Detection](https://learnopencv.com/wp-content/uploads/2018/12/Quora-Post-Image.jpg)
![Quora Duplicate Questions Detection](https://miro.medium.com/max/1400/1*EYrwCbBDUAbx5dKPjJIIIg.png)
![Quora Duplicate Questions Detection](https://packt-type-cloud.s3.amazonaws.com/uploads/sites/2489/2018/04/715e07d7-e420-4cdf-a0b2-550e847304da.png)

## Problem Statement

Quora is a fantastic site where queries are posed, addressed, followed, and altered by online businesses. As a result, people are better able to grasp the world and benefit from the other's knowledge. It's not surprising that many questions have similar wording since there are about 100 million visitors to Quora each month. Asking its users to write an answer to the same question is not a better strategy for Quora. Therefore, if there is a system that can recognize whether a new question is similar to ones that have already been addressed, that would be ideal.

So, determining if a pair of questions is duplicated or not is our problem statement. 

## Dataset Description

The goal of this project is to predict which of the provided pairs of questions contain two questions with the same meaning. The ground truth is the set of labels that have been supplied by human experts. The ground truth labels are inherently subjective, as the true meaning of sentences can never be known with certainty. Human labeling is also a 'noisy' process, and reasonable people will disagree. As a result, the ground truth labels on this dataset should be taken to be 'informed' but not 100% accurate, and may include incorrect labeling. We believe the labels, on the whole, to represent a reasonable consensus, but this may often not be true on a case by case basis for individual items in the dataset.

## Data fields

    id - the id of a training set question pair
    qid1, qid2 - unique ids of each question (only available in train.csv)
    question1, question2 - the full text of each question
    is_duplicate - the target variable, set to 1 if question1 and question2 have essentially the same meaning, and 0 otherwise.

## Python Libraries Used

<ul>
  <li>Numpy</li>
  <li>Pandas</li>
  <li>Seaborn</li>
  <li>Matplotlib</li>
  <li>NLTK</li>
  <li>XGBoost</li>
  <li>CatBoost</li>
  <li>Scikit-learn</li>
</ul>
