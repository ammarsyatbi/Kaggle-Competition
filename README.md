
### Model Architecture
CNN + Batch Normalization + Data Augmentation  

_________________________________________________________________
Layer (type)                 Output Shape              Param #   
=================================================================
conv2d_7 (Conv2D)            (None, 26, 26, 32)        320       
_________________________________________________________________
batch_normalization   (Batch (None, 26, 26, 32)        128       
_________________________________________________________________
conv2d_8 (Conv2D)            (None, 24, 24, 32)        9248      
_________________________________________________________________
batch_normalization   (Batch (None, 24, 24, 32)        128       
_________________________________________________________________
conv2d_9 (Conv2D)            (None, 12, 12, 32)        25632     
_________________________________________________________________
batch_normalization_10 (Batc (None, 12, 12, 32)        128       
_________________________________________________________________
dropout_4 (Dropout)          (None, 12, 12, 32)        0         
_________________________________________________________________
conv2d_10 (Conv2D)           (None, 10, 10, 64)        18496     
_________________________________________________________________
batch_normalization_11 (Batc (None, 10, 10, 64)        256       
_________________________________________________________________
conv2d_11 (Conv2D)           (None, 8, 8, 64)          36928     
_________________________________________________________________
batch_normalization_12 (Batc (None, 8, 8, 64)          256       
_________________________________________________________________
conv2d_12 (Conv2D)           (None, 4, 4, 64)          102464    
_________________________________________________________________
batch_normalization_13 (Batc (None, 4, 4, 64)          256       
_________________________________________________________________
dropout_5 (Dropout)          (None, 4, 4, 64)          0         
_________________________________________________________________
flatten_2 (Flatten)          (None, 1024)              0         
_________________________________________________________________
dense_3 (Dense)              (None, 128)               131200    
_________________________________________________________________
batch_normalization_14 (Batc (None, 128)               512       
_________________________________________________________________
dropout_6 (Dropout)          (None, 128)               0         
_________________________________________________________________  
dense_4 (Dense)              (None, 10)                1290        

### Resource
  
competition link  
. [Kannada-MNIST](https://www.kaggle.com/c/Kannada-MNIST/)
  
some of the great kernel i learned from   
. [indian-way-to-learn-cnn](https://www.kaggle.com/shahules/indian-way-to-learn-cnn)
. [kannada-mnist-beginner-to](https://www.kaggle.com/jakelj/kannada-mnist-beginner-to)
  
choosing model  
. [how-to-choose-cnn-architecture-mnist#1](https://www.kaggle.com/cdeotte/how-to-choose-cnn-architecture-mnist#1.-How-many-convolution-subsambling-pairs?)