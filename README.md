[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/mqRawNyD)

# ♻️ Transfer Learning for Waste Image Classification

**Highlight:** Built an end-to-end deep learning pipeline to classify 9 categories of real-world waste images. Compared multiple pre-trained CNNs (ResNet50/101, EfficientNetB0, VGG16) using transfer learning and regularization. Achieved **56% accuracy** on the RealWaste dataset with VGG16 as the best-performing model.

---

## 🚀 Project Overview
This project demonstrates my ability to design and implement a **production-style ML workflow**:
- **Data Preparation:** 4,752 waste images across 9 categories, resized to 224×224 with OpenCV, normalized and one-hot encoded.
- **Augmentation:** Combined OpenCV preprocessing (random crop, contrast adjustment) with Keras’ `ImageDataGenerator` (rotation, zoom, flips).
- **Transfer Learning:** Fine-tuned four ImageNet pre-trained CNNs (ResNet50, ResNet101, EfficientNetB0, VGG16).
- **Training Strategy:** 100 epochs with early stopping, 20% validation split, dropout & L2 regularization.
- **Evaluation:** Reported training/validation loss curves, accuracy metrics, and test set performance.

---

## 📊 Key Results
| Model          | Test Accuracy |
|----------------|---------------|
| ResNet50       | ~39%          |
| ResNet101      | ~38%          |
| EfficientNetB0 | ~21%          |
| **VGG16**      | **56%** ✅    |

- VGG16 outperformed other architectures, showing the importance of architecture selection for small-to-medium datasets.
- Demonstrated ability to implement **multi-model benchmarking**.

---

## 🛠️ Tech Stack
- **Languages:** Python (NumPy, Pandas)
- **Libraries:** TensorFlow/Keras, OpenCV, scikit-learn, Matplotlib
- **Tools:** Jupyter Notebook, tqdm, pickle
- **Concepts:** Transfer Learning, CNNs, Regularization, Data Augmentation
