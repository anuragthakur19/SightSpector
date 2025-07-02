# 🕵️‍♂️ SightSpector – Real vs AI Image Classifier

**SightSpector** is an AI-powered web application built using Flask and CNN that detects whether an uploaded image is **real** or **AI-generated** (deepfake).

---

## 🚀 Features

- Upload an image through a clean web interface
- Get instant prediction: `Real` or `Fake`
- Trained on the CIFAKE dataset
- Deep learning model using Keras (CNN)
- Model stored externally (Google Drive link)

---

## 🧠 Model

> 🔗 [Download model from Google Drive (32 MB)](https://drive.google.com/uc?id=1xV3H-9q8cexn0Eg69d_k93BgHaZhobz9)

After downloading, place the file as:

SightSpector/
├── app.py
├── index.html
├── style.css
├── cifake_classifier.h5 ← Place model here
