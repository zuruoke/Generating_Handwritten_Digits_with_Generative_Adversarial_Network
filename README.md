# Generating_Handwritten_Digits_with_Generative_Adversarial_Network

This kernel uses Generative Adversarial Networks (GAN) to recreate Images of Handwritten Digits from the keras mnist dataset.

GAN are able to learn high dimensional and complex data distributions to be able to reproduce synthetic data that looks real.

It has a behemothic inclusion in DeepFake Technology.

The kernel's workflow includes:

- Loading and Prepocessing the Data from keras.mnist

- Building a Generator Model that will create the fake images to fool the Discriminator network into thinking that its real 

- Building a Discriminator Model

- Building a GAN - Combining the Generator and Discriminator Networks

- Training a GAN

- Visualizing the Loss and the Generated Image

All these will be done with Tensorflow 2.x
