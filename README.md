# JoOUSTConnect - University Social Networking Platform

A web application designed for **university students** to socialize, connect, and chat in real-time. The platform is inspired by **X (formerly Twitter)** and allows students to share posts, comment, like, and chat using **Daphine**.

---

## 🚀 Features

* Social feed similar to X (formerly Twitter)
* Real-time chat powered by Daphine
* User profiles for students
* Posting, commenting, and liking functionality
* Search and follow other students
* Environment-based configuration
* Optimized for university networking

---

## 🛠️ Tech Stack

* Python 3.x
* Django 4.x
* Daphine for real-time chat
* HTML / CSS / JavaScript
* SQLite (default database)

---

## 📦 Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/yourusername/jooustconnect.git
cd jooustconnect
```

### 2️⃣ Create a virtual environment

```
python3 -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows
```

### 3️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 4️⃣ Setup environment variables

Create a `.env` file based on `.env.example`:

```
DJANGO_SECRET_KEY=your_django_secret_key
DEBUG=True
```

### 5️⃣ Apply database migrations

```
python manage.py migrate
```

### 6️⃣ Create a superuser (optional for admin)

```
python manage.py createsuperuser
```

### 7️⃣ Run the development server

```
python manage.py runserver
```

Open your browser and go to:

```
http://127.0.0.1:8000/
```

---

## 💬 Daphine Chat Setup

1. Ensure Daphine server is running locally or hosted
2. Configure the chat settings in `.env` or `settings.py`
3. Real-time chat will now be available for all connected students

---

## 🧪 Test Users

* Create multiple student accounts to test social feed and real-time chat functionality
* Follow, like, post, and chat to test full feature set

---

## 📄 License

MIT License

---

## 👨‍💻 Author

VALENTINO ACHIRA
