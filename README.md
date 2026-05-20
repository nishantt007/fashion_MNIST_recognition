# CNN Classifier for Fashion MNIST Dataset

A Convolutional Neural Network (CNN) built with TensorFlow/Keras to classify images from the [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) dataset. The model achieves multi-class classification across 10 clothing and footwear categories. Input images are single-channel (grayscale), so the input shape is `[28, 28, 1]`.

## Dataset

Fashion MNIST consists of 70,000 grayscale images (28×28 pixels) split into:
- **Training set:** 55,000 samples
- **Validation set:** 5,000 samples
- **Test set:** 10,000 samples

**Classes:** T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

## Training

- **Loss:** Sparse categorical cross-entropy
- **Optimizer:** SGD (learning rate = 0.01)
- **Regularizer** Dropout = 0.5
- **Metric:** Accuracy
- **Epochs:** 20
- **Validation:** Monitored each epoch; learning curves plotted via pandas/matplotlib
