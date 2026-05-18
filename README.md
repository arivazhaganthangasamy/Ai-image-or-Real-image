# 🧠 AI vs REAL Image Classification System

A Flask-based Deep Learning web application that detects whether an uploaded image is **AI Generated** or **Real** using a custom CNN model built with PyTorch.

---

# 🚀 Features

- Upload images through web interface
- AI vs REAL image classification
- Built using PyTorch CNN
- Flask web application
- Image preview after upload
- Fast prediction system

---

# 🛠 Technologies Used

- Python
- Flask
- PyTorch
- Torchvision
- PIL (Pillow)
- HTML/CSS

---

# 📂 Project Structure

```bash
project/
│
├── app.py
├── classifier.pth
├── requirements.txt
├── uploads/
│
├── templates/
│   └── index.html
│
├── static/
│
└── README.md
```

---

# ⚙ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/ai-real-classifier.git
cd ai-real-classifier
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

# ▶ Run Application

```bash
python app.py
```

Then open:

```bash
http://127.0.0.1:5000
```

---

# 🧠 Model Architecture

The CNN model contains:

- 2 Convolution Layers
- Max Pooling
- Fully Connected Layers
- ReLU Activation

Input image size:

```bash
150 x 150
```

Classes:

```python
["AI", "REAL"]
```

---

# 📸 How It Works

1. Upload an image
2. Image is resized and normalized
3. CNN model predicts image type
4. Result displayed on webpage

---

# 📦 Requirements

```txt
flask
torch
torchvision
pillow
numpy
```

---

# 🔮 Future Improvements

- Add confidence score
- Add drag & drop upload
- Deploy on Render/Heroku
- Use pretrained models
- Add webcam support

---

# 👨‍💻 Author

Developed by arivazhagan

---

# 📜 License

This project is open-source and available under the MIT License.
