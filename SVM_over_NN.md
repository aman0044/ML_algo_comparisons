
# Advantages of SVM over NN

* Data-hungry: To train NNs, you need massive amounts of data. Here is a standard set of benchmark datasets: https://archive.ics.uci.edu/ml/datasets.html : Data Sets. Pick any dataset from this set with fewer than 1000 training examples, and try training a NN that beats SVM on that data by a large margin.


* SVM tries to increase the margin between different features but NN tries to decrease the error.Hence NN can overfit the data.Moreover SVM has inherently a linear decision boundary. To learn more complex decision boundaries, kernels can be used. ANNs naturally learn non-linear decision boundaries and thus are also more prone to overfitting.


* SGD (Gradient Descent) is typically used for learning the parameters of ANNs (this might get stuck in local minima), SMO (Sequential Minimal Optimization) is used to learn parameters of a SVM (reaches global minima).


* SVM results are understandable and can be explained both numerically and visually.NN typically is a black box of algorithms.


* Comparing to CNN's ,CNN require spatial property: Convolution operation performs an operation on a set of pixels or a sequence of words/audio signals that are close-by. Shuffling the pixels/words/audio signals will change the output of the CNN completely. That is, the order of the features is important, or in other words, convolution is a “spatial” operation. SVMs are unaffected by shuffling of features. So problems which do not have the spatial property will not benefit from CNNs.





### Lets see what Andrew Ng (ML-God) has to say about this.

link : http://cs229.stanford.edu/materials/CS229-DeepLearning.pdf

### Use of SVM in deep learning 
 http://deeplearning.net/wp-content/uploads/2013/03/dlsvm.pdf

### At last Quote of the day 
## “Don’t throw away the needle when you get a sword!”


```python

```