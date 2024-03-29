**ASSIGNMENT 9**

In this assignment, we will learn to deform an initial shape (e.g. sphere) to fit a target shape. Starting from a sphere mesh, we learn the offset to each vertex in the mesh such that the predicted mesh is closer to the target mesh at each optimization step. 

**The goals of this practice are the following:**

-   Use different PyTorch3D mesh loss functions
-   Set up an optimization loop
-   Evaluate optimization results
-   Reason about advantages and limitations of the method

### Instructions:
If you’re using Google Colab, you just need to have a google account and an associated Google Drive. Make a copy of the notebook located below and modify it as requested.

In case you’re choosing to work locally in your machine you must set Anaconda or a `venv` virtual environment, and install the necessary libraries. Create a folder in your Google Drive or in your machine’s workspace. Copy to your drive folder or download the following notebook:

[Assignment 9 Notebook](https://colab.research.google.com/github/hallpaz/3dsystems23/blob/main/assignments/lab9_deforming_meshes.ipynb)
<a href="https://colab.research.google.com/github/hallpaz/3dsystems23/blob/main/assignments/lab9_deforming_meshes.ipynb" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>

1. Follow the instructions in the notebook for completing the assignment.
2. If you want, you can build auxiliary .py scripts and call them from your notebook, for organizational purposes.

### Submission 

The assignment is due on May 29th, 2023 at 11:59pm (GMT-3).

Students should send their assignments before the due date to hallpaz@impa.br with a copy to lvelho@impa.br. Late delivers will be consider subject to a lower score.

The submission email should be sent with the subject “Assignment 9 - [first-name] - [last-name]”. The assignment can be structured and sent in two ways:

If your whole solution is implemented in the same notebook as the one provided for the assignment, then you can send just the .ipynb file as the solution. If parts of your implementation were done in auxiliary .py scripts, then you must send both the final notebook and the scripts inside a .zip file. The organization of the code will also be considered in the evaluation.

### References:

1. [PyTorch3d website](https://pytorch3d.org)
2. PyTorch3D [source code for Meshes](https://github.com/facebookresearch/pytorch3d/blob/master/pytorch3d/structures/meshes.py) data structure.
3. [Pixel2Mesh: Generating 3D Mesh Models from Single RGB Images](https://arxiv.org/abs/1804.01654)
4. [Mesh R-CNN](https://arxiv.org/abs/1906.02739)
5. [Exploring the PyTorch3D Library](https://hallpaz.github.io/3dsystems20/assignment1.html)
