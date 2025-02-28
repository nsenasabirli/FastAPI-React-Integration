# FastAPI-React-Integration

How to connect a FastAPI Backend to a React Frontend, we'll do this from scratch.

![Ekran Resmi 2025-02-28 14 53 57](https://github.com/user-attachments/assets/8ca58d80-6e0e-456d-9a61-fb10b6187d78)

#FastAPI Setup

Python 3.9+
Setup
mkdir backend
cd backend
Create a virtual environment: python3 -m venv venv
Activate the virtual environment:
Mac/Linux: source ./venv/bin/activate
Windows: .\venv\Scripts\activate
Install the dependencies from requirements.txt
pip install -r requirements.txt

#Run the API
python main.py

#React Setup

Dependencies
NodeJS

Setup
npm create vite@latest frontend --template react
cd frontend
npm install
npm install axios

Components
Make the following dir structure
src/
  components/
    Fruits.jsx
    AddFruitForm.jsx
    App.jsx
    main.jsx
    api.js

#Run the App

npm run dev

![Ekran Resmi 2025-02-28 15 49 35](https://github.com/user-attachments/assets/c7438efe-e585-4b03-81f1-c6c3f08a9219)

![Ekran Resmi 2025-02-28 16 06 41](https://github.com/user-attachments/assets/0c021688-4754-4b5d-b756-0171624c499b)

