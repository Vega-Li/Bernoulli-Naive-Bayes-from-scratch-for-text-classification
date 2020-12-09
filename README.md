# Text Classification with Machine Learning Methods

**Please make sure the training file and test file have been uploaded to the Colab before you run the code.**

### 1. Bernoulli Naïve Bayes from Scratch

3. Run the main function with the format (BNB, 'train.csv', 'test.csv', numFolds, feature_num)).

   ​	1. 'BNB' stands for the method of 'Bernoulli Naïve Bayes'.
   
   2. 'numFolds' is the number of folds of corss validation. 
   
   3. 'feature_num' is the number of features you want to use with the model.

### 2. Different Models from Sklearn Package

1. Run the main function with the format (model, 'train.csv', 'test.csv', numFolds, feature_num)).

   1. Choose the model you would like to use from the 'Models' section. MLP = MLPClassifier(), LSVC = svm.LinearSVC(), GNB = naive_bayes.GaussianNB(), MNB = naive_bayes.MultinomialNB(), LRC = LogisticRegression(), KNN = neighbors.KNeighborsClassifier(), DTC = tree.DecisionTreeClassifier(), RDTC = RandomForestClassifier(), BDTC = BaggingClassifier(). The hyper-parameters of different models have already been set.
   2. 'numFolds' is the number of folds of corss validation. 

   3. 'feature_num' is the number of features you want to use with the model.

