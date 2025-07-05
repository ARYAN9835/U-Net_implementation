# U-Net for Brain Tumor Segmentation

This repository contains a **pure U-Net implementation from scratch** for performing brain tumor segmentation on MRI images.

U-Net is a widely used architecture for semantic segmentation tasks in biomedical imaging. It consists of a **contracting path (encoder)** to capture context and a **symmetric expanding path (decoder)** that enables precise localization.

---

## Model Architecture

U-Net is composed of:

- **Encoder**: 4 downsampling blocks using Conv2D + MaxPooling
- **Bottleneck**: Deepest layer with most filters
- **Decoder**: 4 upsampling blocks with Conv2DTranspose and skip connections
- **Final Layer**: 1x1 Conv to map features to binary mask

🧬 **Skip connections** between encoder and decoder help retain spatial information, essential for segmentation.

---
##  Dataset Used

- **Dataset**: [Brain Tumor Segmentation (Kaggle)](https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation) 
- Contains MRI images along with corresponding tumor masks.
