# Paper2Pytorch
pytorch implementation of some computer vison research papers
 
## Goal

The goal of project is to implement the main ideas of research papers into pytorch code. The code is thus not meant to review all results given in the paper, but rather to get a feeling about how the algorithm runs. I usually lean myself on some existing code in a different deep learning framework or language, e.g. tensorflow, torch, theano and transform into pytorch. I try to cite clearly what my main sources are, but wont be able to cite all sources from e.g. quick solution googleing. If you feel I used your idea, I am more than happy to give credits to you.
I code every project in one comprehensive iPython notebook, mainly because it lets you run them in Google Colab with GPU support for free.

## Papers

Some paper implementations are still in progress. 

Here is the current list of papers:
#### GAN
* DCGAN -> [Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks](https://arxiv.org/abs/1511.06434)
#### Image-to-Image Translation (more GANs)
* pix2pix ->[Image-to-Image Translation with Conditional Adversarial Networks](https://arxiv.org/abs/1611.07004)
* cycleGAN -> [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/abs/1703.10593)
#### Style Transfer
* fast_style -> [Perceptual Losses for Real-Time Style Transfer and Super-Resolution](https://cs.stanford.edu/people/jcjohns/eccv16/)
* neural_style_transfer (Combination of the following papers):
    - [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)
    - [Controlling Perceptual Factors in Neural Style Transfer](https://arxiv.org/abs/1611.07865)
