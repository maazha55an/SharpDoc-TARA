# SharpDoc-TARA

SharpDoc-TARA is a deep learning–based **document image restoration and enhancement** project implemented in **PyTorch**.  
The project focuses on improving the visual quality of degraded document images (blur, noise, low contrast) to make them more readable and OCR-friendly.

This repository contains an experimental Jupyter Notebook comparing **SharpDoc-style restoration** with baseline document restoration approaches.

# Pre-print PDF
🔗 https://github.com/maazha55an/SharpDoc-TARA/blob/main/SharpDoc-TARA.pdf

---

## 🚀 Features

- Document image enhancement using deep learning
- PyTorch-based training and inference
- Comparison with baseline document restoration methods
- End-to-end workflow inside a Jupyter Notebook
- Suitable for research experiments and academic projects

---

## 🧠 Model & Approach

- Framework: **PyTorch**
- Tasks:
  - Document restoration
  - Image sharpening and enhancement
- Loss functions and architectures inspired by modern document restoration models
- Notebook-based experimentation (Colab / Jupyter)

---

## 📂 Repository Structure

```
SharpDoc-TARA/
│
├── SharpDoc-TARA.ipynb   # Main Jupyter Notebook (training & evaluation)
├── README.md            # Project documentation
```

---

## 🛠️ Requirements

Make sure you have the following installed:

- Python 3.8+
- PyTorch
- torchvision
- NumPy
- OpenCV
- Matplotlib
- Jupyter Notebook / Google Colab

Install dependencies (example):

```bash
pip install torch torchvision numpy opencv-python matplotlib
```

---

## ▶️ How to Run

### Option 1: Google Colab
1. Upload `SharpDoc-TARA.ipynb` to Google Colab
2. Enable GPU:
   - Runtime → Change runtime type → GPU
3. Run cells sequentially

### Option 2: Local Jupyter
```bash
jupyter notebook
```
Open `SharpDoc-TARA.ipynb` and execute the cells in order.

---

## 📊 Results

- Improved sharpness and clarity of degraded document images
- Better visual quality compared to baseline restoration
- Useful as a preprocessing step for OCR systems

*(Qualitative results can be observed directly in the notebook outputs.)*

---

## 🎓 Use Case

- Research experiments
- Document image restoration studies
- OCR preprocessing pipelines
- Academic projects and demos

---

## 📜 License

This project is intended for **educational and research purposes**.  
You are free to use and modify it with proper attribution.

---

## 👤 Author

**Maaz Hassan**  
GitHub: https://github.com/maazha55an
