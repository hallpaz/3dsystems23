**Laboratory Class 12**

In this class, we will understando how PyTorch3D implements a differentiable rendering for meshes and pointclouds.

**Our goals are to understand the following:**

- PyTorch3D's adaptation of Soft Rasterizer for meshes.
- PyTorch3D's integration of Pulsar renderer for pointclouds 
- How to set up a renderer effectively in PyTorch3D

[Demo  Notebook](https://colab.research.google.com/github/hallpaz/3dsystems23/blob/main/assignments/lab12_differentiable_rendering_demo.ipynb.ipynb)
<a href="https://colab.research.google.com/github/hallpaz/3dsystems23/blob/main/assignments/lab12_differentiable_rendering_demo.ipynb.ipynb" target="_blank"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>


### References:

1. PyTorch3D: [Getting Started with Renderer](https://pytorch3d.org/docs/renderer_getting_started)
2. Source code for standard shaders in PyTorch3D: https://github.com/facebookresearch/pytorch3d/blob/main/pytorch3d/renderer/mesh/shader.py
2. Source code for points rasterizer in PyTorch3D: https://github.com/facebookresearch/pytorch3d/blob/main/pytorch3d/renderer/points/rasterizer.py
2. OpenDR: An Approximate Differentiable Renderer [paper](https://files.is.tue.mpg.de/black/papers/OpenDR.pdf)
3. Neural 3D Mesh Renderer - [paper](https://arxiv.org/pdf/1711.07566.pdf)
4. Soft Rasterizer: A Differentiable Renderer for Image-based 3D Reasoning - [paper](https://arxiv.org/pdf/1904.01786.pdf)
5. Pulsar: Efficient Sphere-based Neural Rendering [paper](https://arxiv.org/abs/2004.07484)