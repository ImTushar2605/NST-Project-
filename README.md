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

# Define the Loss
The net loss for style transfer is defined as :  
![loss function](https://github.com/ImTushar2605/NST-Project-/assets/132780116/237b8d4d-701b-4399-9b91-8a144a37422e)
 Lₜₒₜₐₗ is the total loss, L 𝒸ₒₙₜₑₙₜ is the content loss of all the intermediate layers and Lₛₜᵧₗₑ is the style loss of all the intermediate layers. Here, α and β are the weighting coefficients of the content and the style loss, respectively
# Content Loss
Calculating content loss means how similar is the randomly generated noisy image(G) to the content image(C).In order to calculate content loss :
               ![content loss](https://github.com/ImTushar2605/NST-Project-/assets/132780116/e5fb0b22-ed3f-4591-be72-646847510da1)
# Style Loss 
It is the function of style reference image and genrated image . It mesures how similar is style of  the genrated image to the style of style image. 

# Results 

  
                    
                                   

