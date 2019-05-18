This is a **[PyTorch](https://pytorch.org) Implementation of Object Detection**.

Basic knowledge of PyTorch, convolutional neural networks is needed.

If any Questions, suggestions, or corrections please post as issues.

I'm using `PyTorch 0.4` in `Python 3.7`.

# Objective

**To build a model that can detect and localize specific objects in images.**

# Concepts

* **Object Detection**. 

* **Single-Shot Detection**. Earlier architectures for object detection consisted of two distinct stages – a region proposal network that performs object localization and a classifier for detecting the types of objects in the proposed regions. 

* **Multiscale Feature Maps**. In image classification tasks, we base our predictions on the final convolutional feature map – the smallest but deepest representation of the original image. In object detection, feature maps from intermediate convolutional layers can also be _directly_ useful because they represent the original image at different scales. Therefore, a fixed-size filter operating on different feature maps will be able to detect objects of various sizes.
