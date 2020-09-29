# Image-Denoising-Using-Autoencoder

Image Denoising Techniques Using Autoencoder using Keras implemented on Fashion MNIST dataset.

* In this project we will use Denoising Autoencoder for denoising the images of fashion MNIST dataset.

* We will add noise to train dataset**(noisy_pixel = pixel + noise_factor * random_no)**, feed to the Autoencoder network as input.

* The output will be clean(denoised) original image.

* The denoising autoencoder tries train vector field to map toeards a low dimensional manifold, i.e. the sensitive region to where the noisy distribution can shift, so as to generate denoised version of the image.

* The structure of denoising autoencoder is shown below:

![Image]()

The details implementation is done using Keras as tensorflow backend, can be found in the [Collab Notebook](https://github.com/sayan0506/Image-Denoising-Using-Autoencoder/blob/master/Autoencoder_for_image_denoising.ipynb).

**References:**

* IIT Kharagpur Deep Learning Lectures
* https://www.pyimagesearch.com/2020/02/24/denoising-autoencoders-with-keras-tensorflow-and-deep-learning/

