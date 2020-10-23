# Data Cleaning

### Learning to Validate the Predictions of Black Box Classifiers on Unseen Data
* [Paper Link](https://dl.acm.org/doi/10.1145/3318464.3380604)
* Tell the user if the data is noisy by analyzing the output of classifiers.

### Attention-based Learning for Missing Data Imputation in HoloClean
* [Paper Link](https://proceedings.mlsys.org/paper/2020/hash/202cb962ac59075b964b07152d234b70-Abstract.html)
* It utilizes a variation of the dot product attention mechanism to learn interpretable, structural properties of the mixed data distribution and relies on the learned structure to perform imputation.

### GAIN: Missing Data Imputation using Generative Adversarial Nets
* [Paper Link](http://proceedings.mlr.press/v80/yoon18a.html)
* Imputing missing data by GAN. The generator (G) observes some components of a real data vector, imputes the missing components conditioned on what is actually observed, and outputs a completed vector. The discriminator (D) then takes a completed vector and attempts to determine which components were actually observed and which were imputed.

### MISGAN: LEARNING FROM INCOMPLETE DATA WITH GENERATIVE ADVERSARIAL NETWORKS
* [Paper Link](https://openreview.net/forum?id=S1lDV3RcKm)
* It can utitilze the missing data to train a GAN to generate complete data by allowing discriminator take the missing data as input, and use mask operation to corrupt the output of generator. It also provide a theoretical analysis.

### Raha: A Configuration-Free Error Detection System
* [Paper Link](https://dl.acm.org/doi/10.1145/3299869.3324956)
* It can generate an expressive feature vector for each tuple value.By generating a limited number of configurations for error detection algorithms that cover various types of data errors.
