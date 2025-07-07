# 🩸 BloodConnect

**BloodConnect** is a full-stack web platform designed to facilitate blood donation and request management. It connects patients, donors, and blood banks with ease.

Built with:
- ⚙️ **FastAPI** for the backend
- ⚛️ **React + Vite + Material UI (MUI)** for the frontend
- 🗄️ **SQLite** with SQLAlchemy ORM for data handling

---

## 👨‍💻 Developed by

- **Arein Jain** ([@areinjain](https://github.com/areinjain))
- **Aryan Tripathi** ([@aryantripathi](https://github.com/aryantripathi))

---

## 🌐 Project Structure

```
BloodConnect/
├── BloodConnect_Frontend_UI/   # React + Vite + MUI frontend
├── BloodConnect_Backend/       # FastAPI + SQLite backend
└── README.md                   # Project overview
```

---

## 🚀 Features

- Submit blood requests with details like name, blood group, urgency, and location
- View all submitted blood requests
- Responsive UI with clean Material UI components
- Realtime form validation and alerts
- Modular and scalable backend APIs

---

## 🛠️ How to Run the Project

### ✅ 1. Clone the Repo

```bash
git clone https://github.com/YOUR_USERNAME/BloodConnect.git
cd BloodConnect
```

---

### ⚙️ 2. Run Backend (FastAPI)

```bash
cd BloodConnect_Backend/backend
python -m venv venv
.env\Scriptsctivate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

> Runs at: `http://localhost:8000`

---

### 🎨 3. Run Frontend (React + Vite)

```bash
cd ../../BloodConnect_Frontend_UI
npm install
npm run dev
```

> Runs at: `http://localhost:5173`

---

## 🧪 API Endpoint (Sample)

POST blood request:

```http
POST /request/create
Content-Type: application/json
```

```json
{
  "name": "Aryan Tripathi",
  "bloodGroup": "A+",
  "location": "Delhi",
  "quantity": 2,
  "userId": "2401020040",
  "urgencyLevel": "High"
}
```

---

## 📷 Screenshots

> (You can add screenshots here if you'd like later)

---

## 🤝 Contributions

Built as a collaborative project for learning and real-world application.

---

## 📄 License

MIT License – feel free to use and contribute!

---

> Made with ❤️ by **Arein Jain** & **Aryan Tripathi**
