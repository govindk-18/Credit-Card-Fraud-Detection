In this notebook, we will explore the data through initial EDA with some visualizations. Then we will hit the main point of the notebook, which is to explore ways to handle imbalanced data. We will use two methods:

Using the weights parameters in Sci-Kit Learn classifiers
Over and Undersampling (to be developed in the next version)
Finally, we will quantify and illustrate the effects of the trade off between True Positive Rate and False Positive Rate using ROC and Precision/Recall (PR) curves, and disucss why the popular ROC curve should not be used on highly imbalanced dataset (or in general, why I prefer PR curves over ROC).
