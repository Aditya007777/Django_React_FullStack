# Django React FullStack Project

This is a full-stack web application built using **Django (Backend) and React (Frontend)**.  
The backend is deployed on **Choreo**, but you can also run it locally.

## 🌍 Live Deployment (Choreo)

The backend is deployed on **Choreo**. You can access the API at:

```
https://452b754f-bdee-4f1f-a576-ed044b08dc98.e1-eu-north-azure.choreoapps.dev
```

---

## 🛠️ Running the Project Locally

Follow these steps to set up and run the project on your local machine.

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/Aditya007777/Django_React_FullStack.git
cd Django_React_FullStack
```

### 2️⃣ Backend Setup (Django)

#### Install Dependencies

Ensure **Python (>=3.8)** and **PostgreSQL** are installed. Then run:

```sh
cd backend
python -m venv venv  # Create a virtual environment
source venv/bin/activate  # Activate (Linux/Mac)
venv\Scripts\activate  # Activate (Windows)
pip install -r requirements.txt  # Install dependencies
```

#### Configure Environment Variables

Create a `.env` file in the `backend/` directory based on `.env.example` and update:

```ini
DB_NAME=your_db_name
DB_USER=your_db_user
DB_PWD=your_db_password
DB_HOST=localhost
DB_PORT=5432
SECRET_KEY=your_secret_key
DEBUG=True
```

#### Apply Migrations & Start Server

```sh
python manage.py migrate
python manage.py runserver
```

The backend should now run at **`http://127.0.0.1:8000/`**.

---

### 3️⃣ Frontend Setup (React)

#### Install Dependencies

```sh
cd ../frontend
npm install
```

#### Start the React App

```sh
npm start
```

The frontend will run at **`http://localhost:3000/`**.

---

## 🔗 API Endpoints

| Method | Endpoint       | Description                |
|--------|---------------|----------------------------|
| GET    | /api/         | Test API                   |
| POST   | /api/login/   | User Login (JWT)           |
| GET    | /api/data/    | Fetch Data                 |

For a full list, check **Django `urls.py`**.

---

## 📌 Features

✅ **User Authentication (JWT)**  
✅ **CRUD Operations**  
✅ **Django REST Framework (DRF) APIs**  
✅ **React Frontend**  
✅ **PostgreSQL Database**  
✅ **CORS Configured for Frontend-Backend Communication**  

---

## 🎯 Contributing

1. **Fork the repository**  
2. **Create a new branch** (`git checkout -b feature-name`)  
3. **Commit your changes** (`git commit -m "Added feature"`)  
4. **Push the branch** (`git push origin feature-name`)  
5. **Open a Pull Request**  

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 🌟 Contact & Support

For issues and contributions, open an issue in the repo:  
🔗 [GitHub Repo](https://github.com/Aditya007777/Django_React_FullStack)
