# CNN
**Scratch implementation of all the layers of a simple convolutional neural network using basic python libraries.**
The notebook displays scratch implementation of all the layers in a convolution neural network using numpy fit forward as well as backward pass. 
![image](https://github.com/user-attachments/assets/9b5455d1-ab11-4cf0-a8a9-e94546d65c11)

The implemented layers are:
**1.  2D Convolutional Layer**
      **Parameters:** in_channels,filter_size,filter_num, padding=0, stride=1, bias=True,  conv_layer=1
      in_channels:int  -> number of input channels
      filter size: int -> size of the convolution kernel
      filter_num:int -> number of kernels
      padding:int -> by defaut 0 and implements zero padding

      output size= (input size-filter size  + 2*padding)/stride) +1
      
      For backpropagation in 2d convolutional layer, refer to https://deeplearning.cs.cmu.edu/F21/document/recitation/Recitation5/CNN_Backprop_Recitation_5_F21.pdf  
      
**2.  2D Max Pooling Layer**  
      Outputs the maximum value in the filter.
      **Parameters:** pool_size, stride, padding=0
      pool size: int -> size of the max kernel

**3.  2D Average Pooling Layer**  
      Averages the value in the filter.
      **Parameters:** pool_size, stride, padding=0
      pool size: int -> size of the max kernel

**4.  Flatten Layer**  
      Converts the 2D input to a 1D array. 

**5.  Activation layer Layer**  
      Implements three activations function - sigmoid, ReLu, Softmax

**6.  Linear Layer**  
      Python class implementing single layered neural network.

Dataset link: KMINST  https://github.com/rois-codh/kmnist

