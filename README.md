# DC-VideoGen: Efficient Video Generation with Deep Compression Video Autoencoder

## Abstract

We introduce DC-VideoGen, a post-training acceleration framework for efficient video generation. DC-VideoGen can be applied to any pre-trained video diffusion model, improving efficiency by adapting it to a deep compression latent space with lightweight fine-tuning. The framework builds on two key innovations: (i) a **Deep Compression Video Autoencoder** with a novel chunk-causal temporal design that achieves $32\times$/$64\times$ spatial and $4\times$ temporal compression while preserving reconstruction quality and generalization to longer videos; and (ii) **AE-Adapt-V**, a robust adaptation strategy that enables rapid and stable transfer of pre-trained models into the new latent space. Adapting the pre-trained Wan-2.1-14B model with DC-VideoGen requires only 10 GPU days on the NVIDIA H100 GPU. The accelerated models achieve up to $14.8\times$ lower inference latency than their base counterparts without compromising quality, and further enable $2160\times 3840$ video generation on a single GPU. 

## Release
- The code and pretrained models will be released after the legal review is completed.
