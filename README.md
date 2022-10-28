# Applying Naive Bayes Algorithm on DonorsChoose Dataset.

Dataset link: https://www.kaggle.com/competitions/donorschoose-application-screening/data


In the .ipynb I've applied Naive Bayes Classifier on the DonorsChoose Dataset. Categorical features are encoded using one hot encoding, bag of words and tfidf.
The performance of the model is measured via various metrics like confusion matrix, ROC and AUC score.


About Dataset:


DonorsChoose.org receives hundreds of thousands of project proposals each year for classroom projects in need of funding. Right now, a large number of volunteers is needed to manually screen each submission before it's approved to be posted on the DonorsChoose.org website.

Next year, DonorsChoose.org expects to receive close to 500,000 project proposals. As a result, there are three main problems they need to solve:

1. How to scale current manual processes and resources to screen 500,000 projects so that they can be posted as quickly and as efficiently as possible.
2. How to increase the consistency of project vetting across different volunteers to improve the experience for teachers.
3. How to focus volunteer time on the applications that need the most assistance.

The goal of this kaggle competition is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved, using the text of project descriptions as well as additional metadata about the project, teacher, and school. DonorsChoose.org can then use this information to identify projects most likely to need further review before approval.
