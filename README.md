# 🇧🇩 Bangladeshi Taka Note Detection using YOLOv26

An explainable computer vision framework designed to identify and classify 18 different classes of Bangladeshi Taka (9 denominations, Front and Back sides).

## 📊 Project Overview
This project was developed as part of an AI research assignment to create a robust detection system for local currency. The model was trained using a custom dataset of over 16,000 images, achieving a high mean Average Precision (mAP).

* **Model Architecture:** YOLOv26
* **Total Classes:** 18 (2, 5, 10, 20, 50, 100, 200, 500, 1000 Taka - Front & Back)
* **Mean Average Precision (mAP):** 72.7%
* **Inference Hardware:** Optimized for CPU-based detection (~40ms)

## 🔗 External Resources
Due to file size limits on GitHub, the full dataset and large assets are hosted externally:
* **📁 Full Dataset (17k+ Images):** [PASTE YOUR GOOGLE DRIVE LINK HERE]

## 📁 Repository Structure
* `YOLOv26.ipynb`: The complete training, validation, and inference pipeline.
* `best.pt`: The final trained model weights for deployment.
* `data.yaml`: Configuration file defining class names and directory paths.
* `samples/`: (Recommended) Folder containing images with detected bounding boxes.


## 📈 Evaluation Results
The model shows strong performance in distinguishing between similar-colored notes (e.g., 10 and 100 Taka) by focusing on specific textural features and numerical annotations on the currency.

---
**Author:** sumaiyasarker  
