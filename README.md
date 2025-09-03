# Chest X-Ray Images (Pneumonia) Dataset  

This project provides An Algorithm for Pneumonia Detection Based on **Chest X-Ray Images Images**, a publicly available medical imaging dataset used for developing and evaluating machine learning models to detect pneumonia from chest X-rays.  

---

## 📌 Overview  

- **Name**: Chest X-Ray Images (Pneumonia)  
- **Released by**: U.S. National Institutes of Health (NIH), 2018  
- **Hosted on**: [Kaggle](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)  
- **Format**: JPEG images with variable resolutions (commonly 1024×1280 pixels)  
- **Labels**: Normal vs. Pneumonia (binary classification)  

---

## 📂 Dataset Content  

- **Total images**: 5,856  
- **Subsets**:  
  - **Training**: 5,216 images  
  - **Testing**: 624 images  
  - **Validation**: 16 images  

- **Labels file**: Indicates whether an image is **normal** or shows signs of **pneumonia**.  
- **Annotations**: Provided by experienced NIH radiologists.  

---

## 🧭 Applications  

This dataset is widely used for:  

- Training deep learning and classical ML models for **pneumonia detection**.  
- Benchmarking medical image classification algorithms.  
- Research on **computer-aided diagnosis (CAD)** in radiology.  
- Exploring challenges in **medical imaging** (imbalanced data, resolution variability, interpretability).  

---

## 📊 Dataset Details  

- Images are chest X-rays of pediatric patients.  
- Labeled as **NORMAL** or **PNEUMONIA**.  
- Useful for binary classification tasks.  
- Contains high inter-class variability, making it a robust testbed for algorithm development.  

---

## 📚 Citation  

If you use this dataset in your research, please cite:  

> Rajpurkar, P., Irvin, J., Ball, R. L., et al.  
> "Deep learning for chest radiograph diagnosis: A retrospective comparison of the CheXNeXt algorithm to practicing radiologists,"  
> *PLoS Medicine*, vol. 15, no. 11, 2018.  
> DOI: [10.1371/journal.pmed.1002686](https://doi.org/10.1371/journal.pmed.1002686)  

---

## 📂 Repository Structure  

- `data/` – Folder containing chest X-ray images (organized by Normal / Pneumonia)  
- `labels.csv` – File with image labels  
- `EDA_Xray.ipynb` – Exploratory data analysis notebook  
- `Model_Training.ipynb` – Deep learning model development and evaluation  

---

## ⚙️ How to Use  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/chest-xray-pneumonia.git
   cd chest-xray-pneumonia
