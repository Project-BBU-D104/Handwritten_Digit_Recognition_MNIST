# Handwritten Digit Recognition with MNIST


Build a convolutional neural network with TensorFlow v2 to classify handwritten digits from the MNIST dataset.

Based on the official TensorFlow examples: https://github.com/aymericdamien/tensorflow-examples

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

For GPU acceleration, install TensorFlow v2 with CUDA support:

```bash
pip install tensorflow[and-cuda]
```

This pulls the required CUDA libraries automatically. No manual CUDA / cuDNN installation is needed.

For more details about TensorFlow installation, you can check [TensorFlow Installation Guide](https://www.tensorflow.org/install/)