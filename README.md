# DL Assignment 2: Neural Networks, CNNs, and VGG-13

A set of Jupyter notebooks that build from a basic neural network to a convolutional neural network and a VGG‑13 implementation, including optimization techniques and experiments.

## Notebooks
- 01_basic_neural_network.ipynb — Build a simple feedforward NN
- 02_nn_optimization.ipynb — Train/optimize with improved techniques
- 03_building_cnn.ipynb — Implement and evaluate a CNN
- 04_vgg13_implementation.ipynb — VGG‑13 model implementation and experiments

## Data
- datasets/ — Input data used by the notebooks
  - datasets/cnn_dataset/ — Image data for CNN/VGG experiments
  - datasets/dataset.csv — Tabular/sample data (if used by Part I/II)

## Quick Start
1. Create and activate a virtual environment (optional but recommended):
   - Windows: `python -m venv .venv && .venv\Scripts\activate`
   - macOS/Linux: `python3 -m venv .venv && source .venv/bin/activate`
2. Install common dependencies:
   `pip install jupyter numpy matplotlib pandas scikit-learn torch torchvision torchaudio`
3. Launch Jupyter and open the notebooks:
   `jupyter lab` (or `jupyter notebook`)

## Suggested Order
1. 01_basic_neural_network.ipynb
2. 02_nn_optimization.ipynb
3. 03_building_cnn.ipynb
4. 04_vgg13_implementation.ipynb

## Notes
- Some notebooks may assume the presence of the image dataset under `datasets/cnn_dataset/`.
- GPU acceleration (if available) can speed up CNN/VGG training considerably.