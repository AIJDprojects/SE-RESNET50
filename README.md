# Squeeze-and-Excitation Networks (SENet) Implementation

This repository contains an implementation of **Squeeze-and-Excitation Networks (SENet)**, the award-winning architecture that achieved **1st place in ILSVRC 2017** with a top-5 error of only 2.251%. The SE block is a novel architectural unit that adaptively recalibrates channel-wise feature responses by explicitly modeling interdependencies between channels.

## Paper Reference
This work is based on the original research:  
**Squeeze-and-Excitation Networks**  
[Jie Hu](https://github.com/hujie-frank), Li Shen, Samuel Albanie, Gang Sun, Enhua Wu  
*IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*  
[arXiv:1709.01507](https://arxiv.org/abs/1709.01507) | [Official GitHub](https://github.com/hujie-frank/SENet)


## Key Concept: SE Block

The SE block operates through two simple operations:

   Squeeze
    Global average pooling to aggregate spatial information into a channel descriptor

   Excitation
    A self-gating mechanism using fully-connected layers to capture channel-wise dependencies

https://github.com/hujie-frank/SENet/raw/master/figures/SE-Inception-module.jpg
Figure from original paper showing SE block integration
Implementation Highlights

This repository includes:

✅ Modular SE block implementations for popular architectures (ResNet, Inception, etc.)

✅ Training/evaluation scripts for ImageNet and other datasets

✅ Pre-trained models and benchmarking tools

✅ Efficient GPU-accelerated operations

Acknowledgments

This implementation builds upon the original work by:

  Jie Hu et al. for the SENet paper and official implementation
