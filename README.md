# Basic FastAPI App

A beginner-friendly REST API built using **FastAPI** and **Uvicorn** as part of the **CAIE Course Program - Assignment 4**.

## 📌 Project Overview

This project demonstrates the basics of creating a web API with FastAPI. It includes:

- A root endpoint (`/`) that returns a welcome message.
- A dynamic endpoint that accepts a URL parameter and returns a personalized response.
- Automatic interactive API documentation provided by FastAPI.

---

## 🚀 Features

- Built with **FastAPI**
- Runs using **Uvicorn**
- JSON responses
- Dynamic path parameter endpoint
- Interactive API documentation at `/docs`

---

## 🛠️ Technologies Used

- Python 3
- FastAPI
- Uvicorn

---

## 📂 Project Structure

```
fastapi-basic-app/
│── main.py
│── README.md
└── venv/
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/fastapi-basic-app.git
cd fastapi-basic-app
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows (PowerShell)**

```powershell
venv\Scripts\Activate.ps1
```

**Windows (Command Prompt)**

```cmd
venv\Scripts\activate.bat
```

**macOS/Linux**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install fastapi uvicorn
```

---

## ▶️ Run the Application

Start the server using:

```bash
uvicorn main:app --reload
```

The application will be available at:

- **API:** http://127.0.0.1:8000
- **Interactive Docs (Swagger UI):** http://127.0.0.1:8000/docs
- **ReDoc Documentation:** http://127.0.0.1:8000/redoc

---

## 📖 API Endpoints

### GET /

Returns a welcome message.

**Response**

```json
{
  "message": "Hello, FastAPI"
}
```

---

### GET /greet/{name}

Returns a personalized greeting.

**Example**

```
GET /greet/Alice
```

**Response**

```json
{
  "message": "Hello, Alice!"
}
```

> Replace `greet` with your endpoint name if you used a different one.

---

## 📸 Assignment Requirements Completed

- ✅ FastAPI application created
- ✅ Root endpoint implemented
- ✅ Dynamic endpoint with URL parameter
- ✅ JSON responses
- ✅ Uvicorn server used
- ✅ Interactive API documentation verified
- ✅ Single `main.py` file

---

## 📚 Learning Outcomes

Through this project, I learned how to:

- Create APIs using FastAPI.
- Define GET endpoints.
- Use path parameters.
- Return JSON responses.
- Run a FastAPI application with Uvicorn.
- Explore and test APIs using Swagger UI.

---

## 👨‍💻 Author

**K.Sivakumar**

GitHub: https://github.com/147Sivakumar
