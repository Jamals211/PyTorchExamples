# PyTorchExamples


<p>

  
Overview of PyTorch, Tensors, and NumPy
PyTorch
* TorchScript for creating serializable and optimizable models
* Distributed training to parallelize computations
* Dynamic Computation graphs to make computation graphs


Spatial Orientation
ANN -Artificial neural network 
* Number of parameters increases dramatically
* They lose spatial orientation

CNN-Convolutional neural networks
* First extracts low dimensional features then high dimensional features
* Uses filters to extract features from images and Pooling to reduce parameters
* Dont necessarily need grayscale but it eliminates a layer
* need to resize images to 28*28

<p>
CNN scans a 256 X 256 image chunk by chunk (say a 5 X 5 window) The window usually moves from left to right and top to bottom. The <b>Stride Length </b> determines how quickly the windows moves over the image. For example, a stride length of 2 means the window moves by 2 pixels at a time until the whole image is scanned.
  </p>
  
  <p>
  <b> Convolution </b> is a weighted sum of pixel values of the image
  </p>
