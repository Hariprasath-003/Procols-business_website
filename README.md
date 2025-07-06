# Student Project Business Website 🎓

A responsive business website designed for a startup offering college-student project services — showcases services, collects enquiries, and features student audio reviews.

---

🌐 **Live Demo:** [https://procols-m0n6.onrender.com](https://procols-m0n6.onrender.com)

---
## 🧩 Overview

This website helps a startup attract clients by showcasing their project offerings and gathering leads. Key highlights include a “Free Consultation” form, audio-based student reviews, and a responsive design that adapts seamlessly across devices.

---

## 🚀 Features

- Company profile and detailed service sections  
- “Free Consultation” form that sends email notifications to the admin  
- Student review section with **embedded audio** feedback  
- Fully ***mobile-responsive*** user interface  
- Admin dashboard to view and manage form submissions

---

## 🛠️ Technologies Used

- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Backend:** Django (Python)  
- **Database:** MySQL  
- **Version Control:** Git / GitHub

---

## 📥 Setup & Installation

1. **Clone the repo**
   ```bash
   git clone https://github.com/Hariprasath-003/Procols-business_website.git
   cd Procols-business_website
   ```

2. **Create a virtual environment & install dependencies**
   ```bash
   python3 -m venv env
   source env/bin/activate
   pip install -r requirements.txt
   ```

3. **Apply migrations**
   ```bash
   python manage.py migrate
   ```

4. **Create a superuser (for admin)**
   ```bash
   python manage.py createsuperuser
   ```

5. **Run the server**
   ```bash
   python manage.py runserver
   ```

   Visit `http://127.0.0.1:8000/` in your browser.

---

## 🎯 Usage

- **Explore the homepage:** See services and company overview  
- **Free Consultation:** Fill out and submit, admin receives email  
- **Student Reviews:** Listen to audio testimonials  
- **Admin Dashboard:** Log in at `/admin/` to manage submissions and content

---

## 🛡️ Future Improvements

- Add **reCAPTCHA** to the consultation form  
- Enable **student audio uploads** via the frontend  
- Include **video testimonials** from students  
- Integrate a **CMS** for admin-managed content

---

## 🧑‍💻 About the Author

**Hariprasath L**  
Freelance Full‑Stack Developer  

Passionate about building responsive, secure web applications  
[GitHub](https://github.com/Hariprasath-003) | [LinkedIn](https://www.linkedin.com/in/hariprasath-l-174b54270)

---
