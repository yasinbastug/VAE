# VAE
Manipulating latent space and acquiring plane images from CIFAR-10 bird-plane dataset with encoding-decoding being done by Variational Autoencoder.

## The dataset
https://www.cs.toronto.edu/~kriz/cifar.html

## The paper I got inspired
https://arxiv.org/abs/2111.08794

## Implementation
- Train the Variational Autoencoder (VAE) with bird-plane train dataset
- Train a binary classifier to use for later to see the results.
- Use (VAE) to encode the 32*32 images
- Do Principal Component Analysis (PCA) on latent space of the encoded image
- Manipulate the principal component: add or subtract a real number
- Decode with the VAE
- Use binary classifier to classify the new manipulated dataset
- Compare the ratios of planes to birds
