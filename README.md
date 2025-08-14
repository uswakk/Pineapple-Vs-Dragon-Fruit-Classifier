# 🍍 Pineapple vs. Dragon Fruit Classifier  
*A fun deep learning project with fastai & PyTorch*

![Fastai](https://img.shields.io/badge/Library-fastai-blue?style=for-the-badge&logo=python)  
![PyTorch](https://img.shields.io/badge/Framework-PyTorch-red?style=for-the-badge&logo=pytorch)  
![Colab](https://img.shields.io/badge/Run-Google%20Colab-orange?style=for-the-badge&logo=googlecolab)  

---

## 📌 Overview  
This project is a simple image classifier that predicts whether a given image is of a **pineapple** 🍍 or a **dragon fruit** 🐉🍈.  
It’s based on [fastai](https://fastai.github.io/) and uses **transfer learning** with a pre-trained ResNet18 model for quick and effective training.

Even though the use case is playful, the project demonstrates:
- How to **collect image data** programmatically  
- **Preprocess & clean** the dataset  
- **Fine-tune** a CNN on custom images  
- Make **predictions** on new images  

---

## 🖼 Example Predictions
| Image | Prediction | Confidence |
|-------|------------|------------|
| ![Pineapple](pineapple.jpg) | Pineapple | 98% |
| ![Dragonfruit](dragonfruit.jpg) | Dragon Fruit | 96% |

---

## ⚙️ How It Works
1. **Image Collection** – Uses DuckDuckGo image search (`ddgs`) to fetch pineapple and dragon fruit photos.  
2. **Data Preprocessing** – Resizes, cleans, and organizes images into class folders.  
3. **Model Training** – Trains a ResNet18 CNN with fastai’s high-level API.  
4. **Prediction** – Classifies new images and outputs probability scores.

---

## 🚀 Installation & Usage
You can run the notebook locally or on **Google Colab**.

### 1️⃣ Clone the repo
```bash
git clone https://github.com/uswakk/pineapple-vs-dragonfruit.git
cd pineapple-vs-dragonfruit
