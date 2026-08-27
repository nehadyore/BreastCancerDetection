# BreastCancerDetection
 An approach of breast cancer detection system for multi classification of breast cancer abnormalities. This repository contains the implementation accompanying our paper:
> Rani, N., Gupta, D.K. & Singh, S. **"Multi-class classification of breast cancer abnormality using transfer learning."** *Multimedia Tools and Applications*, 83, 75085–75100 (2024). [https://doi.org/10.1007/s11042-023-17832-2](https://doi.org/10.1007/s11042-023-17832-2)
## Overview
Breast cancer is one of the leading causes of cancer-related deaths worldwide, and early, accurate diagnosis is critical to improving survival rates. This project uses **transfer learning with pre-trained CNN architectures** to classify mammogram images into four abnormality types: Asymmetry, Calcification, Carcinoma, Mass. Three pre-trained models - **VGG16**, **VGG19**, and **ResNet50** were fine-tuned on the classification task and benchmarked against each other. **VGG16** achieved the best performance overall, with accuracy ranging from **92% to 95%** on the DDSM and UPMC mammography datasets.
## Dataset
- Images sourced from the **DDSM (Digital Database for Screening Mammography)** and **UPMC** breast imaging datasets. Approximate 2,276 images total, split into an 80%/20% train-test ratio (stratified across the 4 classes).
## Requirements
```
tensorflow / keras
scikit-learn
numpy
matplotlib
opencv-python
imutils
```
## Citation
If you use this work, please cite:
```bibtex
@article{rani2024multiclass,
  title={Multi-class classification of breast cancer abnormality using transfer learning},
  author={Rani, Neha and Gupta, Deepak Kumar and Singh, Samayveer},
  journal={Multimedia Tools and Applications},
  volume={83},
  pages={75085--75100},
  year={2024},
  publisher={Springer},
  doi={10.1007/s11042-023-17832-2}
}
```
