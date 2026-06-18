[README.md.txt](https://github.com/user-attachments/files/29089999/README.md.txt)
# Task-05: Neural Style Transfer 🎨

## 📌 Project Overview
This project demonstrates **Neural Style Transfer (NST)** using deep learning. The goal is to combine the **content of one image** with the **artistic style of another image**, producing a new stylized image.

---

## 🧠 Concept
Neural Style Transfer is a deep learning technique that uses Convolutional Neural Networks (CNNs) to:

- Extract content features from one image
- Extract style features from another image
- Combine both to generate a new artistic image

It is widely used in AI art generation and creative applications.

---

## 📂 Project Files

- `style_transfer.ipynb` → Main Colab notebook implementing NST
- `content.jpg` → Original content image
- `style.jpg` → Artistic style image (e.g., painting)
- `stylized_output.jpg` → Final generated image
- `requirements.txt` → Required Python libraries
- `README.md` → Project documentation

---

## ⚙️ How It Works

1. Load content and style images
2. Use a pre-trained VGG19 model
3. Extract features from both images
4. Compute content and style loss
5. Optimize target image using gradient descent
6. Generate final stylized image

---

## 📦 Requirements

```txt
torch
torchvision
pillow
matplotlib
