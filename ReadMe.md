# COMLGAN: Concurrent Optimisation via Mutual Learning GAN for Wear Defect Detection

[![Status](https://img.shields.io/badge/status-under%20review-yellow)](https://img.shields.io/badge/status-under%20review-yellow)
[![License](https://img.shields.io/badge/license-MIT-blue)](LICENSE)

## 📋 Overview

**COMLGAN** is a novel deep learning framework for automated detection and classification of wear defects on friction surfaces using Scanning Electron Microscope (SEM) micrographs. The architecture integrates an Auxiliary Classifier GAN (ACGAN) with a U-Net segmentation branch through concurrent optimisation and mutual learning mechanisms.

## ⚠️ Project Status

**This project is currently under academic review.**

- 📝 The full implementation will be publicly released after the peer-review process is complete
- 🔒 Some components (pre-trained models, complete dataset) are temporarily restricted
-  For research collaboration or early access inquiries, please contact the authors

## 📰 Paper Information

**Title:** Detecting Localized Wear on Friction Surfaces via Concurrent Optimisation and Mutual Learning in Generative Adversarial Network

**Journal:** *????* (Elsevier)

**Status:** Under Review

## 🎯 Graphical Abstract

![COMLGAN Graphical Abstract](graphical_abstract.png)

*Figure: COMLGAN architecture workflow showing the dual-branch design with mutual learning fusion for semantic segmentation of wear defects on SEM friction track images.*

## ✨ Key Features

- **Dual-Branch Architecture:** Combines adversarial learning (ACGAN) with semantic segmentation (U-Net)
- **Mutual Learning Mechanism:** Cross-regularization between branches for enhanced feature extraction
- **Concurrent Optimisation:** Joint training objective for spatial coherence and morphological accuracy
- **Multi-Class Detection:** Identifies adhesive, abrasive, fatigue cracks, and delamination wear mechanisms
- **Real-World Application:** Validated on continuous SEM friction tracks, not just isolated patches

## 🔧 Architecture

### U-Net Branch (Segmentation Generator)
- Encoder-decoder structure with skip connections
- Pixel-wise semantic segmentation
- Global spatial context preservation

### ACGAN Branch (Adversarial Generator + Classifier)
- High-frequency anomaly reconstruction
- Class label prediction
- Local feature discrimination

### Mutual Learning Fusion
- Bidirectional knowledge transfer
- Shared representations
- Concurrent joint objective optimization

## 📦 Installation

*Installation instructions will be provided after paper acceptance.*

```bash
# Placeholder - full requirements.txt will be available soon
# torch>=1.9.0
# torchvision>=0.10.0
# opencv-python>=4.5.0
# numpy>=1.19.0
# scikit-image>=0.18.0
