An Image classifier for CIFAR 10 Dataset 
=
CIFAR 10 dataset contain 70,000 images ( 60,000 training set and 10,000 test set ).

The images belong to 10 different classes.

Link : https://www.cs.toronto.edu/~kriz/cifar.html

<b>Note</b>

The Python Notebook attached shows the architecture and the training processes of an ANN model for image classification. 
The model has more than 1,000,000 parameters in total and so it was trained on a GPU. 
Working with on so many parameters would be extremely difficult with a CPU and will take quite a long time to train with not so results.
It is advised to run neural networks ( basically Deep Learning Algorithms )  on a GPUs since they 
require a lot of computational power. 

In this case Google Colab was used since it provides strong computational resources ( GPU and TPU support )  
for free (a cloud based environment). A local GPU can also be used but setting up a GPU requires some research and version compatibility.
There many useful videos on YouTube for the same. And before starting please make sure you have GPU device install on your system.  
If your system has a NVIDIA setup do check the official websites of NIVIDIA and Tensorflow for the requirments and installations steps. 
CUDA Driver and cuDNN libraries are the main requirements for running tensorflow-gpu on a local machine.

After training, the model achieved an accuracy of 40.73% on the training set and 44.66% on the validation (test) set. 
This accuracy is not that bad for a ANN model having so many parameters to train on. The accuracy can be improved by tuning the
hyperparamters of the neural network.
