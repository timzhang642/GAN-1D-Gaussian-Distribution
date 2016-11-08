###Generative Adversarial Nets - generate 1-D Gaussian distribution


Original GAN paper: https://arxiv.org/pdf/1406.2661v1.pdf

This code is borrowed from and modified based on Eric Jang's implementation: http://blog.evjang.com/2016/06/generative-adversarial-nets-in.html

The goal is to create a fake-and-detect game, where two multilayer perceptrons are paired with each other. One network starts with nothing but noise to try to counterfeit data samples that look like the real data, whereas another network takes both real and fake data and tries to differentiate them. By competing with each other, overtime, they both get better. Ultimately the counterfeiter creates something that's so real that the detector network can no longer discriminate. This training mechnism is called Generative Adversarial Network. 
