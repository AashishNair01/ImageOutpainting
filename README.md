# ImageOutpainting
With advancements in AI technology, machines can
perform or even mimic tasks that we humans can do. One of its
achievements can be seen in image generation, one of it being
Image Inpainting (completion).In Image Inpainting, we use AI
to complete missing data in an image. This is an extensive field
of research, but its contemporary field, i.e., image outpainting, is
not a well-researched one. In Image Outpainting (extrapolation)
We try to extend the image beyond its borders. This is similar to
our brain picturing the whole image of an object that we
partially see through a gap. This task can be achieved by using
Generative Adversarial Networks (GANs). Compared to
Inpainting, the biggest challenge is to achieve spatial correlation
between the generated image and the ground truth image. Also,
the process of overcoming this challenge is sometimes
affected because of the training instability of GAN. With the help
of Wasserstein GAN (WGAN), the above issue can be solved. So,
we propose a model based on the Wasserstein GAN with
Gradient Penalty (WGAN-GP) algorithm and deep
convolutional neural networks for image outpainting using a
dataset of natural images. From this proposed model, we found
that the results of the WGAN-GP algorithm were better than
GAN algorithm in various aspects. <br/>
The works of this project were presented in an IEEE conference (ICCMC 2022). Read more about it [here](https://ieeexplore.ieee.org/document/9753713)
