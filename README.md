# MLP from scratch
Building a fully connected feed-forward network (Multilayer perception) using only numPy. The neural network is trained to detect hand-drawn numbers from the MNIST dataset.
This was a quick project that I did to get a good foundational understanding of the math behind back-propagation and stochastic gradient descent.

### Stochastic gradient descent results
The accuracy on the test dataset is around 92%

This is the loss function during training over 5 epochs:

![image](https://github.com/user-attachments/assets/66b3d07e-b7a3-48c0-864e-02f7ad6a3c9f)


### Minibatch gradient descent results
The accuracy on the test dataset is around 90%

This is the loss function during training over 20 epochs with a minibatch size of 16:

![image](https://github.com/user-attachments/assets/1bd73b6a-cabc-45ed-93c9-6282ae1bf590)


### Future projects
I didn't tweak the initial parameters or try out other non-linearity functions like ReLU or tanh, so that will be something I will try out in the future.

I also want to learn and implement other optimization algorithms (ex. Autograd)

I want to try implementing other architectures, like CNNs or LSTM neural networks...




