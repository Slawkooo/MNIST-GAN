# MNIST-GAN

The main gol of this project is to learn how generative adversarial network works and how to train them. The gan network I build try generates hand written digits form 0 to 9 based on MNIST data set. 

There is two neural network, one of them is generator and the other one is discriminator.
- Generator goal is to generates images 28x28 pixels witch have one of hand written digit form 0 to 9 and fool the discriminator with them,
- Discriminator goal is to identify witch images comes from original data set (true) and witch ones are generate from generator (fake).

Those two neural networks will learn together and at the end we will end up with generator that can generate realistic images of hand written digits in shape 28x28 pixels.
