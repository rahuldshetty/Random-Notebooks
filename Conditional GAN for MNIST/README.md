# Conditional GAN for MNIST

In this notebook I created a Neural network that can synthesis a given hand written digit. I used a label encoding to train the network to generate that particular digit. The generator is trained with a label and latent vector to generate a 28x28 image of that label(0 to 9). The discriminator takes in the image and the label and predicts if they both match or not.