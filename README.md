# 🎓 Examination Management Portal

A web-based **Examination Management Portal (EMP)** built as a college project to manage examinations, examiners, students, examination slots, bookings, and evaluations.

> 🚧 **Project Status: In Progress**
>
> I am currently learning the technologies required for this project. I have completed the basics of **HTML and CSS** and will be building the application step by step while learning Flask, Jinja2, Bootstrap, SQLite, and backend development.

---

## 📌 About the Project

Educational institutions often manage examinations using spreadsheets, emails, and manual coordination. This can make it difficult to manage:

- Examination schedules
- Examiner availability
- Examination slots
- Student bookings
- Examiner assignments
- Student evaluations
- Examination results

The **Examination Management Portal** aims to provide a centralized web application where administrators, examiners, and students can manage these activities according to their roles.

This project is being developed as part of my college project work.

---

## 🎯 Project Objectives

The main objectives of this project are:

- Learn how a complete web application is developed.
- Understand frontend and backend integration.
- Build a role-based authentication system.
- Manage data using SQLite.
- Create examination and course management functionality.
- Allow examiners to create examination slots.
- Allow students to book available slots.
- Implement examination evaluation and result management.
- Practice database design and relationships.
- Understand Flask and Jinja2 through a practical project.

---

## 👥 User Roles

The application will have three main types of users.

### 👨‍💼 Admin

The Admin will manage the complete examination system.

Planned functionalities:

- Manage courses
- Manage examinations
- Manage examination rubrics
- Approve/deactivate examiners
- Configure examination timelines
- Open/close slot creation
- Open/close student booking
- View examination slots
- Manage bookings
- Reschedule bookings
- Change examiner assignments
- Search students, examiners, examinations and bookings
- View system statistics

### 👨‍🏫 Examiner

Examiners will be responsible for conducting examinations and evaluating students.

Planned functionalities:

- Register and login
- Wait for Admin approval
- View assigned examinations
- Create examination slots
- Update/delete slots before booking begins
- View students booked in their slots
- Evaluate students
- Submit marks and remarks

### 👨‍🎓 Student

Students will use the portal to find and book examination slots.

Planned functionalities:

- Register and login
- View available examinations
- Search/filter examinations
- View available slots
- Book examination slots
- Cancel bookings before the deadline
- View upcoming examinations
- View booking history
- View published results and feedback
- Edit profile

---

## 🛠️ Technologies

The project will be developed using the technologies specified in the college project requirements.

| Technology   | Purpose                                |
| ------------ | -------------------------------------- |
| HTML5        | Structure of web pages                 |
| CSS3         | Basic styling                          |
| Bootstrap    | Responsive user interface              |
| Python       | Backend programming                    |
| Flask        | Web application backend                |
| Jinja2       | Server-side templating                 |
| SQLite       | Database                               |
| Git & GitHub | Version control and project management |

### Important Project Constraints

- Flask must be used for the backend.
- Jinja2 must be used for templating.
- HTML, CSS and Bootstrap will be used for the frontend.
- SQLite is the only database.
- The database will be created programmatically.
- JavaScript will not be used for core requirements.

---

# 🗂️ Planned Project Structure

The folder structure may change as I learn and develop the application.

```text
Examination-Management-Portal/
│
├── app/
│   ├── __init__.py
│   ├── models.py
│   ├── routes.py
│   │
│   ├── templates/
│   │   ├── base.html
│   │   ├── login.html
│   │   ├── register.html
│   │   │
│   │   ├── admin/
│   │   ├── examiner/
│   │   └── student/
│   │
│   └── static/
│       ├── css/
│       └── images/
│
├── instance/
│   └── database.db
│
├── requirements.txt
├── run.py
├── README.md
└── .gitignore
```

> This is a planned structure. The actual structure will evolve as the project develops.

---

# 🗄️ Planned Database

The database will be implemented using **SQLite** and created through Python/Flask code.

Some planned entities include:

- User
- Student
- Examiner
- Course
- Examination
- Examination Rubric
- Examination Slot
- Booking
- Evaluation

The exact database structure may change as development progresses.

---

# 🚀 Core Features to Implement

### Authentication

