# 🧠 Liver Tumor Segmentation with Deep Learning Architectures

<img width="1024" height="768" alt="liver" src="https://github.com/user-attachments/assets/8e3bc91a-1c3b-4580-a859-588725c7274c" />


This repository contains my project on **automatic liver tumor segmentation** from CT scans using deep learning.  
The study compares **U-Net** and **ResNet50** architectures for accurate segmentation of liver tumors, leveraging  
loss functions like **Tversky Loss** and evaluation metrics such as **Dice Coefficient, Jaccard Index, and Accuracy**.

---

## 📂 Repository Structure
- `Liver_Tumor_Segmentation_with_Deep_Learning_Architectures.pdf` → Full project report (detailed write-up).  
- `liver-tumor-segmentation-with-dl-architectures.html` → HTML version of the report for easy viewing.  
- `liver_tumor_segmentation.ipynb` → Jupyter Notebook with model implementation, training, and evaluation.

---

## 🧪 Methodology
- **U-Net**: Encoder-decoder architecture with skip connections for precise boundary segmentation.  
- **ResNet50**: Pre-trained backbone adapted for segmentation tasks, fine-tuned for CT scans.  
- **Dataset**: Liver Tumor Segmentation (LiTS) challenge dataset.  
- **Loss Function**: Tversky Loss to handle class imbalance.  
- **Evaluation Metrics**: Dice, Jaccard, and Accuracy.  

---

## 📊 Results
| Model   | Dice Coefficient | Jaccard Index | Validation Accuracy |
|---------|-----------------|---------------|----------------------|
| **U-Net**   | 0.93            | 0.92          | 97.18%               |
| **ResNet50** | 0.94            | 0.94          | 97.15%               |

- U-Net: More efficient and lightweight, but misses very small tumors.  
- ResNet50: Stronger feature extraction, better precision for irregular tumors.

  
