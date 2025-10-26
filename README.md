This project is an AI-powered Career Guidance Platform that helps students choose the right career path after 12th. It includes a frontend built with HTML, CSS, and JavaScript containing pages like BCA, BBA, MBBS, Law, and more, along with a chatbot and quiz for guidance. The backend, developed using Flask (Python), processes user inputs and provides suitable career suggestions. The project aims to simplify career decision-making by combining technology and education into one interactive web platform.



Career Guidance Platform — Project Workflow

📁 Project Structure

Career Guidance/
│
├── BACKEND/
│   ├── app.py                # Flask backend main file
│   ├── index.py              # Additional backend logic
│   ├── requirement.txt       # Python dependencies
│
├── FRONTEND/
│   ├── index.html            # Home page
│   ├── chatbot.html          # Chatbot UI for student interaction
│   ├── quiz.html             # Career quiz page
│   ├── animation.html        # Intro or transition animations
│   ├── logic.html            # Logic-based course page
│   ├── law.html              # Law course details page
│   ├── mbbs.html             # Medical course details page
│   ├── bca.html              # BCA course details page
│   ├── bba.html              # BBA course details page
│   ├── ba.html               # BA course details page
│   ├── bsc.html              # B.Sc course details page
│   ├── btech.html            # B.Tech course details page
│
├── venv/                     # Virtual environment (Python)
│
└── tempCodeRun.py            # Temporary run/debug file

⚙ How It Works

1. Frontend (HTML, CSS, JS)
Students explore various courses, attempt quizzes, and interact with the AI-powered chatbot.


2. Backend (Flask - Python)
Handles requests from the frontend, processes chatbot messages, and returns AI-generated career suggestions.


3. Integration
Frontend pages (HTML) connect to the Flask API (via app.py) using fetch or AJAX requests.


4. Deployment

Host frontend on GitHub Pages or Netlify.
