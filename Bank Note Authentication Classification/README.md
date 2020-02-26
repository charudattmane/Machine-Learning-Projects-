In this project, Banknote Authentication Dataset is used. Three algorothms are used on this dataset to measure which algorithm gives better accuracy. The algorithms used on the dataset are :

1. SVM-Support Vector Machine : In machine learning, support-vector machines (SVMs, also support-vector networks) are supervised learning models with associated learning algorithms that analyze data used for classification and regression analysis. Given a set of training examples, each marked as belonging to one or the other of two categories, an SVM training algorithm builds a model that assigns new examples to one category or the other, making it a non-probabilistic binary linear classifier (although methods such as Platt scaling exist to use SVM in a probabilistic classification setting).

2. Logistic Regression : Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable, although many more complex extensions exist. In regression analysis, logistic regression(or logit regression) is estimating the parameters of a logistic model (a form of binary regression).

3. Decision Tree : A decision tree is a decision support tool that uses a tree-like graph or model of decisions and their possible consequences, including chance event outcomes, resource costs, and utility. It is one way to display an algorithm that only contains conditional control statements.

Here we were needed to find whether the banknote is real or fake and based on different parameters we estimated the result.

Data Set Information:
Data were extracted from images that were taken from genuine and forged banknote-like
specimens. For digitization, an industrial camera usually used for print inspection was used. The
final images have 400x 400 pixels. Due to the object lens and distance to the investigated object
gray-scale pictures with a resolution of about 660 dpi were gained. Wavelet Transform tool were
used to extract features from images.

Attribute Information:
The data file banknote_authentication.csv is the source of information for the classification
problem. The number of instances (rows) in the data set is 1372, and the number of variables 
(columns) is 5. In that way, this problem has the following variables:

1. variance_of_wavelet_transformed, used as input.
2. skewness_of_wavelet_transformed, used as input.
3. curtosis_of_wavelet_transformed, used as input.
4. entropy_of_image, used as input.
5. class, used as target. It can only have two values: 0 (false) or 1 (true).

The instances are divided into training, selection and testing subsets. There are 824 instances for 
training (60%), 274 instances for selection (20%) and 274 instances for testing (20%).
