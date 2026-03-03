# Practice 1 - CNNs (Deep Learning, MIA 2025-2026)

## Objective

Develop several CNN models to classify images from the **STL-10** dataset (10 classes, 96×96 color images).

## Structure

| Notebook | Description |
|----------|-------------|
| `01_Custom_CNNs.ipynb` | **Part 1** — Custom CNN architectures (baseline, improved, ResNet-style, Inception-style) |
| `02_Pretrained_CNNs.ipynb` | **Part 2** — Pretrained models with feature extraction and fine-tuning (VGG16, ResNet50, MobileNetV2) |

## Dataset

- **STL-10**: 5,000 training + 8,000 test images across 10 classes
- Loaded via `tensorflow_datasets`

## Requirements

```
tensorflow
tensorflow-datasets
keras
numpy
matplotlib
pandas
```