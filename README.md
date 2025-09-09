[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/mqRawNyD)
# 🗑️ Waste Image Classification with Transfer Learning (DSCI 552 Final Project)

Perfect-score (100/100) project for **Machine Learning (DSCI 552)** @ USC.  
Built a **9-class waste classifier** using transfer learning with multiple CNN architectures.

---

## 🚀 Highlights
- **Models compared**: ResNet50, ResNet101, EfficientNetB0, VGG16  
- **Data Augmentation**: crop, flip, rotate, zoom, contrast (OpenCV + Keras)  
- **Regularization**: BatchNorm, Dropout (20%), L2 penalty  
- **Training Strategy**: Frozen base layers, fine-tuned dense head, early stopping  
- **Evaluation Metrics**: Precision, Recall, F1, ROC AUC  

---

## 📊 Results
- **ResNet50 & EfficientNetB0** performed best overall.  
- **ResNet101** strong but computationally heavy.  
- **VGG16** underperformed, showing limits of older architectures.  
- Augmentation + transfer learning reduced overfitting and boosted generalization.  

---

## 📂 Files
- `Final_Project.ipynb` → Full notebook (preprocessing, training, evaluation)  
- `Final Project.pdf` → Assignment description  

---

## 👩‍💻 Author
**Chenyi Weng** | M.S. Spatial Data Science @ USC (Class of 2025)  
🌐 [Portfolio](https://mona100421.github.io/chenyi) • 💼 [LinkedIn](https://linkedin.com/in/wengchen) • 📧 wengchen@usc.edu
