## Supervised Machine Learning challenge on an imbalanced dataset

*Keywords:*

**Imbalanced dataset, XGBClassifier**

*Forewords:*

This script has been written during a Kaggle competition at the [Propulsion Academy](https://propulsion.academy/) during the Data Science Bootcamp 2020 (you can check the final project presentation of the student batch [here](https://drive.google.com/file/d/1WYcEVMIcYaRl6J4hg43KhBM5hvwHtYui/view?usp=sharing)). It was co-written with Chris Riccione.

*Dataset:*

The dataset contains two CSV files ‘features’ and ‘target’. Each row in the ‘features’ belongs to a ‘measurement’ and each column represents a ‘feature’. For each row in the ‘features’ there is a corresponding class label in ‘target’. Row-numbers are considered as keys. A dataset named ‘train’ was used to implement the models. The results obtained from the predictions of the Machine Learning models were submitted using a test dataset.

*Challenge:*

- Explore the data. Identify anything interest that is worth noting from the data?
- Define a set of possible classifiers and show which one performs best. Keep in mind the problem of overfitting.
- Using feature selection try to reduce the number of features. In the dataset there are over 120 features. Find the good ones for the classifier.

*Note on the data:*

The data exploration revealed that the dataset was **imbalanced**. The key in this challenge was to downsample the groups containing the most frequent label to prevent **overfitting*.
