
This competition is a playground type of competition where we doing it for fun and learning.  
The challenge in this competition is to do Kannada numbers image detection which consist of numbers from 0 to 10.  
  
### Model Architecture
CNN + Batch Normalization + Data Augmentation  

Conv1  
Conv1_1     28x28x32  
Conv1_2     26x26x32   
Conv1_3     24x24x32 - Pooling  
Dropout     12x12x64  
BatchNorm   12x12x64  
  
Conv2  
Conv2_1     12x12x64  
Conv2_2     10x10x64   
Conv2_3     8x8x64   - Pooling      
Dropout     4x4x64  
BatchNorm   4x4x64  

Flatten     1x1x1024  
Dense       1x1x128  
BatchNorm   1x1x128  
Droput      1x1x128  
Dense       1x1x10   - softmax

### Resource
  
competition link  
* [Kannada-MNIST](https://www.kaggle.com/c/Kannada-MNIST/)
  
some of the great kernel i learned from   
* [indian-way-to-learn-cnn](https://www.kaggle.com/shahules/indian-way-to-learn-cnn)
* [kannada-mnist-beginner-to](https://www.kaggle.com/jakelj/kannada-mnist-beginner-to)
  
choosing model  
* [how-to-choose-cnn-architecture-mnist#1](https://www.kaggle.com/cdeotte/how-to-choose-cnn-architecture-mnist#1.-How-many-convolution-subsambling-pairs?)