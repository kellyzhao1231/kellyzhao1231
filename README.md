## Hi, I'm Kelly Zhao

Undergrad at **Caltech** studying Applied & Computational Mathematics (4.1/4.0). I work on generative models, flow matching, and scientific ML.

Currently doing research at **Stanford's Vasanawala Lab** on accelerated MRI reconstruction with attention-based architectures and flow-matching diffusion.

### What I'm working on

**[MRI Reconstruction @ Vasanawala Lab](https://med.stanford.edu/vasanawalalab.html)** (Stanford, Summer 2026)
- Benchmarked U-Net and T-Net with self-attention, cross-attention, and hybrid variants for dual-echo water-fat MRI reconstruction
- T-Net Cross-Attention + data-consistency achieved 29.08 dB (Echo 0) and 32.63 dB (Echo 1) at R=10
- Designed a physics-informed fusion gate conditioning attention mixing weights on inter-echo phase difference
- Extended the backbone into a flow-matching diffusion denoiser with measurement-consistency guidance

**[FlowNP: Flow Matching Neural Processes](https://github.com/kellyzhao1231/project159)** (CS 159 Final Project)
- Transformer-based conditional flow-matching Neural Process, replacing Gaussian latent priors with learned ODE transport
- Beat 6 NPF baselines on GP regression and image completion; 19.0 dB PSNR on CelebA (5% context), 17.3 dB on MNIST (10%)
- Conditioned the flow on frozen Stable Diffusion VAE features via spatial cross-attention at 128x128

**TRS-RL** (Midas Intelligence)
- RL framework fine-tuning Qwen3.5-2B with GRPO on symbolic term rewriting over a custom DSL
- Lifted solve rates from 0-2.5% (zero-shot) to 80-96% across a 5-phase curriculum
- Built a SymPy-based symbolic verifier replacing LLM-judge scoring

**Mars Subsurface Ice Prediction** (NASA JPL)
- Trained gradient-boosted classifiers on 1,200+ Martian impact sites with spatial block cross-validation
- Calibrated probabilities via isotonic regression; results released to NASA's internal database

### Other

- 2x USAMO Qualifier (2022, 2023)
- Caltech Math Club -- coordinated 2025 & 2026 Caltech Math Meet
- Caltech Quant Club
- TA for Decidability & Tractability at Caltech

### Tools

`Python` `PyTorch` `Lean 4` `MATLAB` `LaTeX` `TensorFlow` `NumPy` `SymPy`

Flow Matching | Diffusion Models | VAEs | Attention Mechanisms | Reinforcement Learning (GRPO) | LLMs
