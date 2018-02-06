# Authorship Identification

### Task
Authorship identification is process of identifying an author from a given piece of
text. The importance of this problem has recently received a lot of attention from the
information retrieval, text mining, machine learning and NLP researchers. It is very
well suited for supervised learning problem. It has a wide application like identifying
anonymous authors on online discussion forums and plagiarism detection. In this
assignment, you are given the training and testing data for some group of authors
with their pen crafted piece of text. You need to train a model for classification. You
are free to define a feature space for this task. Obviously Naive Bayes (NB) can be
used as a classifier for this task, but you are free to select your classifier as long as
you understand the working of it. Class specific feature selection is a trivial approach
in such cases.

### Dataset
The dataset contains piece of text from three authors of fictions, Edgar Allan Poe,
HP Lovecraft and Mary Shelley. The label dataset contains 19K examples from these
three. You need to train a classifier such that when given a piece of text, it can predict
the author. Obviously, there are three classes. It is a multi-class classification
problem. The train excel file contains the data. You need to split the data into 70/30
and use 30% data as testing set. The evaluation will be done on this set.
