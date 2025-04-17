#  Fully Connected Neural Network on Modified MNIST Datasets

This project implements a **PyTorch-based fully connected neural network (FCNN)** designed to tackle several variations of the MNIST handwritten digit dataset. With no convolutional layers, this network still achieves **over 98% accuracy** on standard MNIST and performs impressively on custom dataset variants.

---

##  Project Description

This repository contains:

-  A baseline FCNN trained on **standard MNIST**
-  Performance comparison across 4 datasets:
  1. **Standard MNIST** (50,000 training samples)
  2. **Low-data MNIST** (1,000 training samples)
  3. **Brightened MNIST** (pixel values altered via transformation)
  4. **Concatenated 3-digit MNIST** (multi-digit classification: 1,000 classes)
-  Visualization of **training curves** and **test results**
-  A full **IEEE-style paper** analyzing each scenario

---

##  Files Included

| File | Description |
|------|-------------|
| `DL MNIST Project 1.ipynb` | Jupyter notebook with model training and evaluation |
| `Implementing_A_Fully_Connected_Neural_Network_on_Modified_MNIST_Datasets.pdf` | Final report with methodology, results, and discussion |
| `DL_Project_1_Statement.pdf` | Original assignment statement |
| `Project_1_Dataset_X_Training.png` | Training loss and accuracy plots for each dataset |
| `Project_1_Dataset_X_Results.png` | Final performance results and score ratios for each dataset |

---

##  Sample Results

> These figures are referenced in the report and generated during training.  
> You can view them directly in this repository:

| Dataset | Results | Training Curves |
|--------|---------|------------------|
| Dataset 1 | ![D1 Results](Project%201_Dataset%201%20Results.png) | ![D1 Training](Project%201_Dataset%201%20Training.png) |
| Dataset 2 | ![D2 Results](Project%201_Dataset%202%20Results.png) | ![D2 Training](Project%201_Dataset%202%20Training.png) |
| Dataset 3 | ![D3 Results](Project%201_Dataset%203%20Results.png) | ![D3 Training](Project%201_Dataset%203%20Training.png) |
| Dataset 4 | ![D4 Results](Project%201_Dataset%204%20Results.png) | ![D4 Training](Project%201_Dataset%204%20Training.png) |

---

##  Key Takeaways

- Even without convolutional layers, the FCNN generalizes well on digit classification tasks.
- The model maintains **reasonable performance in low-data and high-class-count settings**.
- Score ratio (accuracy normalized by model size) is used to balance complexity vs. performance.

---

##  Citation

If you use this work or learn from it, consider citing the report or notebook and linking to this repository.

---

##  Tech Stack

- Python 3.10
- PyTorch
- Matplotlib / NumPy
- LaTeX (IEEEtran)

---

## Contact

**Blaine Swieder**  
bswieder@vols.utk.edu  
University of Tennessee, Knoxville

---

