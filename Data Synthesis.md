# Data Synthesis

### Generating Multi-label Discrete Patient Records using Generative Adversarial Networks
* [Paper Link](http://proceedings.mlr.press/v68/choi17a.html)
* Transform the discrete data to a continuous space by Autoencoder, which can address the issue of the discrete data synthesis.

### FakeTables: Using GANs to Generate Functional Dependency Preserving Tables with Bounded Real Data
* [Paper Link](https://www.ijcai.org/Proceedings/2019/287)
* This paper utilizes AutoEncoder to encode the Functional Dependency constraints. Then add two extra loss terms into the loss function of GAN, which can guide to generate synthetic data. And provides a theoretical analysis.

### Modeling Tabular data using Conditional GAN
* [Paper Link](http://papers.nips.cc/paper/8953-modeling-tabular-data-using-conditional-gan)
* Using the skew attributes as the conditional input to train a conditional GAN.

### Differentially Private Generative Adversarial Network
* [Paper Link](https://arxiv.org/abs/1802.06739)
* Adding noise to the gradient of discriminator to guarantee the differential privacy of synthetic data.

### Data Synthesis based on Generative Adversarial Networks
* [Paper Link](http://www.vldb.org/pvldb/vol11/p1071-park.pdf)
* Using CNN to implement the generator and introduce a classifier to guarantee the consistence of label.

### Synthesizing Tabular Data using Generative Adversarial Networks
* [Paper Link](http://arxiv.org/abs/1811.11264)
* Using LSTM to implement the generator.
