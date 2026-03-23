# Rex: A JAX-Powered Framework for Sim-to-Real Robotics

Rex is a framework for developing and training robotic control policies, with a focus on bridging the simulation-to-reality gap. It leverages JAX for high-performance, differentiable simulation and learning, enabling rapid experimentation and robust policy transfer to physical hardware.

## Key Features
*   Differentiable physics simulation built on JAX for efficient gradient-based optimization.
*   Tools and utilities designed to address sim-to-real challenges like domain randomization.
*   Modular design for easy integration of new tasks, robot models, and learning algorithms.
*   Pre-built examples for common robotic benchmarking and training pipelines.

## Tech Stack
*   **JAX**
*   **Brax** (Physics Engine)
*   **Python**

## Getting Started
```bash
git clone https://github.com/zoreanuj/rex.git
cd rex
pip install -e .
# Run an example training script
python examples/train_brax_env.py
```