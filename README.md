# Convolutional Neural Network Example

Build a convolutional neural network with TensorFlow v2 to classify handwritten digits from the MNIST dataset.

## Requirements

- **Python**: 3.9 – 3.12
- **pip packages**: see `requirements.txt`

## Quick Start

```bash
# 1. Create a virtual environment (recommended)
python -m venv .venv

# 2. Activate it
#    Windows:
.venv\Scripts\activate
#    Linux / macOS:
source .venv/bin/activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Launch Jupyter / VS Code and open the notebook
jupyter notebook convolutional_network.ipynb
```

## GPU Support (Linux / WSL2)

For GPU acceleration, install TensorFlow with CUDA support:

```bash
pip install tensorflow[and-cuda]
```

This pulls the required CUDA libraries automatically. No manual CUDA / cuDNN installation is needed.
