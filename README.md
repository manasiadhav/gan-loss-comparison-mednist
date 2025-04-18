# GAN Loss Function Comparison using MedNIST

This project compares the impact of three different GAN loss functions on medical image generation using the MedNIST dataset.

## Loss Functions Compared

- **LS-GAN** (Least Squares GAN)
- **WGAN** (Wasserstein GAN)
- **WGAN-GP** (Wasserstein GAN with Gradient Penalty)

## Evaluation Metrics

- Inception Score (IS)
- Fréchet Inception Distance (FID)
- Visual Inspection (side-by-side samples)

## Directory Structure

- `data/`: Dataset loading scripts
- `models/`: GAN architecture and training logic
- `outputs/`: Generated image samples and saved models
- `evaluation/`: Metric implementations and evaluation outputs
- `tensorboard_logs/`: Logs for real-time monitoring via TensorBoard

## ▶️ Run the Code

```bash
pip install -r requirements.txt
python main.py
