# Watermarking Neuromorphic Brains: Intellectual Property Protection in Spiking Neural Networks

This repository contains the implementation of the watermarking techniques proposed in the paper:

**[Watermarking Neuromorphic Brains: Intellectual Property Protection in Spiking Neural Networks](https://ieeexplore.ieee.org/abstract/document/10766558)**  
by [Hamed Poursiami](https://scholar.google.com/citations?user=4n2kpIwAAAAJ&hl=en), Ihsen Alouani, and Maryam Parsa.

## Overview  
As Spiking Neural Networks (SNNs) become more widely used in neuromorphic computing, protecting their intellectual property (IP) is crucial. This repository explores two primary watermarking approaches:  

- **Fingerprint-based watermarking** (adversarial frontier stitching)
- **Backdoor-based watermarking** (trigger pattern insertion)  

We evaluate their impact on model fidelity, resilience against attacks, and applicability to SNNs.

## Features  
- Implementation of **fingerprinting and backdoor watermarking** for SNNs  
- Benchmarking on **MNIST** with Spiking Neural Networks  
- Evaluation of watermark robustness against **fine-tuning and compression attacks**  
- PyTorch-based implementation with **SNNtorch** for neuromorphic computing  


## 🛠 Requirements

The code is written in **Python** and requires the following libraries:

- 🏋 **[PyTorch](https://pytorch.org/)**
- ⚡ **[SNNTorch](https://snntorch.readthedocs.io/en/latest/)**
- 🎯 **[Tonic](https://tonic.readthedocs.io/en/latest/)**



You can install the required libraries using pip:

```bash
pip install pytorch snntorch tonic 
```



