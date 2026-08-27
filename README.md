# PyTorch Demo

PyTorch neural network demonstrations and activities covering `nn.Sequential`, training loops with mini-batching and validation, and image classification on CIFAR-10.

## Quickstart

### Prerequisites

- [Git](https://git-scm.com/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- [VS Code](https://code.visualstudio.com/) with the [Dev Containers extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)

### 1. Fork and clone

1. Click **Fork** on [github.com/gperdrizet/pytorch-demo](https://github.com/gperdrizet/pytorch-demo) to create a copy under your own account.
2. Clone your fork locally:

```bash
git clone git@github.com:<your-username>/pytorch-demo.git
cd pytorch-demo
```

### 2. Open in a dev container

1. Open the cloned folder in VS Code
2. Open the VS Code Command Palette (`Ctrl+Shift+P` / `Cmd+Shift+P`) and run **Dev Containers: Reopen in Container**.
3. Select the configuration that matches your hardware:

| Configuration | Use when |
|---|---|
| `DeepLearning NVIDIA` | Linux/Windows with an NVIDIA GPU |
| `DeepLearning CPU` | Linux/Windows, CPU only |
| `DeepLearning Mac` | Apple Silicon (M1/M2/M3) Mac |

VS Code will pull the container image and install all dependencies automatically.

### 3. Run the notebooks

Open any notebook from the `notebooks/` folder and run cells with the kernel provided by the container.

---

## Notebooks

| Notebook | Description |
|---|---|
| `lesson-29-demo.ipynb` | **Demo part 1**: Introduces `nn.Sequential` and a basic PyTorch training loop using a tabular housing dataset. Covers tensor preparation, model definition, loss and optimizer setup, and evaluation on a test set. |
| `lesson-29-activity-part1.ipynb` | **Activity 1**: Extends the demo training loop to add mini-batch processing via `DataLoader` and validation tracking. Solution in `lesson-29-activity-part1-solution.ipynb`. |
| `lesson-29-activity-part2.ipynb` | **Activity 2**: Guided exercise to define, train, and evaluate a DNN classifier for CIFAR-10. Data loading and preparation are provided; the model architecture and training loop are left for you to implement. Solution in `lesson-29-activity-part2-solution.ipynb`. |
