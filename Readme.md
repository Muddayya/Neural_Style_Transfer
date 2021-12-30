# Neural style transfer with tf.keras

## Description
- The principle of neural style transfer is to define two distance functions, one that describes how different the content of two images are , Lcontent, and one that describes the difference between two images in terms of their style, Lstyle. Then, given three images, a desired style image, a desired content image, and the input image (initialized with the content image), we try to transform the input image to minimize the content distance with the content image and its style distance with the style image. In summary, we’ll take the base input image, a content image that we want to match, and the style image that we want to match. We’ll transform the base input image by minimizing the content and style distances (losses) with backpropagation, creating an image that matches the content of the content image and the style of the style image. 

## Implemented on
- Google Colab

## Resources
- https://medium.com/tensorflow/neural-style-transfer-creating-art-with-deep-learning-using-tf-keras-and-eager-execution-7d541ac31398

## Screenshots
- Content Image
![CLI-Content](https://github.com/111903050/Neural-Style-Transfer/blob/main/Images/turtle.png)

- Style Image
![CLI-Style](https://github.com/111903050/Neural-Style-Transfer/blob/main/Images/ocean.png)

- Output Image
![CLI-Output](https://github.com/111903050/Neural-Style-Transfer/blob/main/Images/output.png)
