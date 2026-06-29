# PyTorch Learning

Notebook-based PyTorch practice covering tensors, data handling, model training loops, linear regression, and neural-network classification fundamentals.

This repository is intentionally a learning track, not a polished production app. It shows the progression from PyTorch basics to model-building patterns that are useful for AI/ML engineering roles.

## What This Covers

- Tensor creation, shapes, indexing, reshaping, matrix operations, and device placement.
- PyTorch workflow for data splitting, model definition, loss functions, optimizers, training, and inference.
- Linear regression from scratch using `torch.nn.Module`.
- Binary classification with neural networks on synthetic circular data.
- Evaluation using loss curves, predictions, accuracy, and decision-boundary visualization.
- Reusable training-loop structure: forward pass, loss calculation, backpropagation, optimizer step, and evaluation mode.

## Repository Structure

| File | Focus |
|---|---|
| `pytorch_Learning.ipynb` | Core tensor operations and PyTorch fundamentals. |
| `01_pytorch_learning.ipynb` | End-to-end linear regression workflow with train/test split and model parameter learning. |
| `02_Neural_network_Classification.ipynb` | Neural-network classification experiments using `make_circles`, PyTorch models, loss functions, optimizers, and decision-boundary helpers. |

## Tech Stack

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- Jupyter Notebook

## How To Run

1. Clone the repository:

```bash
git clone https://github.com/yg36/PyTorch-Learning.git
cd PyTorch-Learning
```

2. Create and activate a virtual environment:

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

macOS/Linux:

```bash
source .venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Start Jupyter:

```bash
jupyter notebook
```

Then open the notebooks in order:

1. `pytorch_Learning.ipynb`
2. `01_pytorch_learning.ipynb`
3. `02_Neural_network_Classification.ipynb`

## Notes

- The classification notebook downloads helper plotting functions from Daniel Bourke's public PyTorch learning repository when needed.
- Some saved notebook outputs reflect experiments and learning checkpoints, including models that underfit. That is intentional because the repo documents learning progression, not only final results.
- GPU is optional. The notebooks can run on CPU for these small examples.

## Recruiter-Relevant Signal

This repo shows hands-on PyTorch fundamentals: tensors, `nn.Module`, loss functions, optimizers, training loops, inference mode, and classification workflows. It supports the deeper applied AI/ML projects in my portfolio by showing the foundation behind model implementation.

<!-- repository-refresh: 2026-06-29 | preserved-order-rank: 003/71 -->
