# Deep Learning Models
This repository contains three deep learning models - Simple Artificial Neural Network, Convolutional Neural Network, and Recurrent Neural Network implemented on different use cases.


### **Simple Neural Network**

<p>
This model was used for a simple binary classification problem with two features. The features were standardized using <code>StandardScaler</code> before being split and sent into the neural network for training. The figure below visualizes the architecture chosen for the neural network.
</p>

<p>
The model was compiled using the Adam optimizer, binary crossentropy as the loss function, and accuracy as the evaluation metric. Training was conducted over 200 epochs with a batch size of 50.
</p>

### **Convolutional Neural Network**

<p>
This Convolutional Neural Network (CNN) model was trained with images of five types of flowers (sunflower, tulip, dandelions, roses, and daisy). The goal is to see if the model can identify what type of flower is in an image if it is shown an image it has not seen during training. The input images were preprocessed by resizing them to a standard dimension and normalizing pixel values to a range of 0 to 1 before being fed into the network. 

<p>
The model was compiled using the Adam optimizer, categorical crossentropy as the loss function, and accuracy as the evaluation metric. Training was conducted over 20 epochs with a batch size of 32.
</p>

### **Recurrent Neural Network**
<p>
This Recurrent Neural Network (RNN) model was applied to sunspot data, which is a record of the number of visible sunspots on the surface of the Sun over time. Sunspot data is considered time series data because it consists of observations collected sequentially over regular time intervals, capturing temporal dependencies and patterns.
</p>

<p>
The data was preprocessed by normalizing the values to improve model performance. The RNN architecture was designed to capture these temporal dependencies and make predictions about the next set of values in the series. The model utilized Long Short-Term Memory (LSTM) layers, which are well-suited for handling sequential data and retaining long-term dependencies.
</p>

<p>
The model was compiled using the Adam optimizer, mean squared error as the loss function, and no additional metrics. Training was conducted over 5 epochs with a batch size of 64.
</p>






