

# 📚 Learning Management System – React + Django Full Stack App

A full-featured **Learning Management System (LMS)** built with **React (Frontend)** and **Django (Backend)** to manage courses, users, content delivery, and tracking. It offers a seamless user experience with role-based access for students and instructors, along with real-time interaction features.



## 🔥 Key Features

✅ User authentication with role-based access (Admin, Instructor, Student)  
✅ Create and manage courses, lectures, and materials  
✅ Enroll students and track their progress  
✅ Upload video, PDF, and document resources  
✅ Interactive dashboard for each user type  
✅ Responsive UI with React  
✅ Django REST Framework API for scalable backend  
✅ Integrated SQLite or PostgreSQL database



## 🛠 Tech Stack

| Layer        | Technology Used              |
|--------------|------------------------------|
| **Frontend** | React, Axios, Bootstrap       |
| **Backend**  | Python, Django, Django REST   |
| **Database** | SQLite (dev) / PostgreSQL     |
| **Auth**     | JWT (Django SimpleJWT)        |
| **API**      | Django REST Framework         |



## 🚀 Getting Started

### ✅ Prerequisites

* Python 3.7 or higher  
* Node.js and npm  
* pip (Python package manager)  



### 🧰 Backend Setup (Django)

```bash
# Navigate into the backend directory
cd backend

# Create and activate a virtual environment
python -m venv env
env\Scripts\activate  # On Windows
# or
source env/bin/activate  # On macOS/Linux


# Apply migrations
python manage.py migrate

# Create a superuser
python manage.py createsuperuser

# Start the backend server
python manage.py runserver
````

Backend runs at: `http://127.0.0.1:8000`



### 🖥️ Frontend Setup (React)

```bash
# Navigate into the frontend directory
cd frontend

# Install dependencies
npm install

# Start the React development server
npm start
```

Frontend runs at: `http://localhost:3000`


## 🔐 Environment Variables

Set the following variables in a `.env` file (backend):

```env
SECRET_KEY=your_django_secret_key
DEBUG=True
DATABASE_URL=your_database_url_if_using_postgres
```

Frontend can include `.env` as:

```env
REACT_APP_API_URL=http://127.0.0.1:8000/api/
```



## 🌱 Future Enhancements

* 🎓 Quiz and assignment modules
* 📊 Course analytics for instructors
* 💬 Student discussions or forums
* 📥 CSV export of results and progress
* 📲 PWA support for mobile learning
* 🧾 Certificate generation for completed courses



## 👤 Contributors

* **Samiksha Walia**
[GitHub](https://github.com/Samiksha-Walia) • [LinkedIn](https://linkedin.com/in/samiksha-walia) 

* **Japesh Jhatta** 
[GitHub](https://github.com/japesh5579) • [LinkedIn](https://www.linkedin.com/in/japesh-jhatta)

* **Samdisha Walia** 
[GitHub](https://github.com/Samdisha-Walia) • [LinkedIn](https://linkedin.com/in/samdisha-walia) 




## ⭐️ Support This Project

If you found this project helpful, please consider giving it a ⭐️ on GitHub to show your support.

> 📝 *Built for academic, portfolio, and scalable LMS use cases. Inspired by real-world education platforms.*



