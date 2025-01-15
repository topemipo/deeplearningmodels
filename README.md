# Deep Learning Models
This repository contains three deep learning models - Simple Artificial Neural Network, Convolutional Neural Network, and Recurrent Neural Network implemented on different use cases.

<h1>Simple Neural Network</h1>

<p>
This model was used for a simple binary classification problem with two features. The features were standardized using <code>StandardScaler</code> before being split and sent into the neural network for training. The figure below visualizes the architecture chosen for the neural network.
</p>

<div align="center">
  <img src="plots/model_plot.png" alt="Simple Neural Network Architecture" width="300" height="300">
</div>

<p>
The model was compiled using the Adam optimizer, binary crossentropy as the loss function, and accuracy as the evaluation metric. Training was conducted over 200 epochs with a batch size of 50.
</p>

<p>
The training and validation loss and accuracy were plotted. The figure is shown below:
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/00892ea1-4365-4bb6-b86c-09d405c026ec" alt="Training and Validation Loss and Accuracy" width="600" height="300">
</div>

<p>
The loss and accuracy of the neural network are <b>0.494</b> and <b>0.843</b>, respectively.
</p>

<p>
A confusion matrix was also plotted to assess the model's performance. See below:
</p>

<div align="center">
  <img src="https://github.com/user-attachments/assets/741210dc-cf5b-4ee7-b75a-9ccf9ef9be87" alt="Confusion Matrix" width="300" height="300">
</div>





