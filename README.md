# Pytorch-application-on-MNSIT

Experiment with different optimizers on the MNIST dataset with different hyper-parameters using PyTorch. We used LeNet with ReLU activation function, Kaiming He initialization and logistic loss. We experimented using gradient descent, stochastic gradient
descent, AdaGrad and ADAM.

(a) Gradient Descent: We chose three learning rates and plotted the learning curves on one figure; each curve corresponds to one learning rate
(b) Stochastic Gradient Descent: We chose two different batch sizes and three learning rates and plotted two figures; each figure corresponds to one batch size and each curve corresponds to one learning rate
(c) AdaGrad: We fixed a reasonable batch size (which makes sure the loss function is overall decreasing) and an initial accumulator value (τ in PyTorch implementation). We chose three learning rate decays (η in PyTorch implementation) and three learning rates. We plotted three figures; each figure corresponds to one learning rate decay and each curve corresponds to one learning rate
(d) ADAM: We fixed a reasonable batch size and a learning rate. We tried three different values on adaptivity momentum (β1 in PyTorch implementation) and three different values on gradient momentum (β2 in PyTorch implementation). We plotted three figures; each figure corresponds to one β1 and each curve corresponds to one β2

Finally, a discussion on what are the advantages and disadvantage of different algorithms from the optimization point of view with focus on areas related to hyper-parameter sensitivity, convergence rates, etc.