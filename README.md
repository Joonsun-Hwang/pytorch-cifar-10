# pytorch-cifar-10
## The best test accuracy is 92.12% at 90 epoch

## Ajou Unversity: Computer Vision Lecture
	- by Johnson Hwang (201321140) -


 * This was developed based on Google Colaboratory & Google Drive


### Constraint
  Have to stack up to 10 layers and make a model.

### Used
 0. Python Deep Learning Framework - Pytorch
 1. Data augmentation
 2. Optimizer - Adam (learning rate=0.0001, 0.00004)
 3. Initializer - Xavier

### Model Architecture
 1. Use LeakyReLU & Fractional Max-Pooling (output size=0.8) Layer
 2. The probability of dropout increases as the hidden layer deepens.
 3. For the n-th convolution layer, the number of out channels is 120*n.
 4. This model consists of 8 conv2d, 1 conv1d and 1 FC

 This model is stored on Google drive using pyDirve.