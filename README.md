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

## Installation  

### Prerequisites  
- Python 3.8+  
- PyTorch  
- [SNNtorch](https://github.com/jeshraghian/snntorch)  

### Setup  
Clone the repository:  
```bash
git clone https://github.com/yourusername/Watermarking-SNNs.git
cd Watermarking-SNNs
