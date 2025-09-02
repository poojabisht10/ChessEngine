<h1 align="center">♟️ Flask Chess Engine & Interface</h1>
<p align="center">A simple chess engine with Flask backend and chess.js frontend</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9-blue" />
  <img src="https://img.shields.io/badge/Flask-2.0-lightgrey" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## ✨ Features
- Interactive chessboard powered by **chessboard.js** + **chess.js**
- Backend move validation and calculations using **python-chess**
- Flask server to connect frontend and backend seamlessly
- Supports UCI engines and Gaviota tablebases (via extensions)

---

## 🛠️ Tech Stack
- **Frontend:** HTML, JavaScript, chessboard.js, chess.js  
- **Backend:** Python, Flask, python-chess  
- **Optional:** UCI protocol, Gaviota tablebases  

---

## ⚙️ Installation & Setup

```bash
# Clone the repo
git clone https://github.com/your-username/flask-chess-engine.git
cd flask-chess-engine

# Install dependencies
pip install flask
pip install python-chess[uci,gaviota]

# Run the server
python app.py
