# Art-Neural-Transfer

- The idea for this project comes from this paper: https://arxiv.org/abs/1508.06576

- Applied neural style transfer with pre-trained vgg-19 model to generate artistic images from selected content and style images.

- The generated image starts from an image with random noices. Then the cost function tires to minize the distance from the generated image to both the content image and the style image.

- With defined learning rate as well as the alpha and beta hyperparameters, the training process can start.

- The generated results should be ready after about 140 iterations of training.
