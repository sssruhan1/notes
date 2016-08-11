# Half-CNN: A General Framework for Whole-Image Regression

Jun Yuan, Bingbing Ni, Ashraf Kassim
arXiv'14

Using AlexNet structure, replacing the last layer as regression. Input image is entire image ( if size is not uniform, pad the images to same size). In between, use reverse-padding (up-sampling) to deal with size issue of object. Output image is probability-mask.

## comment: 
1. The promise is interesting. so what if the image size is huge? 
2. How come the input size can be random? Input size affect the output size in one layer. If one layer changes the input size, the following layer would have different input size.....


