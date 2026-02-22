# 🚀 FaceNova

**FaceNova** is an AI-powered face swap application that allows users to seamlessly swap faces in images (and optionally videos) with high-quality enhancement and upscaling.

Built using modern deep learning models and GPU acceleration for fast and realistic results.

---

## ✨ Features

* 🔄 Face Swapping (Image Mode)
* 🎥 Optional Video Mode Support
* 🧠 AI-based Face Detection & Alignment
* 🔍 GFPGAN Face Enhancement
* 📈 Real-ESRGAN 720p Upscaling
* ⚡ GPU Acceleration (ONNX / CUDA supported)
* 💻 Clean and Simple User Interface

---

## 🛠️ Tech Stack

**Frontend**

* React / HTML / CSS (or your UI framework)

**Backend**

* Python
* OpenCV
* ONNX Runtime (GPU acceleration)

**Models Used**

* GFPGAN – Face restoration & enhancement
* Real-ESRGAN – Image upscaling (720p)

---

## 📂 Project Structure

```
FaceNova/
│
├── frontend/              # UI code
├── backend/
│   ├── models/            # AI models
│   ├── face_swap.py       # Core face swap logic
│   ├── enhancement.py     # GFPGAN integration
│   └── upscale.py         # Real-ESRGAN integration
│
├── notebooks/             # Testing (.ipynb files)
├── assets/                # Sample images
├── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/facenova.git
cd facenova
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

### Image Mode

```bash
python backend/face_swap.py --source source.jpg --target target.jpg
```

Output will be saved in the `output/` folder.

---

## 🖥️ GPU Support

For best performance:

* NVIDIA GPU recommended
* CUDA enabled
* ONNX Runtime GPU version installed

FaceNova runs 5–10x faster with GPU acceleration.

---

## 📸 Example Workflow

1. Upload Source Face
2. Upload Target Image
3. Enable Enhancement (optional)
4. Click Generate
5. Download Result

---

## 📌 Roadmap

* [ ] Real-time webcam swapping
* [ ] Batch image processing
* [ ] Web-based deployment
* [ ] Cloud API integration

---

## ⚠️ Disclaimer

This project is intended for educational and research purposes only.
Users are responsible for ensuring ethical and legal use of face-swapping technology.

---

## 🤝 Contributing

Pull requests are welcome.
For major changes, please open an issue first to discuss what you would like to improve.

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 📢 Share it

---
