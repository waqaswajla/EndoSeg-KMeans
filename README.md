# 🩺 EndoSeg-KMeans

**EndoSeg-KMeans** is a Python-based project that performs **unsupervised segmentation of endoscopy images** using the KMeans clustering algorithm. It aims to extract meaningful regions (e.g., tissues, lesions) from gastrointestinal (GI) tract imagery without using labeled data.

---

## 📌 Project Goals

- Segment endoscopy images using **KMeans Clustering**
- Evaluate clustered output using standard metrics like **Dice Score** and **IoU**
- Provide a simple, explainable baseline for medical image segmentation
- Build a foundation for future **deep learning-based segmentation**

---

## 🧠 Technologies Used

- **OpenCV** – for image processing  
- **NumPy** – for numerical operations  
- **Matplotlib** – for visualization  
- **Scikit-learn** – for KMeans clustering  
- **Python** – main language used

---

## 🩻 Why Endoscopy Image Segmentation?

Endoscopy is crucial for diagnosing GI disorders, but analyzing the images manually is slow and error-prone. This project aims to automate tissue segmentation in endoscopic images to assist in medical diagnosis or preprocessing for AI systems.

---

## 🗂️ Project Structure

```text
EndoSeg-KMeans/
│
├── images/                # Folder with input endoscopy images
├── masks/                 # (Optional) Ground truth masks for evaluation
├── EndoSeg_KMeans.ipynb   # Main Jupyter Notebook
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation

## Evaluation Metrics

This project includes evaluation using:
Dice Score – overlap between prediction and ground truth
IoU (Jaccard Index) – intersection over union of masks


