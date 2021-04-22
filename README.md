# CISC-372-Spam-Email-Filter
We are the students from Queen's University and tries to figure out the solution to spam emails problem.
Solutions to the problem includes lazy learning methods: KNN Classifier, and eager learning methods: Naive Bayes Classifier, SVM Classifier , CNN and RNN, pre-trained word embeddings(GloVe) is also applied to see if there would be any improvements. The dataset is on the 'release' tag which origins from the Enron-Spam Dataset：http://www2.aueb.gr/users/ion/data/enron-spam/       We aggregate the data from 6 sets and form a whole with 36609 mails labelled with 0,1, represent ham or spam, repectievly.
20% of the data is sampled as testing set, without replacement, both train and testing set have similar distribution of ham and spam mails(around 55%/45%). The accuracy of each model would be evaluated with some further discussions.
MergeDataset.ipynb includes the code of how we merge 6 datasets, drop empty entries, retain the distribution of 2 classes.
spam_email_classifiers.ipynb is the code that include 6 models, SVM, KNN, Naive Bayes, CNN, RNN, RNN+GloVe



