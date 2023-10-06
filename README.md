# Content
The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis.[1] It is sometimes called Anderson's Iris data set because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species.[2] Two of the three species were collected in the Gaspé Peninsula "all from the same pasture, and picked on the same day and measured at the same time by the same person with the same apparatus".[3]

The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals, in centimetres. Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other.



# KNN-algorithm in the iris jupyter notebook

KNN algorithm applied on IRIS dataset with accuracy 96%
after reading data . it had been cleand from Duplicates (found 3).
no null values had been found.
data had been visualaized in gird (2,2) all columns with the target one (species).
data had been splited to (X,y) y is the target column.
then (X,y) had been splited to (X_train , X_test , y_train , y_test).
then (X_train,y_train) splited to (X_train , X_val , y_train , y_val).
the (X_train,X_test,X_val) had been normalaized to numbers between (0 and 1).
the (y_train,y_test,y_val) ==> the target section. had been encoded .
the (KNN Classifier) mdel used to train the data see (https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html).
the model had been tuned and the (K = 5) untel the accuracy_score became (96%).
