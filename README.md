# Breaking the Privacy Promise: Gradient Inversion Attacks on Federated Low-Rank Adapted Vision Transformers

**WACV 2027**

Ritik K. Badiya, Siladittya Manna, Ashmit Sinha, Yashwanth Mandula, Anirban Chakraborty
Indian Institute of Science, Bengaluru

[Project Page](https://vcl-iisc.github.io/lora_gia_trpe/) · [Paper](static/pdf/paper.pdf) · [Code](https://vcl-iisc.github.io/lora_gia_trpe_code/)

Federated LoRA fine-tuning of ViTs shares only low-rank gradients, but that does not prevent data leakage. Making positional embeddings trainable in every transformer block gives an honest-but-curious server layer-wise spatial anchors. Combined with a generative prior, these anchors let the server reconstruct private images with high fidelity. On CIFAR-10, adding the anchors to GIAS raises reconstruction PSNR by 10.14 dB over GIAS alone.

This repository hosts the project page.
