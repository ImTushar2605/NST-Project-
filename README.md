# NST-Project-
# Description
Building a Deep Learning model that inputs two images - content and style, and outputs an image that looks like the content image in the style of the style reference image.
 
# Methodology 
1. The project commenced with an exploration of deep learning and artificial neural networks.
2. Created a simple neural network from scratch using NumPy for classifying digits in the MNIST dataset.
3. Enhanced our models by learning optimization techniques and transitioned to PyTorch for efficiency.
4. Learnt the working of CNN and studied various CNN architecture 
5. Implemented our own custom CNN architecture with a high level of accuracy for digit classification on the MNIST dataset.
6. Finally, the culmination of our project involved implementing Neural Style Transfer using the PyTorch framework as the final task

 **The Algorithm**
      Neural style transfer is an optimization technique used to take two images,
 a content image and a style reference image (such as an artwork by a famous painter)—
and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

![styletransferexample](https://github.com/ImTushar2605/NST-Project-/assets/132780116/1f0e51b4-7f86-417f-8bf0-a807b194509b)
**Procedure** 
VGG19 network is used for Neural Style transfer. VGG-19 is a convolutional neural network that is trained on more than a million images from the ImageNet database. The network is 19 layers deep and trained on millions of images. 
<img width="528" alt="415eefce2de29543991446cabc1adc08" src="https://github.com/ImTushar2605/NST-Project-/assets/132780116/fa34744d-bee8-4c21-890a-169572511e49">
Firstly we defined two functions
**(i) : Content Loss** :
        ![Uploading quicklatex.com-0eb42b529c2bf73ca5756760e07c3c0e_l3.svg…]()
 # (ii): Style Loss      
                ![quicklatex com-526dc5d6e78d9557eedbdeed3d9e67dd_l3](https://github.com/ImTushar2605/NST-Project-/assets/132780116/b6d6c458-0626-4e5a-b85d-d9c0ebf1c610)
                    
                                   

