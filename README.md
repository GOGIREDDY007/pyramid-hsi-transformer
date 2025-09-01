# Pyramid Hierarchical Spatial-Spectral Transformer for Hyperspectral Image Classification

This repository implements a **Pyramid Hierarchical Spatial-Spectral Transformer (PHSS-Transformer)** for hyperspectral image (HSI) classification.  
The model leverages **spatial-spectral attention** and **hierarchical feature learning** to achieve high accuracy on benchmark datasets such as *Indian Pines* and *Pavia University*.  

---

## 🚀 Features
- Transformer-based architecture tailored for hyperspectral data
- Pyramid hierarchical representation learning
- Spatial-spectral attention mechanism
- Evaluation on benchmark hyperspectral datasets
- Reproducible results with metrics and visualizations

---

## 📂 Repository Structure
```bash
pyramid-hsi-transformer/
│── main.py                        # Original implementation
│── README.md                      # Project documentation
│── requirements.txt                # Dependencies
│
├── metrics/                        # Model evaluation metrics & plots
│   ├── distribution_plot.png
│   ├── inputimage_map.png
│   ├── outputimage_map.png
│   └── pixelsignature_plot.png
│
├── results/                        # Classification results & comparisons
│   ├── groundtruth_map.png
│   ├── classification_map.png
│   └── confusion_matrix.png
│


