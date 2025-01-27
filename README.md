
# Creating Sample Datasets from Large Datasets

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)

A step-by-step guide to creating smaller, manageable datasets from large datasets using **Flickr30k** as an example. Perfect for prototyping image-captioning models or testing pipelines without overwhelming computational resources.

---

## 📖 Overview

This repository demonstrates how to programmatically extract a **subset of images and their captions** from a large dataset while preserving the original structure. The example uses the [Flickr30k dataset](https://www.kaggle.com/datasets/hsankesara/flickr-image-dataset), but the code can be adapted to other datasets (e.g., COCO, custom datasets) with minimal changes.

**Key Features**:
- 🎯 **Random Sampling**: Select `N` random images from a large dataset.
- 📂 **Structure Preservation**: Copy images and their corresponding captions to a new directory.
- 🖼️ **Visualization**: Display sample images with captions for verification.
- 🔄 **Reproducibility**: Fix random seeds for consistent sampling across runs.

---

## 🛠️ Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/sayemuzzamansiam/Creating-Sample-Datasets-from-Large-Datasets.git
   cd Creating-Sample-Datasets-from-Large-Datasets
