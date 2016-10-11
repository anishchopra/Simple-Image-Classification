# Simple-Image-Classification
A tool allowing you to perform image classification on a relatively small dataset by using the Inception V3 pre-trained model.

In the example provided, only 42 images were used for each category, including the training and validation images! This is the advantage of using a pre-trained model.

## Requirements
- NumPy
- Scikit-Learn
- Keras
- TensorFlow

## Usage
Use generate_inception_features.py to generate the features computed using the Inception V3 pre-trained model.

Use train_nn.py to train a one-layer neural network classifier, which takes in an Inception feature as input.

Use run_classifier.py to run your newly-trained classifier on a new image.

See demo.py for example usage and further instructions.
