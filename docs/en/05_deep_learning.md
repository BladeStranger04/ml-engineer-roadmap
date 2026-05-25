# 5. Deep Learning

> Russian version: [05_deep_learning.md](../ru/05_deep_learning.md)

> PyTorch is the default practical stack. TensorFlow still appears, but less often.

---

## Theory

- [ ] Fully connected networks, forward and backward pass
- [ ] Backpropagation, derived by hand
- [ ] Activations: ReLU, GELU, SiLU, sigmoid, tanh, softmax
- [ ] Losses: MSE, BCE, CrossEntropy, focal, contrastive
- [ ] Optimizers: SGD, Momentum, Adam, AdamW, Lion
- [ ] Regularization: dropout, batch norm, layer norm, weight decay, label smoothing
- [ ] Weight initialization: Xavier, He
- [ ] Vanishing and exploding gradients

---

## Architectures

### Computer vision
- [ ] CNNs: convolutions, pooling, receptive field
- [ ] LeNet, AlexNet, VGG, ResNet, EfficientNet
- [ ] Detection: YOLO, Faster R-CNN, DETR
- [ ] Segmentation: U-Net, Mask R-CNN
- [ ] Vision Transformer, Swin

### Sequences
- [ ] RNN, LSTM, GRU for historical context
- [ ] Seq2Seq, Attention
- [ ] Transformer as the main architecture

### Generative models
- [ ] Autoencoder, VAE
- [ ] GAN, WGAN, StyleGAN
- [ ] Diffusion: DDPM, Stable Diffusion, Kandinsky

---

## PyTorch stack

- [ ] PyTorch: `nn.Module`, autograd, custom datasets, DataLoader
- [ ] PyTorch Lightning for cleaner training code
- [ ] Hugging Face Transformers, Datasets, Accelerate
- [ ] `timm` for pretrained CV models
- [ ] Albumentations for augmentations
- [ ] Weights & Biases or TensorBoard for logging
- [ ] Mixed precision: `torch.amp`, `torch.compile`
- [ ] Distributed training with DDP
- [ ] GPU profiling

---

## Resources

| Resource | Level |
|---|:---:|
| [Neural Networks: Zero to Hero](https://karpathy.ai/zero-to-hero.html), Andrej Karpathy | *** |
| [Stanford CS231n](http://cs231n.stanford.edu/) | *** |
| [Stanford CS224n](https://web.stanford.edu/class/cs224n/) | *** |
| Deep Learning, Goodfellow, Bengio, Courville | *** |
| [Dive into Deep Learning](https://d2l.ai/) | ** |
| [PyTorch tutorials](https://pytorch.org/tutorials/) | ** |
| [fast.ai Practical Deep Learning](https://course.fast.ai/) | ** |

---

## Checkpoint projects

1. Implement an MLP and backpropagation from scratch with NumPy.
2. Train a ResNet-like model on CIFAR-100 and improve it with augmentations.
3. Fine-tune a pretrained model for your own task and deploy it with FastAPI.
