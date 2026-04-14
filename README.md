# Title: Correcting Defocus Blur in Microscopic Images Using Generative Deep Learning Models

## Abstract
Blur artifacts are common in images acquired through microscopy, particularly in biological applications where focus can vary locally. These degradations, often caused by physical or technical limitations during acquisition, compromise readability and the extraction of relevant information. In some cases, blur affects only a limited area of the field of view, making its correction even more challenging.
In this context, deep learning models offer promising avenues for automatic blur correction without human intervention. Architectures such as CycleGAN [4] enable learning image transformations between two domains (blurred ↔ sharp) without requiring perfectly aligned image pairs. More recently, denoising diffusion probabilistic models (DDPM) [6] have emerged as particularly robust and high-performing approaches for image generation and restoration.


Research question: How can unsupervised deep learning architectures, such as CycleGAN or DDPM, be adapted to effectively correct local blur present in microscopy images?


To address this, I divide my study into several stages. First, I evaluate existing architectures. I provide an in-depth analysis of the results obtained with the CycleGAN model, before testing the DDPM model. Finally, I attempt to improve the results obtained with CycleGAN using the COMI model [8]. All results are analyzed through quantitative metrics and qualitative visual evaluation. Throughout the project, I use the Mendeley parasite dataset [1] from an open cohort.


## Sources

### Datasets :
[1] Mendeley dataset: https://data.mendeley.com/datasets/m3jxgb54c9/4
[2] Facades dataset: https://www.kaggle.com/datasets/balraj98/facades-dataset
[3] Horse2zebra dataset: https://www.kaggle.com/datasets/balraj98/horse2zebra-dataset

### CycleGAN :
[4] Zhu, Park, Isola & Efros (2020). Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks (version 7): https://arxiv.org/abs/1703.10593 
[5] aitorzip. PyTorch-CycleGAN : https://github.com/aitorzip/PyTorch-CycleGAN

### DDPM :
[6] Jonathan Ho, Ajay Jain, Pieter Abbeel. Denoising Diffusion Probabilistic Models: https://arxiv.org/abs/2006.11239 
[7] lucidrainns. DDPM (Denoising Diffusion Probabilistic Model): https://github.com/lucidrains/denoising-diffusion-pytorch 

### COMI :
[8] Chi Zhang, Hao Jiang, Weihuang Liu, Junyi Li, Shiming Tang, Mario Juhas, Yang Zhang. Correction of out-of-focus microscopic images by deep learning: https://www.sciencedirect.com/science/article/pii/S2001037022001192 
[9] jiangdat. COMI (Correction of Out-of-focus Microscopic Images by Deep Learning): https://github.com/jiangdat/COMI

### Autre :
[10] Prafulla Dhariwal, Alex Nichol. Diffusion Models Beat GANs on Image Synthesis: https://arxiv.org/abs/2105.05233