- [ ] Admin login
- [ ] Student registration/login
- [ ] Examiner registration/login
- [ ] Role-based access
- [ ] Examiner approval by Admin

### Admin

- [ ] Admin dashboard
- [ ] Course management
- [ ] Examination management
- [ ] Rubric management
- [ ] Examiner management
- [ ] Timeline configuration
- [ ] Slot management
- [ ] Booking management
- [ ] Student management
- [ ] Search functionality
- [ ] Examiner reassignment
- [ ] Booking rescheduling

### Examiner

- [ ] Examiner dashboard
- [ ] View assigned examinations
- [ ] Create examination slots
- [ ] Edit slots
- [ ] Delete slots
- [ ] View booked students
- [ ] Evaluate students
- [ ] Submit marks and remarks

### Student

- [ ] Student dashboard
- [ ] View examinations
- [ ] Search examinations
- [ ] Filter examinations
- [ ] View available slots
- [ ] Book a slot
- [ ] Cancel booking
- [ ] View upcoming examinations
- [ ] View booking history
- [ ] View results
- [ ] View feedback
- [ ] Edit profile

---

# 📚 Learning & Development Roadmap

I am building this project while learning the required technologies. I will update this table regularly as I make progress.

| Day    | Topic / Technology   | What I Learned                          | What I Built / Practiced      | Status         |
| ------ | -------------------- | --------------------------------------- | ----------------------------- | -------------- |
| Day 1  | HTML Basics          | HTML structure, headings, paragraphs    | Basic HTML pages              | ✅ Completed    |
| Day 2  | HTML Forms           | Forms, inputs, labels, buttons          | Registration/Login form UI    | ⬜ Planned      |
| Day 3  | HTML Tables & Lists  | Tables, lists and semantic HTML         | Basic data page               | ⬜ Planned      |
| Day 4  | CSS Basics           | Selectors, properties, box model        | Styled HTML pages             | ✅ Completed    |
| Day 5  | CSS Layout           | Flexbox, positioning, spacing           | Dashboard layout practice     | ⬜ Planned      |
| Day 6  | Bootstrap            | Containers, rows, columns, cards        | Responsive dashboard UI       | ⬜ Planned      |
| Day 7  | Git & GitHub         | Repository, commit, push                | Created project repository    | 🔄 In Progress |
| Day 8  | Python Basics        | Variables, conditions, loops, functions | Python practice               | ⬜ Planned      |
| Day 9  | Flask Basics         | Flask app, routes                       | First Flask application       | ⬜ Planned      |
| Day 10 | Jinja2               | Templates and template inheritance      | Dynamic HTML pages            | ⬜ Planned      |
| Day 11 | Flask Forms          | Handling form data                      | Registration/login backend    | ⬜ Planned      |
| Day 12 | SQLite               | Tables, queries, relationships          | First database                | ⬜ Planned      |
| Day 13 | Flask + SQLite       | Connecting application and database     | CRUD practice                 | ⬜ Planned      |
| Day 14 | Authentication       | Login and session handling              | User authentication           | ⬜ Planned      |
| Day 15 | Role Management      | Admin/Examiner/Student roles            | Role-based pages              | ⬜ Planned      |
| Day 16 | Course Module        | CRUD operations                         | Admin course management       | ⬜ Planned      |
| Day 17 | Examination Module   | Examination database/model              | Admin examination management  | ⬜ Planned      |
| Day 18 | Rubrics              | Rubric design                           | Examination rubric management | ⬜ Planned      |
| Day 19 | Examiner Module      | Examiner workflow                       | Examiner dashboard            | ⬜ Planned      |
| Day 20 | Slot Management      | Slot creation and capacity              | Examiner slot management      | ⬜ Planned      |
| Day 21 | Student Module       | Student workflow                        | Student dashboard             | ⬜ Planned      |
| Day 22 | Booking System       | Booking rules and validation            | Student slot booking          | ⬜ Planned      |
| Day 23 | Evaluation           | Marks and remarks                       | Examiner evaluation system    | ⬜ Planned      |
| Day 24 | Admin Controls       | Rescheduling/reassignment               | Admin booking management      | ⬜ Planned      |
| Day 25 | Validation & Testing | Backend validation                      | Test core workflows           | ⬜ Planned      |
| Day 26 | UI Improvement       | Bootstrap and responsive design         | Improve application UI        | ⬜ Planned      |
| Day 27 | Final Testing        | Find and fix bugs                       | End-to-end testing            | ⬜ Planned      |
| Day 28 | Documentation        | Project documentation                   | README + report preparation   | ⬜ Planned      |
| Day 29 | Presentation         | Project explanation                     | Demo/video preparation        | ⬜ Planned      |
| Day 30 | Final Submission     | Final review                            | Project submission            | ⬜ Planned      |

