## 🎯 Medical Imaging Projects  

Exploring **AI in Healthcare**, focusing on deep learning models for **medical image segmentation** and analysis.  
This repository showcases research and implementations of state-of-the-art models applied to medical imaging tasks.  
![Brain Tumour MRI Segmentation](https://raw.githubusercontent.com/Hedi-Bk/Medical_Imaging_SwinTransformer/main/brain.jpg)  


---
## Project Overview  


| **Topic** | Kaggle Notebook | Blog (Notion) | Live Demo | Video |
|--------------|-------------------|------------------|--------------|----------|
| **Brain Tumour Segmentation** <br/> *SwinUNETR + MONAI* | [![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/code/bkhedi/brats-segmentation-with-swinunetr) | [![Notion](https://img.shields.io/badge/Notion-Blog-000000?logo=notion&logoColor=white)](https://www.notion.so/Brain-Tumour-Segmentation-Swin-UNETR-1b9974e2543b8094a8bec1630cab860c?pvs=21) | [![Hugging Face](https://img.shields.io/badge/Live-Demo-orange?logo=huggingface&logoColor=white)](https://huggingface.co/spaces/Hedi-Bk/BRATS) | [![Video](https://img.shields.io/badge/Watch-Video-red?logo=youtube&logoColor=white)](https://drive.google.com/file/d/1C6-kxlSkMmb_IBg59EwQr5BywANjTz6H/view?usp=sharing) |

---

## What this project does

This project implements an end-to-end pipeline for **brain tumor segmentation** using MRI scans:

- **Model**: SwinUNETR (transformer-based architecture)  
- **Dataset**: BraTS 2021 (with 4 MRI modalities: FLAIR, T1, T1CE, T2)  
- **Outputs**: Segmentation masks for  
  - Whole Tumor (WT)  
  - Tumor Core (TC)  
  - Enhancing Tumor (ET)  
- **Evaluation**: Dice score & validation pipeline  
- **Interface**: Gradio app to upload scans and visualize predictions  

---

##  Contributors  

- [**Hedi Ben Khalifa**](https://github.com/Hedi-Bk)  
- [**Aziz Esseghaier**](https://github.com/aziz-esseghaier) 

---

## References  

- [MONAI Documentation](https://monai.io/)  
- [BraTS 2021 Dataset](https://www.med.upenn.edu/cbica/brats2021/)  

---
