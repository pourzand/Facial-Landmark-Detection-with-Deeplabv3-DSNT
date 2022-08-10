# Facial Landmark Detection with Deeplabv3 DSNT
Seena Pourzand

Attempt at utilizing the DeeplabV3+ FCN Architecture(implementation courtesy of [mjDelta](https://github.com/mjDelta/deeplabv3plus-keras/blob/master/deeplabv3plus.py)) and DSNT Layer(implementation courtesy of [ashwhall](https://github.com/ashwhall/dsnt)) 


[DeepLabV3+ Paper](https://arxiv.org/abs/1802.02611)

[DSNT Paper](https://arxiv.org/abs/1801.07372)

[Datatset](https://www.kaggle.com/c/facial-keypoints-detection/data)

## Dependencies

Tensorflow (2.9.2) although all the code should techincally work with version 1 given both the implementations of DSNT and DeepLabV3+ were done using v1, I've adapted them to work with v2 just be utilizing the `tf.compat.v1` for any tensorflow v1 specific code.

Numpy

Pandas

MatPlotLib(not necessary, just for visualizing the data)

PIL(not necessary, just for visualizing the data)
