 # 🧪 Mock-Interview-An-AI-Driven-Tool-for-Evaluating-Emotions-and-Communication-Skills(Django Web App)

An end-to-end **Online Examination System** built using **Django**, designed to digitize the process of conducting tests, evaluating results, and managing users. This project serves as a digital platform for educational institutions, coaching centers, or companies to create, assign, and grade exams with efficiency and security.

---

## 📚 Overview

The **Online Examination System** solves the challenge of conducting exams at scale, especially in remote or blended learning environments. It allows administrators to create subjects and exams, assign them to students, monitor participation, and automatically evaluate answers.

Key user roles include:

- **Admin**: Manages users, subjects, and exam settings.
- **Teacher/Examiner**: Creates exams and questions, reviews results.
- **Student**: Takes assigned exams, views results and feedback.

This project is ideal for institutions looking to minimize manual work, reduce paper use, and support online learning and assessments.

---

## 🎯 Key Features

- 🧑‍🏫 Role-based user management (Admin, Examiner, Student)
- 📝 Create and manage multiple-choice and descriptive questions
- 📅 Schedule exams with start/end time, duration
- 🧪 Auto-evaluation of objective questions
- 🗃️ Detailed result reports per student
- 🔐 Secure exam sessions with session management
- 📤 Upload documents/questions (optional)
- 📈 Dashboard with analytics (score trends, pass rate, etc.)
- ✉️ Email notifications for assignments and results (optional)
- 📄 Certificate generation (extendable)

---

## 🛠️ Tech Stack

| Layer         | Technology        |
|--------------|-------------------|
| Backend       | Django (Python)   |
| Frontend      | HTML5, CSS3, Bootstrap |
| Database      | SQLite / PostgreSQL |
| Authentication| Django Auth       |
| Admin Panel   | Django Admin      |

---

## 📁 Project Structure

```
examination-system/
├── core/                   # Core app with models, views, logic
│   ├── models.py           # User, Exam, Question, Result, etc.
│   ├── views.py            # Exam logic, submissions, result processing
│   ├── urls.py             # URL routing
│   ├── forms.py            # Input validation
│   └── admin.py            # Django admin customization
├── templates/              # HTML templates for UI
├── static/                 # CSS, JS, and image assets
├── media/                  # User-uploaded files
├── manage.py               # Django CLI utility
├── db.sqlite3              # Default database
└── requirements.txt        # Python dependencies
```

---

## ⚙️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/online-exam-system.git
cd online-exam-system
```

2. **Create and activate a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. **Install dependencies**

```bash
pip install -r requirements.txt
```

4. **Run migrations**

```bash
python manage.py migrate
```

5. **Create superuser**

```bash
python manage.py createsuperuser
```

6. **Start the development server**

```bash
python manage.py runserver
```

---

## 🧪 Running Tests

```bash
python manage.py test
```

Unit tests cover models, views, and business rules.

---

## 🌍 Future Improvements

- Webcam proctoring with face detection
- Timer countdown on exam pages
- Plagiarism detection for answers
- API access for mobile apps
- Detailed logging and analytics dashboard

---

## 📄 License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute it with attribution.

---

## 👤 Author & Contributions

Built by Ambati Teja Sri Surya – contributions are welcome!  
Fork the repo and open a pull request to get involved.
