Flask Chess Engine & Interface
==============================

A simple chess engine with Flask backend and chess.js frontend.
It lets you play chess in your browser while move validation and calculations
are handled on the backend using python-chess.

------------------------------------
Features
------------------------------------
- Interactive chessboard powered by chessboard.js + chess.js
- Backend move validation and calculations using python-chess
- Flask server to connect frontend and backend seamlessly
- Supports UCI engines and Gaviota tablebases (via extensions)

------------------------------------
Tech Stack
------------------------------------
Frontend:  HTML, JavaScript, chessboard.js, chess.js
Backend:   Python, Flask, python-chess
Optional:  UCI protocol, Gaviota tablebases

------------------------------------
Installation & Setup
------------------------------------
1. Clone the repository:
   git clone https://github.com/your-username/flask-chess-engine.git
   cd flask-chess-engine

2. Install dependencies:
   pip install flask
   pip install python-chess[uci,gaviota]

3. Run the server:
   python app.py

4. Open in your browser:
   http://127.0.0.1:5000

------------------------------------
Future Improvements
------------------------------------
- AI opponent (Stockfish integration)
- Multiplayer with WebSockets
- Save/load games from PGN files
- Online deployment (Heroku/Render)

------------------------------------
License
------------------------------------
MIT – feel free to use and modify.
