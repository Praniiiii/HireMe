# HireMe - Job Portal Web Application 🎯

**HireMe** is a web-based job portal designed to help **students** find and apply for job opportunities, while also enabling **recruiters** to post job listings and interact with potential candidates. This full-stack application is built with **Flask** as the backend, **HTML**, **CSS**, and **Bootstrap** for the frontend, and **SQLite** as the database (with an option to scale to MySQL or PostgreSQL). The platform also features secure authentication via **Flask-Login**, ensuring user privacy and safety.

---

## 🧑‍🎓 Student Functionality:

1. **Register and Log In Securely**: 
   - Students can register with their personal details and log in using a secure authentication system. Passwords are hashed and stored securely.

2. **View Available Job Listings**: 
   - Once logged in, students can browse through a list of available job postings. This may include details such as the job title, description, salary, and required qualifications.

3. **Apply to Jobs**: 
   - Students can apply to jobs they are interested in. The system keeps track of their applications and allows them to manage or withdraw applications if necessary.

4. **Manage Personal Profile and Applications**: 
   - Students can view and update their personal details, including their resume and skills, as well as monitor the status of their job applications (e.g., pending, accepted, or rejected).

---

## 🧑‍💼 Recruiter Functionality:

1. **Register and Log In as a Recruiter**: 
   - Recruiters have their own registration and login system, separate from students. This ensures that their posts and applicant management features are distinct and secure.

2. **Post Job Opportunities**: 
   - Recruiters can create and post job opportunities on the portal. They provide detailed information about the role, including title, description, required qualifications, location, salary range, and application deadlines.

3. **View Student Applications**: 
   - Recruiters can track and view the list of students who have applied to their job postings. This allows them to review resumes, cover letters, and student profiles.

4. **Contact Selected Candidates**: 
   - Recruiters can contact students directly through the portal to arrange interviews or provide further instructions. This can be integrated with an internal messaging system for ease of communication.

---

## 🛠️ Tech Stack

- **Backend**: Python, Flask
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (can be upgraded to MySQL/PostgreSQL)
- **Authentication**: Flask-Login

---

## 💡 Skills Required

- HTML
- CSS
- JavaScript
- SQL
- Python

---

## 🧰 Framework & Tools

- **Framework**: Flask
- **IDE**: Visual Studio Code (VS Code)

---

## 📝 Project Description

HireMe is a full-stack internship project designed to simulate a real-world job portal system. It includes features for both students and recruiters to manage jobs, applications, and interactions efficiently. The system also handles password resets and data management securely.

---

🌐 Project Web Pages
index – Homepage

- student_register – Student Registration
- student_login – Student Login
- student_home – Student Dashboard
- student_reset_password – Student Reset Password
- recruiter_register – Recruiter Registration
- recruiter_login – Recruiter Login
- recruiter_home – Recruiter Dashboard
- create_job – Job Posting Page
- job_details – Job Description for Students
- recruiter_job_details – Job Description for Recruiters
- recruiter_forgot_password – Recruiter Password Reset
- report – Report Generation / Summary
- database_setup – DB Initialization Script


## 📁 Project Setup

### 1. Clone the repository
```bash
git clone https://github.com/Praniiiii/HireMe.git
cd HireMe
```

### 2. Create and activate virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
python app.py
```

## 📸 Screenshots

### Home Page

![image](https://github.com/user-attachments/assets/f236c92a-e9db-41ae-aded-5fa15d068646)

### Student Registration

![image](https://github.com/user-attachments/assets/2a91ac72-2d99-4cf4-ad6a-2ba0f6773dce)

### Student Login

![image](https://github.com/user-attachments/assets/3d23d822-e83a-4c6d-b063-f097ff8eae39)

### Student Dashboard

![image](https://github.com/user-attachments/assets/3faf4c5d-f441-45a7-9db2-f861b5a47845)

### Student_reset_password

![image](https://github.com/user-attachments/assets/d77621c4-bd38-4417-a894-20289223f92d)

### Recruiter Registration

![image](https://github.com/user-attachments/assets/a811c789-d9f4-4499-b454-b33332cd597f)

### Recruiter Login

![image](https://github.com/user-attachments/assets/dbfa37b8-a592-45f7-80b0-d0009e8318b1)

### Recruiter Password Reset

![image](https://github.com/user-attachments/assets/fb8803d5-b617-46e9-81cd-05f16402bc0b)

### create_job – Job Posting Page

![image](https://github.com/user-attachments/assets/76596418-ec83-43b6-a18c-06a8cf068d14)

### Job Description for Recruiters

![image](https://github.com/user-attachments/assets/3317133a-4cd5-4d62-9c52-0bbe04b7a987)


### Report Generation / Summary

![image](https://github.com/user-attachments/assets/f4362073-67aa-4b50-861d-506d59512d9f)


---

## 🤝 Contributing

Contributions are welcome and appreciated! 🙌

If you'd like to contribute to **HireMe**, follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add your message here'`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Open a pull request

Please make sure your code follows best practices and is well-documented.

---

⭐ If you like this project, don't forget to give it a star!
