# LeafNet


#LEAFNET:Design and evaluation of a deep CNN model for recognition of plant leaves.

This project is used to predict the disease of a leaf that uses convolution neural networks to extract features from leaf images and categorize them.In this we have used plant village dataset to train our model.
steps:
1.collect a dataset which contains both healthy and diseased leaves
2.data preprocessing and resize the images and normalize the pixel values.
3.we use convolution layers of the pre trained CNN.in our project we used visual keras packages includes visualization tool for keras model and generate architecture of each model.

we developed a architecture for 7 models.
1.simple CNN
2.CNN WITH AUGMENTED AND DROPUT LAYERS
3.CNN ONLY WITH AUGMENTED LAYERS
4.CNN WITH ONLY DROPOUT LAYERS.
5.CNN WITH ONLY TWO DIFFERENT AUGMENTED LAYERS.
6.CNN WITH DATA AUGMENTATION AND MORE DENSE LAYERS.
7.CNN WITH FILTERS IN ALL THE LAYERS.

AUGMENTATION LAYERS- Data augmentation is a technique of artificially increasing the training set by creating modified copies of a dataset using existing data.
DROPOUT LAYERS-The dropout layer is a layer used in the construction of neural networks to prevent overfitting.
DENSE LAYERS-The Dense layer is a normal fully connected layer in a neuronal network.


In this project we observed each model with different activation functions and optimizers and architecture of each model.

nadam with relu-100%.



