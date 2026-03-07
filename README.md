# DL Algorithms

This repo contains a set of DL algorithms implemented from first principles. These notebooks help to understand the inner workings of modern DL libraries such as Pytorch and Tensorflow. Detailed analysis and comparisons are provided along with the code.

## Algorithms Implemented
**Neural Nets**
- [x] MLP: Multi-Layer Perceptron
- [ ] CNN: Convolutional Neural Network
- [ ] RNN: Recurrent Neural Network
- [ ] GRU: Gated Recurrent Unit
- [ ] LSTM: Long Short-Term Memory
- [ ] GNN: Graph Neural Network

**Representation Learning**
- [ ] Auto Encoders
- [ ] VAE: Variational Autoencoder
- [ ] Contrastive Learning

**Attention**
- [ ] Attention Mechanism & Positional Embedding
- [ ] Transformer
- [ ] minGPT
- [ ] Vision Transformer

**Generative Models**
- [ ] GAN: Generative Adversial Network
- [ ] Diffusion
- [ ] Flow Matching

**Frontiers**
- [ ] MAMBA

## Setup
> This project uses `uv` as the package/environment manager. Install it from [here](https://docs.astral.sh/uv/getting-started/installation/).

```bash
git clone https://github.com/nveshaan/dl_scratch.git
cd dl_scratch
uv sync
```

To update the cloned repo,
```bash
git pull
uv sync
```

## Acknowledgements

MLP implementation is inspired from https://youtu.be/w8yWXqWQYmU?si=1PH7D9MPgnT7uYXU and https://www.youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi
