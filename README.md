# 🚀 JobTrackr – Django-based Job Application Tracker

**JobTrackr** is a full-featured job application management system built using **Django**. It allows users to efficiently manage job applications, track follow-ups, explore jobs posted by admins, and personalize their profiles. Admins can manage available job listings, monitor user activity, and perform CRUD operations.

---

## 📌 Features

### 👤 General User
- 🔐 **User Registration/Login/Logout**
- 🏠 **Dashboard** showing job stats
- ➕ Add, edit, delete job applications
- 📆 Set follow-up reminders
- 🔎 **Search and filter** job applications by status
- 🌙 **Toggle dark/light theme**
- 📂 **Editable user profile**
- 💼 **View available jobs** posted by admin
- ✅ Apply to jobs with one click

### 🛠️ Admin Panel
- 👨‍💼 Admin dashboard with user/job stats
- ➕ Post new available jobs
- 🗑️ Delete posted jobs
- 📈 View registered users and their info

### 🎨 UI/UX
- Bootstrap 5 UI with responsive design
- Centered and styled forms with help text
- Blue buttons, hover effects, alerts
- Interactive layout with visual feedback
- Dark mode support using `data-bs-theme`

---

## 🧰 Tech Stack

- **Backend**: Django 4.x
- **Frontend**: HTML5, CSS3, Bootstrap 5, Jinja2 Templates
- **Database**: SQLite3
- **Authentication**: Django built-in auth
- **Styling**: Custom CSS + Bootstrap 5

---

## 🛠️ Installation

# Clone the repo
git clone https://github.com/AlinaMehboobkhan/jobtrackr.git
cd jobtrackr

# Create virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create superuser for admin panel
python manage.py createsuperuser

# Run the server
python manage.py runserver