> **Note:** The roadmap is flexible. I will update it based on my actual learning progress rather than following the dates strictly.

---

# 📈 Current Progress

### Frontend

- [x] HTML basics
- [x] CSS basics
- [ ] Bootstrap
- [ ] Responsive design
- [ ] Final UI

### Backend

- [ ] Python revision
- [ ] Flask
- [ ] Jinja2
- [ ] Flask routing
- [ ] Form handling
- [ ] Authentication

### Database

- [ ] SQLite basics
- [ ] Database design
- [ ] Flask + SQLite integration
- [ ] Relationships
- [ ] CRUD operations

### Application

- [ ] Admin module
- [ ] Examiner module
- [ ] Student module
- [ ] Examination module
- [ ] Slot booking
- [ ] Evaluation
- [ ] Results

### Documentation

- [ ] ER Diagram
- [ ] API documentation (if implemented)
- [ ] Project report
- [ ] Presentation
- [ ] Demo video

---

# 🔄 Development Approach

I am following a step-by-step development approach:

```text
Learn HTML/CSS
      ↓
Learn Bootstrap
      ↓
Learn Python
      ↓
Learn Flask
      ↓
Learn Jinja2
      ↓
Learn SQLite
      ↓
Connect Flask + SQLite
      ↓
Build Authentication
      ↓
Build Admin Module
      ↓
Build Examiner Module
      ↓
Build Student Module
      ↓
Implement Slot Booking
      ↓
Implement Evaluation
      ↓
Testing
      ↓
Documentation
      ↓
Final Project
```

The goal is to understand each part before moving to the next stage.

---

# 🧪 Testing Goals

The application should eventually handle important cases such as:

- Preventing duplicate bookings for the same examination.
- Preventing booking when the booking period is closed.
- Preventing slot creation outside the allowed period.
- Preventing overbooking.
- Allowing only approved examiners to access examiner functionality.
- Allowing examiners to evaluate only students assigned to their slots.
- Allowing Admin to reschedule bookings.
- Maintaining examination and booking history.

---

# 🌱 Current Learning Philosophy

This project is also a learning journey for me.

Instead of trying to build the entire application at once, I am breaking the project into smaller concepts and learning them one by one.

My current focus is:

> **HTML → CSS → Bootstrap → Python → Flask → Jinja2 → SQLite → Full Web Application**

I will keep updating this repository as I learn new concepts and implement them in the project.

---

# 📌 Project Status

**Current Stage:** 🟡 Learning & Initial Development

**Completed:**

- HTML basics
- CSS basics
- Initial Git/GitHub setup

**Currently Learning:**

- Preparing the frontend structure
- Planning the Flask application
- Understanding database requirements

**Next Goal:**

- Learn Bootstrap
- Start Python/Flask development
- Create the first Flask application

---

# 📖 Future Improvements

Depending on the time available, additional features may include:

- Examination statistics
- Dashboard charts
- Downloadable scorecards
- Email notifications
- Additional search/filter options
- Improved responsive UI
- API endpoints
- Better validation and error handling

---

# 🤖 AI/LLM Usage

AI/LLM tools may be used during development as a learning and assistance tool.

Any AI/LLM usage will be disclosed according to the college's project requirements. I will make sure that I understand the code used in the final project and can explain it during the viva.

---

# 👨‍💻 Author

**Aman Raj Kumar**

College Project — Examination Management Portal

---

## ⭐ Project Journey

This repository is not just the final project; it also represents my learning journey from **HTML/CSS basics to building a complete Flask-based web application**.

I will keep updating the repository as I learn, build, test, and improve the Examination Management Portal.
