---
type: gallery-details
active: true

# Display name
title: Weak Lensing Cosmology with Machine Learning

url: static/img/rotated.jpeg
brief: Cosmological parameter estimation using convolutional neural networks.

keywords:
    - Cosmology
    - UGrad

preview-image: static/img/cnn2.png

# Image slideshow
images:
    - url: /static/img/cnn2.png
      caption: |
        Schematic of a convolutional neural network trained to predict cosmological parameters from weak lensing data.

information: |
    ### Weak Lensing Cosmology with Machine Learning

    * What can we learn about the Universe from weak lensing data?


---

### Weak Lensing Cosmology with Machine Learning

For my Master's, I explored Deep Learning as a method of constraining cosmological parameters in the Lambda-Cold-Dark-Matter Model, supervised by Benjamin Giblin and Catherine Heymans. We used noisy weak lensing shear maps generated using the SLICS and CosmoSLICS simulation suites to train a convolutional neural network (CNN) to predict the underlying parameters. During this process, we explored the effects of different network architectures, training methods, and data augmentation techniques. We found that a CNN was not yet competetive with the standard 2-point correlation function method, but that it was able to obtain constraints on the cosmological parameters explored.
