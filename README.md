# 💼 ResumeCraft – Builder

**ResumeCraft** is a smart, responsive web app that allows users to create, preview, and download professional resumes effortlessly. Designed for job seekers, students, and professionals, this platform makes resume-building quick, simple, and beautiful — no templates, no stress.

---

## 🌟 Features

✅ Multi-step form to gather all resume details  
✅ Real-time live preview as you type  
✅ Download resume in PDF format  
✅ Secure OTP-based password recovery  
✅ Clean, responsive UI (desktop + mobile)  
✅ Custom templates for elegant layouts  
✅ Built from scratch — no third-party builders

---

## 🛠️ Tech Stack

**Frontend:**  
- HTML  
- CSS  
- Tailwind CSS  
- Bootstrap  
- JavaScript

**Backend:**  
- PHP  
- PHPMailer (for sending OTP emails)

---

## 🔐 Security Highlights

- Real-time OTP-based password reset flow  
- Validation and sanitization for all form inputs  
- Sessions used to manage authenticated users

---

## 📸 Screenshots

| Resume Preview | OTP Page | Responsive Form |
|----------------|----------|------------------|
| ![Preview](./screenshots/resume-preview.png) | ![OTP](./screenshots/otp-page.png) | ![Form](./screenshots/form-view.png) |

> 📌 _Add your screenshots to the `/screenshots` folder to display properly here._

---

## 📂 Project Structure

ResumeCraft/ ├── assets/ │ ├── css/ │ └── js/ ├── templates/ │ └── resume-template.php ├── includes/ │ └── db.php │ └── functions.php ├── otp/ │ └── send-otp.php │ └── verify-otp.php ├── index.php ├── resume-preview.php └── generate-pdf.php

---

## 🚀 How to Run Locally

1. Clone the repo  
git clone https://github.com/yourusername/resumecraft.git
Set up XAMPP / WAMP

Import the resumecraft.sql database

Configure your SMTP credentials in send-otp.php

Start Apache + MySQL

Navigate to http://localhost/resumecraft

📬 Contact & Collaboration
Built with 💙 by Team UNIX
Open to collaborations, internships, or freelance work!

📧 1234@example.com

🔗 LinkedIn

🔗 Demo Video

🔗 Live Project (if deployed)

📄 License
This project is open-source under the MIT License.

⭐ Don’t forget to star this repo if you found it helpful!

---
