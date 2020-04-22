# deep-generative-models

This repo contains python code for following deep generative models:
  1. Variational Autoencoders (VAEs) 
  2. Deep Convolutional Generative Adversarial Network (DCGAN).



This is work is greatly inspired from following sources:
*  [pytorch vae tutorial](https://github.com/pytorch/examples/tree/master/vae)
*  [dcgan implemntation by Anish Reddy](https://github.com/anishreddy3/Fashion-MNIST-GAN-Keras)

Models can be trained on following datasets:
* [Fashion-MNIST](https://github.com/zalandoresearch/fashion-mnist)
* [MNIST](http://yann.lecun.com/exdb/mnist/)


<br/>VAE is implemented using pytorch
<br/>To run VAE execute:
```$bash
python vae.py
```

<br/>DCGAN is implemnted is implemented using Tensorflow/Keras
<br/>To run DCGAN execute:
```$bash
python dcgan.py
```