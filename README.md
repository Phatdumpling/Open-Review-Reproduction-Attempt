# Open-Review-Reproduction-Attempt

## Reproduction process

https://openreview.net/pdf?id=HylTBhA5tQ#Hfootnote.4

Created a conda environment for tensorflow 1.15 due to it being 8 years old for [Mnist Challenge](https://github.com/MadryLab/mnist_challenge/tree/master)

Tried to view pictures in the npy files figured out all images were stored as 10000*784 so I reshaped 1 row and got the number 7

Afterwards was able to view and compare the MNIST dataset and compare images for pertubations

## Results 
Partial reproduction of 1/3 data that they used
CIFAR-10 would probably be able to be reproduced
Getting meaningful visualization was difficult
Difficulty mostly stemmed from the paper being old using outdated python packages such as tensorflow
Vizualization attempt [Here](https://github.com/Phatdumpling/Open-Review-Reproduction-Attempt/blob/main/archive/mnist_challenge-master/test.ipynb)