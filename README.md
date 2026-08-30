# Learning PyTorch

This repository is a personal learning project for PyTorch, with a focus on computer vision and object detection workflows.

## Project structure

- `Computer Vision/`
  - `Cifar10.ipynb` for CIFAR-10 image classification experiments
  - `object-detection-transfer.ipynb` for transfer learning object detection work
  - `object-detection-transfer-learning-rate-schedule.ipynb` for learning-rate scheduling experiments
  - `BCCD_Dataset/` contains local dataset files used for object detection examples and is excluded from version control

## Environment setup

1. Create a virtual environment:
   ```bash
   python -m venv .venv
   ```
2. Activate it:
   ```bash
   source .venv/bin/activate
   ```
3. Install the required dependencies:
   ```bash
   pip install torch torchvision torchaudio jupyter matplotlib pandas
   ```
4. Start Jupyter:
   ```bash
   jupyter notebook
   ```

## Notes

- This repo is intended for experimentation and learning rather than production deployment.
- Large local datasets and generated artifacts should stay outside version control.
- Notebooks are organized by topic, and the object detection examples are the main focus of the current work.
