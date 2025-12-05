# Machine-Learning-and-NN-in-Imaging

This repository contains a complete machine-learning pipeline for solving imaging inverse problems. It includes modules for defining the physical forward operator, implementing reconstruction algorithms with priors and data-fidelity terms, generating synthetic datasets, training a deep denoiser (DnCNN) for Plug-and-Play optimization, and developing an unfolded neural network that integrates physics and learning. The notebooks illustrate each stage with code, experiments, and visual results.

Through a sequence of Jupyter notebooks, the project demonstrates how to:
1. Model physical image acquisition using linear operators
2. Implement reconstruction methods combining data fidelity + prior terms
3. Generate datasets tailored to inverse problems
4. Train a deep learning denoiser suitable for Plug-and-Play (PnP) algorithms
5. Build and test an unfolded network, where optimization steps are mapped into a learned architecture
   
The workflow reflects modern approaches in computational imaging, where physics-based models and neural networks are combined to achieve high-quality reconstructions under noisy or incomplete measurements. Each notebook focuses on a specific component of this pipeline, making the project modular and easy to extend.

How to Use This Repository
Start with the physics operator to understand how measurements are simulated.
Run the reconstruction notebook to explore classical methods.
Generate datasets tailored to your reconstruction task.
Train the denoiser for PnP or as a building block for learning pipelines.
Experiment with the unfolded network, modifying components or extending the architecture.
