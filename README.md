# FingerSense

FingerSense is a machine learning project focused on **detecting hands in images and predicting how many fingers are being held up**.

The core of this repository is a **Jupyter Notebook–based workflow** that explores image preprocessing, hand detection, and model inference using **PyTorch**.

---

## 📌 Project Goals

- Load and preprocess hand images
- Detect hands in images
- Train a model to predict the number of raised fingers
- Perform inference by passing images to the trained model
- Keep the project structured, reproducible, and extensible

---

## 🧠 Approach

The project follows a standard machine learning workflow:

1. **Exploration**  
   Inspect and understand the hand image dataset.

2. **Preprocessing**  
   Resize, normalize, and transform images for model input.

3. **Model Training**  
   Train a PyTorch-based model for finger count prediction.

4. **Inference**  
   Pass new images to the model and output the predicted finger count.

---

## 📁 Repository Structure

```text
.
├── notebooks/        # Jupyter notebooks (exploration, training, inference)
├── src/              # Reusable Python code (datasets, models, utils)
├── data/             # Dataset (ignored, see data/README.md)
├── models/           # Trained model files (ignored)
├── outputs/          # Logs and visualizations
├── requirements.txt
└── README.md
``
