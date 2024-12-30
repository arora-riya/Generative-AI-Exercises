### generative-ai

#### `variational_autoencoder.ipynb`
- Implementation of VAE using PyTorch, trained on celebA faces dataset.
- Making images smile, using both original image space and latent space arithmetic.

#### `gan_cifar10.ipynb`
- Implementation of standard GAN on CIFAR-10 data.

#### `gan_mnist.ipynb`
- Implementation of standard GAN on MNIST data. 
- Used the following to prevent discriminator from becoming too good for the generator to learn.
    - Simple architecture for discriminator
    - Low learning rate for the discriminator
    - Label smoothening
    - Updating generator more often