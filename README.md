# Detecting-masks-on-Human-Faces

The goal is to detect whether a person has wore the mask or not by using Tensorflow, Keras, CNN.

<b>train_model.py</b> - is the training code written in Python by using Tensorflow, Keras, CNN for training the model.

<b>Requirements</b> : numpy , matplotlib, keras, tensorflow, os

If you want to train your model from scracth run the train_model.py and adjust the epochs of your choice. Just make sure that the dataset and train_model.py are in the same folder.

For the dataset of images with_masks and without_masks with both train and validation partitions download here - <a href="https://drive.google.com/drive/folders/11UNdC9jgGYaIlEjbnlKsTXwMXVX-fEC9?usp=sharing"><i>Download the Dataset</i></a>.

The Dataset contains the images as stated below:

![Dataset Info](https://github.com/saikumargandhi/Detecting-masks-on-Human-Faces/blob/main/Dataset%20Information.jpg?raw=true)

Training, Validation Accuracy and Loss image shows the respective accuracies and losses occured while training the model for 10 epochs.
![Accuracy and Loss Image](https://github.com/saikumargandhi/Detecting-masks-on-Human-Faces/blob/main/Training%2C%20Validation%20Accuracy%20and%20Loss.png?raw=true)

As you can see for only <b>10 epochs</b> we got a very good <i>accuracy</i> of around <b>98%</b>.
