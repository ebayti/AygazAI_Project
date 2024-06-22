# CIFAR-10 Image Classification: KNN vs. CNN
This project tries to solve image classification task using the CIFAR-10 dataset.  Two approaches were used: **K-Nearest Neighbors (KNN)** and **Convolutional Neural Networks (CNN)**.

#### Libraries Used
- pandas (pd)
- numpy (np)
- random
- matplotlib.pyplot (plt)
- seaborn (sns)
- scikit-learn (various modules)
- tensorflow (tf)
- keras (layers, models, etc.)



The [CIFAR-10]([url](https://www.cs.toronto.edu/~kriz/cifar.html)) dataset is loaded using tf.keras.datasets.cifar10.

## KNN models
This project iterates through different distance metrics (minkowski, manhattan, euclidean) and K values (5, 10, 15) to evaluate KNN models. Then evaluates the performance of each model using accuracy score, F1 score (weighted), recall (weighted), and precision (weighted).


# CNN model
The CNN model was defined using Keras' Sequential API. The model consists of nine total layers which combine convolutional layers for feature extraction, pooling layers for dimensionality reduction, dropout layers to prevent overfitting, and dense layers for final classification. The model is trained using the Adam optimizer, Sparse Categorical Crossentropy loss function, and accuracy metric. Training and validation accuracy/loss are tracked during the training process.


Detailed information can be found at the [presentation](Baytimur_AygazAIPresentation.pdf) document.



