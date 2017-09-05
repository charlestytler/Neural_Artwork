# Neural_Artwork

### References:
Based off the Tensorflow implementation here:
https://github.com/ckmarkoh/neuralart_tensorflow
of "A Neural Algorithm of Artistic Style" published here:
http://arxiv.org/abs/1508.06576

The saved weights for the pretrained VGG-19 model are accessed from a Matlab .mat file here:
http://www.vlfeat.org/matconvnet/models/imagenet-vgg-verydeep-19.mat


[imageOrig]: ./Images/copenhagen.jpg "Copenhagen"
[imageTrain1]: ./Images/pollock.jpg "Pollock"
[imageTrain2]: ./Images/sean_phillips_fatale.jpg "Brubaker"
[imageTrain3]: ./Images/Illusionist.jpg "L'Illusionist"
[imageResult1]: ./Results/pollock.png "Pollock"
[imageResult2]: ./Results/phillips_fatale.png "Brubaker"
[imageResult3]: ./Results/Illusionist.png "L'Illusionist"

### Original image:
![Orig][imageOrig]

## Neural Net images:

The first image will be the training image for the neural net, the second image is the morphed version of the original image taken from the feature map of the neural net.

### Sean Phillips - "Fatale" Comic Book
![b][imageTrain2]
![b][imageResult2]

### Jackson Pollock - "Convergence" Painting
![a][imageTrain1]
![a][imageResult1]

### Sylvain Chomet - "L'Illusioniste" Animated Film
![c][imageTrain3]
![c][imageResult3]

