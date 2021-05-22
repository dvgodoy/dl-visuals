# Initialization Schemes and Gradient Clipping

Shield: [![CC BY 4.0][cc-by-shield]][cc-by]

These images were originally published in the book ["Deep Learning with PyTorch Step-by-Step: A Beginner's Guide"](https://leanpub.com/pytorch).

They are also available at the book's official repository: [https://github.com/dvgodoy/PyTorchStepByStep](https://github.com/dvgodoy/PyTorchStepByStep).

## Index

- [Back](https://github.com/dvgodoy/dl-visuals)
- [Vanishing Gradients](#vanishing-gradients)
- [Initialization Schemes](#initialization-schemes)
    - [Comparing against BatchNorm](#comparing-against-batchnorm)
- [Gradient Clipping](#gradient-clipping)
    - [Value Clipping](#value-clipping)
    - [Norm Clipping](#norm-clipping)
    - [Using Hooks](#using-hooks)

### **** CLICK ON THE IMAGES FOR FULL SIZE ****

## Papers

- Xavier/Glorot Initialization: [Understanding the difficulty of training deep feedforward neural networks](http://proceedings.mlr.press/v9/glorot10a.html) by Glorot, X., Bengion, Y. (2010)
- Kaiming/He Initialization: [Delving Deep into Rectifiers: Surpassing Human-Level Performance on ImageNet Classification](https://arxiv.org/abs/1502.01852) by He, K. et al. (2015)

## Vanishing Gradients

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Initializations%20and%20Clipping/vanishing_violins.png)
*Source: [Chapter Extra](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/ChapterExtra.ipynb)*

## Initialization Schemes

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Initializations%20and%20Clipping/activations_init.png)
*Source: [Chapter Extra](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/ChapterExtra.ipynb)*

### Comparing against BatchNorm

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Initializations%20and%20Clipping/init_vs_bn.png)
*Source: [Chapter Extra](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/ChapterExtra.ipynb)*

## Gradient Clipping

### Value Clipping

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Initializations%20and%20Clipping/clip_value.png)
*Source: [Chapter Extra](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/ChapterExtra.ipynb)*

### Norm Clipping

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Initializations%20and%20Clipping/clip_norm.png)
*Source: [Chapter Extra](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/ChapterExtra.ipynb)*

### Using Hooks

![](https://raw.githubusercontent.com/dvgodoy/dl-visuals/main/Initializations%20and%20Clipping/gradients_clip_vs_hook.png)
*Source: [Chapter Extra](https://github.com/dvgodoy/PyTorchStepByStep/blob/master/ChapterExtra.ipynb)*

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
