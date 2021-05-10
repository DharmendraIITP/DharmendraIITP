- 👋 Hi, I’m @DharmendraIITP
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
DharmendraIITP/DharmendraIITP is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Generative Adversarial Networks, or GANs, are an architecture for training generative models, such as deep convolutional neural networks for generating images.

Developing a GAN for generating images requires both a discriminator convolutional neural network model for classifying whether a given image is real or generated and a generator model that uses inverse convolutional layers to transform an input to a full two-dimensional image of pixel values.

It can be challenging to understand both how GANs work and how deep convolutional neural network models can be trained in a GAN architecture for image generation. A good starting point for beginners is to practice developing and using GANs on standard image datasets used in the field of computer vision, such as the MNIST handwritten digit dataset. Using small and well-understood datasets means that smaller models can be developed and trained quickly, allowing the focus to be put on the model architecture and image generation process itself.

In this tutorial, you will discover how to develop a generative adversarial network with deep convolutional networks for generating handwritten digits.

After completing this tutorial, you will know:

How to define and train the standalone discriminator model for learning the difference between real and fake images.
How to define the standalone generator model and train the composite generator and discriminator model.
How to evaluate the performance of the GAN and use the final standalone generator model to generate new images
