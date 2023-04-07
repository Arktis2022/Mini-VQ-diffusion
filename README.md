# MINI Vector-Quantized Discrete Absorbing Diffusion
Minimalist implementation of Vector-Quantized Discrete Absorbing Diffusion

The goal of this educational repository is to provide a self-contained, minimalistic implementation of Vector-Quantized Discrete Absorbing Diffusion using Pytorch.

All the code you need is in this notebook

In fact, the implementation mainly refers to the paper "Unleashing Transformers: Parallel Token Prediction with Discrete Absorbing Diffusion for Fast High-Resolution Image Generation from Vector-Quantized Codes": https://arxiv.org/pdf/2111.12701v1.pdf

I left out many details in order to highlight the main principles. The transformer in the original text is also replaced by a simple CNN

At present, the model can stably generate mnist and fashionmnist images, but the disadvantage is that the richness of generated images is insufficient. It's not clear why.

Replacing the CNN with a more complex structure and making the noise addition process more reasonable might solve this problem

For a more detailed implementation, please study the source code of the article: https://github.com/samb-t/unleashing-transformers

In addition, I also refer to https://github.com/cloneofsimo/minDiffusion and https://github.com/xiaohu2015/nngen
