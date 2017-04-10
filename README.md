
# Fully convolutional network for image segmentation

This is a model implemented as part of my master thesis. The goal is that the model should segment multispectral images, so that building information can be extracted.


## Tensorflow
The network is implemented by using the library TensorFlow.

## Recognition
The network is based on the SegNet implementation by tkuanlan35: https://github.com/tkuanlun350/Tensorflow-SegNet.

## Requirements:
- Tensorflow GPU 1.0.1
- Python 3.5

See more in requirements.txt.

## Usage
#### Requirements
pip install -r requirements.txt

#### Run TensorBoard:
tensorboard --logdir=path/to/log-directory

#### Dataset
Download the CamVid dataset from: https://github.com/alexgkendall/SegNet-Tutorial, and set correct paths in model_train.py.
