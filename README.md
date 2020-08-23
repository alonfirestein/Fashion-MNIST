# Fashion-MNIST

### As part of a first year university school project, we were tasked with Fashion MNIST Classification using different ML models and dimension reduction using PCA.

The Fashion-MNIST clothing classification problem is a new standard dataset used in computer vision and deep learning. It's a dataset of Zalando’s article images consisting of a training set of 60,000 examples and a test set of 10,000 examples. Each example is a 28×28 grayscale image, associated with a label from 10 classes. Fashion-MNIST is intended to serve as a direct drop-in replacement of the original MNIST dataset for benchmarking machine learning algorithms.
We used the Fashion MNIST given that the original MNIST is too easy and overused.

##### The 10 classes representing each type of clothing are:

0. T-shirt/top
1. Trouser
2. Pullover
3. Dress
4. Coat
5. Sandal
6. Shirt
7. Sneaker
8. Bag
9. Ankle boot



Using different ML models and using PCA for the first time, these were the final results:

### Model Comparisson Accuracy Scores with and without PCA:

Model Name | Without PCA | With PCA
------------ | ------------- | -------------
ConvNet | 90% | 
KNN | 85.5% | 86%
AdaBoost | 53.7% | 58.3%
Naive Bayes | 58.6% | 77%
Decision Tree | 79% | 77%
Random Forest | 85.3% | 86.2%


### For an easy comparison of the results of all the models using SEABORN go to the bottom of the jupyter notebook.


