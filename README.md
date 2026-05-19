# MuralDH Segmentation Subset

> A reorganized subset of the MuralDH dataset for mural damage segmentation research.

## 📋 Overview

This repository provides a reorganized version of the **damage segmentation subset** from the [MuralDH dataset](https://github.com/tearsheaven/MuralDH). The original dataset contains 961 images with pixel-level damage annotations (cracks, flaking, fading).

This version retains only the segmentation subset and re-splits it into **train**, **val**, and **test** sets for easier model development and benchmarking.

## 📥 Download

The dataset is hosted on Google Drive. Click the link below to download:

🔗 **[Download MuralDH Segmentation Subset (Reorganized)](https://drive.google.com/drive/folders/1JtnCo4jUZmYeHAm2GrCp2P7aCWMafHwN?usp=sharing)**

## 📊 Dataset Split

| Split      | Number of Images |
|------------|------------------|
| Train      | 761              |
| Val        | 100              |
| Test       | 100              |
| **Total**  | **961**          |

## 📁 Directory Structure

After downloading and extracting the dataset, you will find the following structure:

MuralDH-Segmentation-Subset/
├── train/
│ ├── images/ # training mural images (761)
│ └── labels/ # corresponding damage masks (761)
├── val/
│ ├── images/ # validation mural images (100)
│ └── labels/ # validation masks (100)
├── test/
│ ├── images/ # test mural images (100)
│ └── labels/ # test masks (100)

All images are in PNG format with size `512×512` pixels. Masks are binary images where pixel value `1` (or `255`) indicates damaged area, and `0` indicates intact area.

## 📝 Citation

If you use this dataset in your research, please cite the original paper:

> Zishan Xu, Yuqing Yang, Qianzhen Fang, Wei Chen, Tingting Xu, Jueting Liu, & Zehua Wang. (2024). *A comprehensive dataset for digital restoration of Dunhuang murals*. Scientific Data.  
> **Original repository**: [https://github.com/tearsheaven/MuralDH](https://github.com/tearsheaven/MuralDH)

BibTeX:
```bibtex
@article{xu2024comprehensive,
  title={A comprehensive dataset for digital restoration of Dunhuang murals},
  author={Xu, Zishan and Yang, Yuqing and Fang, Qianzhen and Chen, Wei and Xu, Tingting and Liu, Jueting and Wang, Zehua},
  journal={Scientific Data},
  year={2024}
}
