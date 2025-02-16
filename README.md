# 🎨 Artist Identification using Deep Learning  

This project explores the use of **Convolutional Neural Networks (CNNs)** and **Transfer Learning (ResNet18 & ResNet50)** to classify paintings by their respective artists. Using deep learning, we aim to automate artist attribution based on painting style and composition.

## 🚀 Project Overview  
- **Problem:** Traditional art authentication methods rely on human expertise, which can be subjective and time-consuming.  
- **Solution:** Train deep learning models to recognize artistic styles using CNNs and transfer learning.  
- **Dataset:** A curated subset from **WikiArt's "Painters by Numbers" dataset**, consisting of **36 artists** with **81 paintings per artist**.  
- **Models Used:**
  - **Baseline CNN (9% accuracy)**
  - **ResNet18 (Fine-tuned) - Best Accuracy: 48%**
  - **ResNet50 (Fine-tuned) - Accuracy: 39%**  

## 🖼️ Sample Results
| Model | Accuracy |
|--------|----------|
| Baseline CNN | 9% |
| ResNet18 (Fine-tuned) | 48% |
| ResNet50 | 39% |

### 🔑 Key Findings:
- **Transfer learning significantly improved performance.**
- **ResNet18 performed best with fine-tuning**, achieving 48% accuracy.
- **ResNet50 did not outperform ResNet18**, possibly due to dataset limitations.
- **Hyperparameter tuning (epochs, learning rate) played a crucial role.**
- **The dataset size was a limiting factor**, and performance could improve with more data.

---

## 📺 Repository Structure  
```
/artist-identification
│— artist_identification.ipynb   # Jupyter Notebook with model training
│— artist-identification-report.pdf   # Research paper detailing the project
│— requirements.txt   # Dependencies for running the notebook
```

---

## 🛠️ Installation & Setup  

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/higupta27/artist-identification.git
cd artist-identification
```

### **2️⃣ Install Dependencies**
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**
```bash
jupyter notebook
```

---

## 📚 Research Paper  
📄 **[Download the Artist Identification Report](artist-identification-report.pdf)**  
This paper provides an in-depth explanation of the dataset, methodology, model architectures, experimental results, and key findings.

---

## 🔮 Future Improvements  
- **Expand dataset size** to improve generalization.  
- **Experiment with Vision Transformers (ViTs)** for comparison.  
- **Improve misclassification handling** by incorporating brushstroke analysis.  
- **Use style transfer techniques** to enhance learning of artist-specific features.  

---

## 👨‍💻 Authors  
- **Himanshi Gupta**  
- **Aditi Krishnakumar**  

---
