# Neural_Network_From_Scratch
The Code has been written using only numpy for calculations and matplotlib.pyplot for plots

* The General Algorithm for Backpropagation can be understood from https://sudeepraja.github.io/Neural/
* Mnist Data set can be downloaded from http://yann.lecun.com/exdb/mnist/. (I have used a much smaller version of the dataset. So you might have to change the hyperparameters accordingly .)
* The Optimisation algorithm used here is called Stochastic Gradient Descent https://en.wikipedia.org/wiki/Stochastic_gradient_descent

The code can be run by using the following steps :
```javascript
!git clone https://github.com/amokhvarma/Neural_Network_From_Scratch.git
!cd Neural_Network_From_Scratch
!python3 Neural_Network.py
```
To install numpy :
```javacript
!pip3 install numpy
```
The hyperparameters available to you are :
```javascript
l=3 #Number of layers
layer_neuron=np.array([784,120,10]) #Number of neurons in each layer. 1st must be 784 and last must be 10
alpha = 0.11
lambda = 0.1
```
Change the above variable to extend the neural network infinitely.
### Note
* input size must be (784,1) and not (28,28)


![download](https://user-images.githubusercontent.com/56398422/90169962-f8718200-ddbc-11ea-8597-97c767c9edd6.png)

Improvements to this can be made by :
1) Changing to Batch Gradient Descent.
2) Grid/Linear Search for hyperparameter tuning.
3) Weight initialisation using special methods like xavier initialisation.\
\
https://towardsdatascience.com/weight-initialization-in-neural-networks-a-journey-from-the-basics-to-kaiming-954fb9b47c79 is a fairly detailed analysis and intuition for weight initialisation.
