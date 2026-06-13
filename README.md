# Transformer-Based-Lip-Reading-for-Silent-Speech-Conversion


# 👄 Transformer-Based Lip Reading for Silent Speech Conversion

A state-of-the-art **Lip Reading System** that converts visual lip movements into text using deep learning and computer vision techniques. The system supports both **real-time webcam-based lip reading** and **video upload analysis**, enabling silent speech recognition through visual cues.

---

## 🚀 Features

### 🎥 Real-Time Lip Reading

* Live webcam-based lip movement recognition.
* Guided mouth capture box for accurate detection.
* Instant text generation from visual speech patterns.

### 📂 Video Upload Analysis

* Upload pre-recorded videos for lip-reading analysis.
* Supports multiple formats:

  * MP4
  * WebM
  * AVI

### 🤖 AI-Powered Recognition

* Deep learning-based architecture inspired by LipNet.
* Captures temporal and spatial lip movement features.
* Decodes silent speech into readable text.

### 🎨 Modern User Interface

* Attractive Glassmorphism-inspired design.
* Responsive and user-friendly dashboard.
* Easy navigation for both live and uploaded video analysis.

### 🔊 Audio-Assisted Refinement

* When audio is available, the system performs multimodal analysis.
* Uses speech transcription to improve prediction accuracy.

---

## 🛠️ Technology Stack

### Backend

* Python
* Flask

### Artificial Intelligence & Machine Learning

* TensorFlow
* Keras
* NumPy

### Computer Vision

* OpenCV
* Face Detection
* Mouth Region Extraction

### Audio Processing

* SpeechRecognition
* MoviePy

### Frontend

* HTML5
* CSS3
* JavaScript

---

## 📋 Prerequisites

Before running the project, ensure the following are installed:

* Python 3.8 or higher
* Webcam (for live lip reading)
* pip package manager

---

## 📁 Project Structure

```bash
Transformer-Based-Lip-Reading-for-Silent-Speech-Conversion/
│
├── app.py
├── model_creation.py
├── requirements.txt
│
├── static/
│   ├── css/
│   ├── js/
│   └── uploads/
│
├── templates/
│   ├── login.html
│   ├── dashboard.html
│   └── result.html
│
├── models/
│   └── lip_reading_model.h5
│
└── README.md
```

---

## ⚙️ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Pranali-Reddy/Transformer-Based-Lip-Reading-for-Silent-Speech-Conversion.git

cd Transformer-Based-Lip-Reading-for-Silent-Speech-Conversion
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Create the Model Architecture

Generate the required model structure and placeholder weights:

```bash
python model_creation.py
```

---

## 🚦 Running the Application

Start the Flask server:

```bash
python app.py
```

The application will be available at:

```bash
http://127.0.0.1:8001
```

---

## 🔐 Login Credentials

Use the following credentials to access the dashboard:

```text
Email    : admin@gmail.com
Password : 1234
```

---

## 🎯 How to Use

### Option 1: Real-Time Camera Analysis

1. Login to the system.
2. Click **Use Real-Time Camera**.
3. Position your face inside the capture frame.
4. Ensure your lips are clearly visible.
5. The system will process lip movements and generate text predictions.

---

### Option 2: Video Upload Analysis

1. Login to the system.
2. Click **Analyze Video**.
3. Upload a supported video file.
4. Wait for processing to complete.
5. View the predicted speech output.

---

## 🧠 Model Architecture

The lip reading model is designed to capture both spatial and temporal information from video sequences.

### Architecture Components

#### 1. Conv3D Layers

* Extract spatial and temporal features simultaneously.
* Learn lip movement patterns across video frames.

#### 2. Bidirectional GRU Layers

* Capture sequential dependencies.
* Analyze lip movement information in both forward and backward directions.

#### 3. CTC Decoder

* Uses Connectionist Temporal Classification (CTC).
* Converts frame-wise predictions into meaningful character sequences.
* Eliminates the need for perfectly aligned training labels.

### Workflow

```text
Input Video Frames
        ↓
Face Detection
        ↓
Mouth Region Extraction
        ↓
3D Convolution Layers
        ↓
Bidirectional GRU Layers
        ↓
CTC Decoding
        ↓
Predicted Text Output
```

---

## 🎯 Applications

* Silent Speech Recognition
* Assistive Communication Systems
* Accessibility Technologies
* Human-Computer Interaction
* Surveillance & Security Systems
* AI Communication Research
* Speech-Impaired Assistance Tools

---

## 📊 Future Enhancements

* Transformer-based attention mechanism
* Multi-language lip reading support
* Mobile application integration
* Real-time deployment optimization
* Improved dataset training
* Cloud-based inference services
* Speaker-independent recognition

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added new feature"
```

4. Push to your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Developed For

**AI Communication Systems & Silent Speech Research**

A deep learning-powered solution for converting visual speech into text, enabling seamless communication through advanced lip-reading technology.
