# 生成式对抗网络源码汇总
## 简介
  自从14年 Ian Goodfellow 发表了论文Generative Adversarial Nets 以来，生成式对抗网络 GAN 受到广受关注，加上学界大牛 Yann Lecun 曾说他最激动的深度学习进展是生成式对抗网络，使得 GAN 成为近年来在机器学习领域的新宠。而目前GAN已经有很多应用，不仅可以生成手写数字，还能生成人脸还有在图像超分辨率上面的应用。
  
## 论文
GAN的发展轨迹如下：
GAN->CGAN->LAPGAN->DCGAN->GRAN->VAEGAN

GAN    Generative adversarial nets https://arxiv.org/abs/1406.2661
CGAN   Conditional Generative Adversarial Nets https://arxiv.org/abs/1411.1784
LAPGAN Deep Generative Image Models using a Laplacian Pyramid of Adversarial Networks https://arxiv.org/abs/1506.05751
DCGAN  Unsupervised representation learning with deep convolutional generative adversarial networks https://arxiv.org/abs/1511.06434
GRAN   Generating images with recurrent adversarial networks http://lanl.arxiv.org/abs/1602.05110
VAEGAN Autoencoding beyond pixels using a learned similarity metric https://arxiv.org/abs/1512.09300

## 代码
- Tensorflow implementation of Deep Convolutional Generative Adversarial Networks which is a stabilize Generative Adversarial Networks https://github.com/carpedm20/DCGAN-tensorflow
- Keras implementation of Deep Convolutional Generative Adversarial Networks https://github.com/jacobgil/keras-dcgan
- Improved Techniques for Training GANs https://github.com/openai/improved-gan
- InfoGAN: Interpretable Representation Learning by Information Maximizing Generative Adversarial Nets https://github.com/openai/InfoGAN
- A collection of generative methods implemented with TensorFlow (Deep Convolutional Generative Adversarial Networks (DCGAN), Variational Autoencoder (VAE) and DRAW: A Recurrent Neural Network For Image Generation). https://github.com/ikostrikov/TensorFlow-VAE-GAN-DRAW
- Implementation of Sequence Generative Adversarial Nets with Policy Gradient https://github.com/LantaoYu/SeqGAN
- StackGAN: Text to Photo-realistic Image Synthesis with Stacked Generative Adversarial Networks https://github.com/hanzhanggit/StackGAN
- Tensorflow implementation of Wasserstein GAN https://github.com/shekkizh/WassersteinGAN.tensorflow
- Style and Structure GAN (ECCV 2016) https://github.com/xiaolonw/ss-gan
- Generative Adversial Network for music composition https://github.com/jacotar/sound-GAN
