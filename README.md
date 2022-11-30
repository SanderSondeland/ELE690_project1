# ELE690 project

## Define path:

'fileCutData' contains the name of the matlab-file, where the data is located.
'pathCutData' is the path to where the matlab-file is located


## How to run:

There are two models implemented. One is a four layer CNN and the other is a five layer CNN. When training one model make sure
to use the right modelname. 

### The four layer CNN - PSP_CNN:
PSP stands for pooling-stride-pooling and this is the variables you can define. Value 1 means with and 0 means without. 
By setting the pooling parameter to 2, only one poolinglayer is added after all the layers.

### The five layer CNN - model_5CNN:
This model has only one adjustable parameter and that is if you want to have increasing number of filters 1 or not 0.

model_5CNN with increasing number of filters gives the best accuracy. 
