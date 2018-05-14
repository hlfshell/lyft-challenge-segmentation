# Semantic Segmentation with VGG FCN
Udacity presented a Lyft sponsored challenge to take a dataset generated from [Intel CARLA](http://carla.org/) - consisting of a single RGB camera view and a 13 category segmentation map - and attempt to train a deep neural network to generate it.

I've never done segmantic segmentation before, so these are somewhat clumsy first attempts.

First, I thought doing a GAN to generate semantic maps by doing a pairwise discriminator. This didn't work out well.

Then I began working with Fully Convolution Networks with VGG16 as a base.
