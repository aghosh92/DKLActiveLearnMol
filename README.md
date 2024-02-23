# DKLActiveLearnMol

This repository includes notebooks and datasets to illustrate how Deep Kernel Learning (DKL), compared to traditional variational autoencoders can be used for molecular datasets such as QM9 dataset for molecular design and property predictions via structured latent spaces related to targets. 

Notebook
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aghosh92/DKLActiveLearnMol/blob/main/Notebooks/notebookI.ipynb)
shows how we can explore the latent space generated by a traditional variational autoencoder (VAE) for molecules. The VAEs build latent spaces based on the data only.

Notebook
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aghosh92/DKLActiveLearnMol/blob/main/Notebooks/notebookII.ipynb)
shows how to explore the latent space generated by a deep kernel learning (DKL) model for molecules. This approach gives a better structured latent spaces compared to those generated by traditional variational autoencoders (VAEs). DKL builds latent space based on the features and target.

Notebook
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/aghosh92/DKLActiveLearnMol/blob/main/Notebooks/notebookIII.ipynb)
explore how Deep Kernel Learning (DKL) can be applied to molecular dataset, or can be built as an active experiment where the features (molecular structures) are available all at the same time, and the targets are becoming available sequentially. It provides a way to guide 'experimental' discovery, and also forms particularly well organized latent spaces.

The sampled datasets are provided in the datasets folder.
