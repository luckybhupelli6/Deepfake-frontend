# 🧠 Deepfake Detection App

This project is a full-stack application that detects deepfakes in images using a deep learning model (EfficientNet). The **frontend** is built with **React**, and the **backend** is powered by **FastAPI** with a trained model.



---

## 👥 Contributors

| GitHub | Profile |
|--------|---------|
| **Sumit Kumawat** | https://github.com/sumiitttt11 |
| **Lucky Bhupelli** | https://github.com/luckybhupelli6 |


---

## 📂 Project Structure

```text
deepfake/
├── backend/           # FastAPI backend
│   ├── app/
│   │   ├── model/     # Model loading & prediction logic
│   │   ├── utils/     # Image preprocessing utilities
│   │   └── ...
│   ├── main.py        # FastAPI entry point
│   └── requirements.txt
│
└── frontend/          # React frontend
    ├── src/
    └── package.json
```

## 🔧 How to Run

**1. Clone the repository**
```
git clone https://github.com/sumiitttt11/Image_Deepfake-detection
```
**2. Navigate to project directory**
```
cd deepfake
```
**⚛️Frontend Setup**
```bash
cd frontend
npm install       # Install dependencies
npm run dev       # Start the React app

```
**🐍 For Backend Setup(Check the below link):**
```
https://github.com/sumiitttt11/deepfake-backend
```
#### The backend will run at http://localhost:8000 and frontend at http://localhost:3000.

## 🧪 How It Works
- Upload an image or video using the web interface.
- The file is sent to the FastAPI backend.
- The model processes and detects if it’s real or a deepfake.
- Results are displayed.

---
