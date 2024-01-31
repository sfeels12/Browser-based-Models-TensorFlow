The model built in this project is a neural network which was trained to classify the images in the [Fashion MNIST dataset](https://www.kaggle.com/datasets/zalando-research/fashionmnist).

When launched, tfjs-vis in the fashion-mnist.html file will automatically display the model architecture and the training progress. 
Once training has finished, you can draw any of the 10 articles of clothing from the Fashion MNIST dataset on the black rectangle to be classified. 
After drawing an article of clothing, and pressing the "classify" button, the code will alert the predicted article of clothing.

The files in Results are:
* my_model.json: Contains the model architecture, i.e. the type and size of each layer.
* my_model.weights.bin: Contains the weights of the model. 
