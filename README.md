# 🧠 Synthetic Brain Tumor Generation Pipeline

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Medical Imaging](https://img.shields.io/badge/Domain-Medical%20Imaging-red)
![Status](https://img.shields.io/badge/Status-Research-green)
![Notebook]([https://img.shields.io/badge/Format-Jupyter-orange](https://colab.research.google.com/drive/1wRtTsK_GxLGo8MXoc7keIgT_eXmtrpta?usp=sharing))

> **A medical imaging pipeline for generating realistic synthetic brain tumors in MRI volumes**  
> Designed for **data augmentation, model robustness, and medical AI research**.

---

## ✨ Overview

This project provides a **3D synthetic tumor generation framework** for brain MRI scans using:

- 🧬 Morphological operations  
- 🌊 Gaussian smoothing & deformation  
- 🧠 Neuroimaging libraries (ANTs, NiBabel, Nilearn)  
- 🎨 Interactive visualization with Plotly  

The generated tumors can be seamlessly fused into real MRI volumes, making the dataset suitable for:
- Tumor segmentation
- Tumor detection
- Synthetic data augmentation
- Medical deep learning experiments

---

## 🔬 Key Features

✅ Realistic 3D tumor shape synthesis  
✅ Smooth anatomical blending  
✅ Multi-stage morphological refinement  
✅ NIfTI-compatible medical imaging  
✅ Interactive 3D visualizations  
✅ Plug-and-play with deep learning pipelines  

---
git clone https://github.com/your-username/synthetic-tumor-generation.git

cd synthetic-tumor-generation

jupyter notebook synthetic_tumor.ipynb

## 🧱 Pipeline Architecture

```text
MRI Volume
   │
   ├── Random Tumor Seed Generation
   │
   ├── Morphological Expansion
   │     ├── Erosion
   │     ├── Closing
   │
   ├── Gaussian Smoothing
   │
   ├── Intensity Blending
   │
   └── Synthetic Tumor MRI Output
📁 synthetic-tumor-generation/
│
├── 📓 synthetic_tumor.ipynb   # Main pipeline notebook
├── 📄 README.md               # Project documentation
├── 📄 requirements.txt        # Dependencies
└── 📁 outputs/
    └── synthetic_mri.nii.gz


