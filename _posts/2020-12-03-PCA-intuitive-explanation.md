---
title: "PCA Intuitively Explained"
categories:
  - Unsupervised Learning
  - Intuitively Explained
tags:
  - Unsupervised Learning
  - Dimensionality Reduction
  - PCA
  - Intuitively Explained
---

# Example Case: Application of PCA to the Hand-written Digits Dataset
Start by loading the Hand-written Digitis dataset using the `sklearn` library.

> This dataset is made up of 1797 8x8 images. Each image, like the one shown below, is of a 
> hand-written digit. In order to utilize an 8x8 figure like this, we’d have to first transform 
> it into a feature vector with length 64. [Scikit-Learn | Examples | Dataset examples | The Digit Dataset](https://scikit-learn.org/stable/auto_examples/datasets/plot_digits_last_image.html#sphx-glr-auto-examples-datasets-plot-digits-last-image-py) 

asdasd

```python
from sklearn.datasets import load_digits
digits = load_digits()
digits.data.shape
```
(1797, 64)





**Warning Notice:** Lorem ipsum dolor sit amet, consectetur adipiscing elit. [Integer nec odio](#). Praesent libero. Sed cursus ante dapibus diam. Sed nisi. Nulla quis sem at nibh elementum imperdiet.
{: .notice--warning}
