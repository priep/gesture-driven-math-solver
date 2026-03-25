# Real-Time Gesture-Driven Mathematical Expression Solver

A touchless AI-powered system that lets users draw mathematical equations 
in the air using hand gestures, recognized and solved step-by-step using 
CNN and Ovis2-4B multimodal AI.

> Final Year B.Tech Project | Rajasthan Technical University, Kota

---

## 🔧 How It Works

| Step | What Happens |
|------|-------------|
| 1 | Webcam captures live hand movements |
| 2 | MediaPipe tracks 21 hand landmarks in real-time |
| 3 | OpenCV renders drawn strokes on virtual canvas |
| 4 | CNN (CROHME dataset) recognizes math symbols — 91.3% accuracy |
| 5 | Ovis2-4B multimodal AI solves equation step-by-step — 90% success rate |

---

## ✍️ Gesture Controls

| Gesture | Action |
|---------|--------|
| Thumb + Index finger up | Draw |
| Thumb + Index + Middle up | Move cursor |
| Thumb + Middle finger up | Erase |
| Thumb + Pinky up | Reset canvas |
| Index + Middle up | Send to AI |

---

## 📊 Results

| Module | Metric | Result |
|--------|--------|--------|
| Gesture Recognition | Accuracy | 92% |
| Symbol Recognition (CNN) | Accuracy | 91.3% |
| Equation Solving | Success Rate | 90% |
| System Latency | Response Time | <80ms |
| User Experience | Pilot Score | 8.6/10 |

---

## 🛠️ Tech Stack
- **Computer Vision:** Python, OpenCV, MediaPipe
- **Deep Learning:** TensorFlow, PyTorch, CNN (CROHME dataset)
- **AI Model:** Ovis2-4B Multimodal Model
- **Frontend:** Streamlit

---

## ▶️ Run Locally
```bash
# 1. Clone the repo
git clone https://github.com/priep/gesture-driven-math-solver.git
cd gesture-driven-math-solver

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add your API key
cp .env.example .env
# Open .env and add your Gemini API key

# 4. Run
streamlit run app.py
```

---

## 💡 Applications
- 🏫 Smart classrooms and EdTech platforms
- ♿ Accessibility tools for motor-impaired users
- 🥽 AR/VR environments
- 🖥️ Virtual interactive whiteboards

---

## 👩‍💻 Authors
Priya Patidar
