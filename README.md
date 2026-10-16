# 🚑 CarePulse – OPD Triage Assistant

CarePulse is a healthcare web application prototype designed to support outpatient department (OPD) patient registration, vital signs collection, patient history, and triage workflow management.

## ✨ Features
- Patient registration and symptom collection
- Vital signs recording
- Patient history management
- Triage assessment workflow
- PostgreSQL database integration

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python, FastAPI
- **Database:** PostgreSQL
- **Database Tool:** pgAdmin

## 📁 Project Structure
```text
CarePulse/
├── frontend/
│   ├── pages/
│   ├── css/
│   ├── js/
│   └── index.html
└── backend/
    ├── main.py
    ├── database.py
    ├── schemas.py
    ├── requirements.txt
    └── .env
```

## ⚙️ Setup

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd CarePulse
```

### 2. Set up the backend
```bash
cd backend
pip install -r requirements.txt
```

Configure your PostgreSQL connection in the `.env` file.

### 3. Start the backend
```bash
python -m uvicorn main:app --reload
```

API documentation: `http://127.0.0.1:8000/docs`

### 4. Run the frontend
Open `frontend/index.html` using a local development server, such as VS Code Live Server.

## 🔒 Important
- Never upload database passwords or secret keys to GitHub.
- Use synthetic patient data for testing.
- This is a project prototype, not a clinically validated diagnostic system. Triage decisions require appropriate clinical review.

## 👨‍💻 Project Status
Currently under development as a college project.

## 🏷️ Topics
`Healthcare` `Python` `FastAPI` `PostgreSQL` `JavaScript` `OPD` `CollegeProject`
