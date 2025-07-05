 Brain Tumor Segmentation using U-Net, ResNet34 & ResNet50

This project focuses on medical image segmentation for brain tumors using deep learning. We compare the performance of three architectures:
- A standalone **U-Net**,
- **U-Net with ResNet34** as the encoder backbone,
- **U-Net with ResNet50** as the encoder backbone.

🧪 The goal is to identify and segment tumor regions from MRI images.

---

## Related Project

# You can find my standalone U-Net implementation here:  
🔗 [U-Net Implementation Repo](https://github.com/ARYAN9835/U-Net_implementation)

---

## Models Compared

| Model                | Encoder      | Description                                      |
|---------------------|--------------|--------------------------------------------------|
| U-Net (Baseline)     | Custom CNN   | Classical architecture with symmetrical encoder-decoder |
| U-Net + ResNet34     | ResNet34     | Pretrained ResNet34 used as encoder backbone     |
| U-Net + ResNet50     | ResNet50     | Deeper encoder for richer feature extraction     |

---

## Dataset Used

- **Dataset**: [Brain Tumor Segmentation (Kaggle)](https://www.kaggle.com/datasets/nikhilroxtomar/brain-tumor-segmentation)  
- Contains MRI images along with corresponding tumor masks  


