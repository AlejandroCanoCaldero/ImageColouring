# Image Colouring

Project developed by Alejandro Cano Caldero and Jesús Moncada Ramírez for the subject Neural Networks and Deep Learning, University of Padova, 2022-23.

## 1. Abstract
We present a method so as to tackle the image recoloring problem, that is to say, assigning RGB values to grayscale pixels. Not only will this paper show how this problem can be handled by implementing a UNET Autoencoder and Patch GAN, but it will also showcase an important enhancement provided by additional perceptual losses and the implementation of a W-GAN network with gradient penalty. These tools will prove to match human perception well and give higher stability to the training model, respectively. To visualize the progress that has been made, we will gradually attach the refinements previously mentioned and the given results to show how the final implementation outperforms the rest.

## 2. Trained models
We trained some models with a 500 samples training set from Imagenette. The resulting models can be found [here](https://drive.google.com/drive/folders/1hR81Sxd95-xA5r4h-IL9mkZ4z3fa7Na3?usp=sharing).

## 3. Some results
Some results of our work are the following. For this input image:

![Input image](/results/input_image_1.png "Input image")

these are the results:

![Result](/results/result_1.png "Results")

## 4. Paper
We have created a paper explaining all the work made, the theory behind the models and the results obtained. It can be found at ``docs/ImageRecoloringWithConditionalGANs.pdf``.

## 5. Interesting links
Some interesting links that helped us to understand the problem covered:
- [(Video) Image to image translation using Pix2Pix GAN](https://www.youtube.com/watch?v=UcHe0xiuvpg)
- [(Video) Satellite image to maps translation using pix2pix GAN](https://www.youtube.com/watch?v=6pUSZgPJ3Yg)
- [Pix2Pix:Image-to-Image Translation in PyTorch & TensorFlow](https://learnopencv.com/paired-image-to-image-translation-pix2pix/#discriminator)
- [Introduction to Generative Adversarial Netowrks (GANs)](https://learnopencv.com/introduction-to-generative-adversarial-networks/)
- [Conditional GAN (cGAN) in PyTorch and TensorFlow](https://learnopencv.com/conditional-gan-cgan-in-pytorch-and-tensorflow/)


