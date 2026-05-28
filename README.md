# IDS Adversarial Traffic Generation using WGAN
Overview

This project focuses on generating adversarial network traffic samples using a Wasserstein Generative Adversarial Network (WGAN) to evaluate and bypass Machine Learning-based Intrusion Detection Systems (IDS).

The objective is to simulate how adversarial attacks can evade IDS models by modifying non-functional network traffic features while preserving the original malicious behavior.

The project includes:

WGAN-based adversarial sample generation
IDS evaluation and testing
Loss visualization and performance analysis
Research-oriented experimentation for cybersecurity and AI security
Project Objectives

The main goals of this project are:

Generate adversarial network traffic samples using WGAN
Evaluate IDS robustness against adversarial attacks
Analyze IDS detection degradation under adversarial conditions
Study GAN stability and convergence in cybersecurity datasets
Explore adversarial machine learning techniques in network security
Basic Steps
1. Install Requirements

Install all required libraries from requirements.txt.

2. Prepare Dataset

Configure and preprocess the dataset in:

data.py

Make sure the dataset path is correct before training.

3. Train IDS Model

Run:

train_ids.py

Or train all IDS models:

train_all_ids.py
4. Train WGAN

Run:

train_wgan.py

This step trains the adversarial traffic generator.

5. Test Generated Adversarial Samples

Run:

test_wgan.py

This evaluates generated adversarial traffic.

6. Test IDS Performance

Run:

test_ids.py

Or test all IDS models:

test_all_ids.py
Output Files

Training and testing results will generate:

Loss plots
Evaluation metrics
IDS performance graphs

Example output files:

test_dos_loss_plot.png
testprobe_loss_plot.png
goc dos.png
Notes
Ensure the dataset is preprocessed correctly before training.
GAN training may require multiple epochs for stable results.
Recommended environment:
Python 3.10+
CUDA-enabled GPU (optional but recommended)
Check file paths before running the scripts.
