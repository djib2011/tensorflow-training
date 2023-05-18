# TensorFlow training

> Note: This is a fairly new repo and most of the material have not been proofread yet! If you encounter any errors or typos let me know so I can fix them!

## Scope

This training aims at teaching people the frameworks of TensorFlow and Keras from a technical standpoint. It is not meant to teach Neural Network or Machine Learning/Deep Learning concepts, instead it assumes some basic theoretical understanding of these.

## Structure

This training is split into two parts: TF101 which is more beginner friendly and TF102 where more advanced and low-level concepts will be explored.

### TF101

The first part mainly aims to introduce Keras, a user-friednly, high-level API to TensorFLow. It consists of 4 parts:

1. **Intro to keras**
    - What is TensorFlow?
    - What is Keras?
    - How can we define and train Neural Networks in Keras?
2. **Deeper customization of Keras models and training**
    - Configuring our models: architecture, training params, regularization, etc.
    - Configuring our models' training: losses, optimizers, metrics, callbacks, etc.
3. **Practical training tips**
    - Visualizing our model's performance through training with the history callback.
    - Intro to TensorBoard.
4. **Using pretrained models**
    - What are pretrained models? Where to find them? 
    - Using a HuggingFace pretrained model as an out-of-the-box classifier/feature extractor.
    - Fine-tuning a pretrained model.
    - Partial warm-start.

### TF 102

The second part aims to introduce the lower-level native TensorFlow API and how it functions.

1. **TF concepts & low-level functionality**
    - What is a computational graph?
    - What is the difference between eager and graph mode?
    - What is AutoGrad?
    - Low-level TensorFlow operations.
2. **Custom training loops**
    - Example defining models without the keras API.
    - Training a model with a custom training loop (i.e. without the .fit() API).
    - Adding custom metrics to TensorBoard.
3. **TensorFlow Datasets**
    - What is a data generator?
    - How to use the TensorFlow Dataset API.
4. **Advanced concepts**
    - Deeper dive into the Keras API. Creating custom layers, losses, metrics, etc. How metrics work in Keras.
    - Distributed training.
    - Explicit device placement.
    - Model performance optimization (distillation, quantization, pruning, etc.)

## Prerequisites

This training assumes the participant has:

1. a working knowledge of Python
2. a basic understanding of Machine Learning and Deep Learning concepts
3. a basic understanding of Neural Networks

These topics are explored in [another tutorial](https://github.com/djib2011/python_ml_tutorial).

## Requirements

This course was run on Python 3.9.13, but should safely run with any Python version above 3.6. Access to a GPU isn't necessary to run the notebooks.  

The detailed list of requirements can be found in `requirements.txt` and can be installed through a command like `pip install -r requirements.txt` to your system interpreter, virtual environment or wherever you prefer. 

