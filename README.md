# Enhancing SAR Automatic Target Recognition with ATG-GAN

A GAN-based deep learning pipeline that generates synthetic SAR target samples to overcome training data scarcity in Automatic Target Recognition (ATR) systems.

📄 **Published in IEEE SSITCON 2024:** https://ieeexplore.ieee.org/document/10796276

## Problem
ATR systems for Synthetic Aperture Radar (SAR) imagery need large amounts of labelled data, which is hard to obtain. This project uses a Generative Adversarial Network to augment the training data and improve classification.

## Approach
- Proposed the **ATG-GAN** model for SAR ATR
- Adversarial training and deep feature extraction
- Custom loss function optimization
- Data preprocessing, model training and evaluation

## Tech Stack
Python, TensorFlow, NumPy, Pandas, GAN

## Results
- Generated **500+ synthetic SAR target samples**
- **95% classification accuracy**
- **20% overall model improvement**
- **15% reduction in false positives**
- **60% increase in training sample diversity**
- Outperformed traditional ATR methods

## Dataset
[EDIT: name of the SAR dataset you used and where to download it]

## Project Structure
[EDIT: list your main files, e.g. preprocessing.py, model.py, train.py, evaluate.py]

## How to Run
1. Clone the repo: `git clone https://github.com/Tharunkumar27/[EDIT: repo-name].git`
2. Install dependencies: `pip install tensorflow numpy pandas`
3. [EDIT: command to train, e.g. `python train.py`]
4. [EDIT: command to evaluate, e.g. `python evaluate.py`]

## Author
Tharunkumar S | tharunsundaraj016@gmail.com
