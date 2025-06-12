# 🧠 Brain Tumor Detection & Segmentation with YOLOv8 + SAM

Welcome to the ultimate medical imaging project! This notebook leverages the power of **YOLOv8** (for object detection) and **Segment Anything Model (SAM)** (for segmentation) to identify and segment brain tumors from MRI images. 🚀

---

## 📓 Project Overview

- **Notebook:** `CB_01.ipynb`
- **Goal:** Detect and segment brain tumors in MRI scans using state-of-the-art deep learning models.
- **Tech Stack:**
  - YOLOv8 (Ultralytics)
  - Segment Anything Model (SAM)
  - PyTorch, OpenCV, Matplotlib, PIL
  - Kaggle Datasets
---

## ✨ Features

- 🔍 **Automatic Tumor Detection:** Fast and accurate localization of tumors in MRI images.
- 🎨 **Precise Segmentation:** SAM refines YOLO's detections for pixel-perfect tumor masks.
- 📦 **Kaggle Integration:** Seamless dataset download and setup.
- 🛠️ **Fully Notebook-Based:** All steps, from setup to results, are in `CB_01.ipynb`.
- 💾 **Easy to Run:** Just follow the cells in order—no code outside the notebook required!

---

## 🚦 Quickstart

1. **Clone this repo & open the notebook:**
   ```bash
   git clone https://github.com/ahmed2231web/Brain-tumor-detection.git
   cd Yolo
   jupyter notebook CB_01.ipynb
   ```

2. **Install dependencies:**
   - The notebook will prompt you to install all required packages (Ultralytics, OpenCV, Matplotlib, SAM, Pillow, Kaggle).
   - Or, pre-install with:
     ```bash
     pip install ultralytics opencv-python matplotlib segment-anything pillow kaggle
     ```

3. **Kaggle API setup:**
   - Download your `kaggle.json` from your Kaggle account.
   - Upload it when prompted in the notebook.

4. **Run all cells:**
   - The notebook will guide you through dataset download, model training, and inference.

---

## 🗂️ Project Structure

```
Yolo/
├── CB_01.ipynb        # Main Jupyter notebook (run this!)
├── .venv/             # (Optional) Python virtual environment
└── ...                # Other files/folders
```

---

## 🧩 How It Works

1. **Setup & Dependencies**  
   📦 Installs all required libraries and downloads the SAM checkpoint.

2. **Dataset Download**  
   📥 Fetches the brain tumor MRI dataset from Kaggle.

3. **YOLOv8 Training**  
   🏋️‍♂️ Fine-tunes YOLOv8 on the brain tumor dataset for detection.

4. **SAM Segmentation**  
   ✂️ Uses SAM to segment tumors within YOLO-detected regions.

5. **Visualization**  
   🖼️ Displays original, detected, and segmented images side by side.

---

## ⚡ Requirements

- Python 3.8+
- Jupyter Notebook
- Kaggle account (for dataset access)

---

## 🙌 Credits

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- [Meta Segment Anything (SAM)](https://github.com/facebookresearch/segment-anything)
- [Kaggle Brain Tumor Dataset](https://www.kaggle.com/datasets/pkdarabi/medical-image-dataset-brain-tumor-detection)

---

## 💡 Tips

- For best results, use a GPU runtime (e.g., Google Colab or local CUDA machine).
- Training time and accuracy depend on your hardware and chosen YOLO model size.
- The notebook is modular—feel free to experiment with different models or datasets!

---

## 📬 Contact

Questions or suggestions? Open an issue or reach out! 🚀

---

> Made with ❤️ for medical AI research. 
