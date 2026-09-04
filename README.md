# 📊 Data Analyst Job Search Tracker

> **A modern, responsive web application for managing job applications, recruiter interactions, follow-ups, interviews, referrals, and job-search analytics — built with HTML, CSS, and JavaScript.**

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/LocalStorage-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="LocalStorage">
  <img src="https://img.shields.io/badge/Responsive-Design-18A86B?style=for-the-badge" alt="Responsive Design">
</p>

<p align="center">
  <a href="https://data-analyst-job-search-tracker.vercel.app/">Live Demo</a> •
  <a href="#-features">Features</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-project-structure">Project Structure</a>
</p>

---

## 🎯 Project Overview

Searching for a Data Analyst role often involves managing dozens of applications across LinkedIn, company career pages, referrals, and recruiter conversations.

I built **Data Analyst Job Search Tracker** to solve this problem with a simple, centralized dashboard.

Instead of maintaining scattered notes or spreadsheets, the application allows users to:

* Track every job application
* Store recruiter information
* Schedule follow-ups
* Monitor interview progress
* Track referrals and connections
* Analyze application performance
* Export and import application data

The project demonstrates how **front-end development and data-driven thinking** can be combined to build a practical productivity application.

---

## ✨ Key Features

### 📊 Interactive Dashboard

Get an immediate overview of your job search:

* Total applications
* Interviews
* Offers
* Rejections
* Saved opportunities
* Follow-ups due
* Interview conversion rate
* Application status distribution
* Applications over time

---
## 📸 Screenshots

### 📊 Dashboard

<img width="1916" height="842" alt="Dashboard" src="https://github.com/user-attachments/assets/389e4e58-63aa-4170-8639-c194ad072761" />


### 📝 Application Tracker

<img width="1915" height="862" alt="Applications" src="https://github.com/user-attachments/assets/08da7921-7aca-4c88-9d8f-cd845586a7c2" />


### 📅 Follow-up Management

<img width="1917" height="862" alt="Follow-Ups" src="https://github.com/user-attachments/assets/cd77e714-5f93-465d-8745-d74b495fb05d" />


### 📈 Analytics

<img width="1912" height="865" alt="Analytics" src="https://github.com/user-attachments/assets/8bc80e9f-bece-46b4-8ba5-a3c2b36d8e51" />

### 🌙 Dark Mode

<img width="1912" height="861" alt="Dark mode" src="https://github.com/user-attachments/assets/95a39e85-1300-4994-b961-718e4b6f7f7d" />


---

### 📝 Application Management

Create and manage detailed job application records.

Each application can include:

| Field                | Description                    |
| -------------------- | ------------------------------ |
| 🏢 Company           | Target company                 |
| 💼 Job Title         | Data Analyst, BI Analyst, etc. |
| 🔗 Job Link          | Original job posting           |
| 📍 Location          | Job location / remote          |
| 📅 Date Applied      | Application date               |
| 👤 Recruiter         | Recruiter or hiring manager    |
| 🔗 Recruiter Profile | LinkedIn/profile URL           |
| 🤝 Connection        | Connection request status      |
| 📆 Follow-up Date    | Planned follow-up              |
| 🎯 Status            | Current application stage      |
| 🗣️ Interview Date   | Scheduled interview            |
| 🤝 Referral          | Referral status                |
| ⭐ Priority           | High / Medium / Low            |
| 📝 Notes             | Additional information         |

---

### ⏰ Smart Follow-Up Tracking

The application automatically calculates a follow-up date of approximately **5 business days after applying** when a follow-up date isn't manually entered.

It also highlights overdue follow-ups so important recruiter conversations don't get forgotten.

---

### 🔍 Search & Filtering

Quickly find applications using:

* Global search
* Status
* Location
* Priority
* Application source
* Follow-up date

This makes it easy to answer questions such as:

> "Which Data Analyst applications need follow-up today?"

or

> "Which high-priority Bengaluru opportunities are still active?"

---

### 📈 Job Search Analytics

Understand the effectiveness of your job-search strategy with:

* Interview rate
* Offer rate
* Recruiter contact count
* Referral count
* Application funnel
* Status distribution
* Monthly application activity

This turns the job search into a **measurable process** rather than guesswork.

---

### 📤 CSV Export & Import

Export application data to CSV for:

* Excel
* Google Sheets
* Backup
* Further analysis

CSV import is also supported, making it easy to restore or transfer application data.

---

### 🌙 Dark Mode

Switch between light and dark themes for a more comfortable experience.

---

### 💾 Browser Data Persistence

Application data is stored using browser **LocalStorage**, allowing the tracker to retain data between sessions without requiring a backend or database.

> **Tip:** Export your data regularly as CSV because clearing browser site data can remove LocalStorage records.

---

### 📱 Responsive Design

Designed to work across:

* 💻 Desktop
* 💻 Laptop
* 📱 Mobile
* 📲 Tablet

---

## 🖥️ Dashboard

The dashboard provides a quick view of the entire job-search pipeline.

**Core workflow:**

```text
Find Job
   ↓
Save Opportunity
   ↓
Apply
   ↓
Contact Recruiter
   ↓
Send Connection Request
   ↓
Follow Up
   ↓
Interview
   ↓
Offer
```

---

## 🛠️ Tech Stack

### Frontend

* **HTML5** — Semantic page structure
* **CSS3** — Responsive UI, layouts, themes and styling
* **JavaScript (ES6+)** — Application logic and interactivity

### Browser APIs

* **LocalStorage API** — Persistent application data
* **FileReader API** — CSV importing
* **Blob API** — CSV exporting
* **Date API** — Follow-up date calculations

### No Framework Required

This project was intentionally built using **vanilla JavaScript** to demonstrate strong fundamentals in:

* DOM manipulation
* Event handling
* State management
* CRUD operations
* Data filtering
* Data transformation
* Browser storage
* File processing

---

## 🧠 Technical Highlights

This project demonstrates several practical front-end development concepts.

### CRUD Operations

Users can:

```text
Create → Add Application
Read   → View Applications
Update → Edit Application
Delete → Remove Application
```

---

### Dynamic Dashboard

Dashboard metrics are calculated directly from application data.

For example:

```text
Interview Rate =
Number of Interviews / Total Applications × 100
```

This allows the dashboard to update automatically whenever application data changes.

---

### Automatic Business-Day Calculation

Follow-up dates are calculated while accounting for weekends.

Example:

```text
Application Date
       ↓
Add 5 Business Days
       ↓
Follow-Up Date
```

---

### Dynamic Filtering

Application records can be filtered based on multiple conditions simultaneously:

```text
Search
  +
Status
  +
Location
  +
Priority
  +
Source
  +
Follow-up Date
```

---

## 📁 Project Structure

```text
data-analyst-job-search-tracker/
│
├── index.html
│   └── Application structure and dashboard layout
│
├── style.css
│   └── Responsive design and UI styling
│
├── script.js
│   └── Application logic, CRUD, filtering,
│       analytics, LocalStorage and CSV handling
│
└── README.md
    └── Project documentation
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/data-analyst-job-search-tracker.git
```

### 2. Navigate to the project

```bash
cd data-analyst-job-search-tracker
```

### 3. Open the application

Simply open:

```text
index.html
```

in your browser.

### Recommended Development Setup

For development, you can use **VS Code + Live Server**.

No backend or package installation is required.

---

## 🌐 Deploy on GitHub Pages

This project can be deployed directly using GitHub Pages.

### Steps

1. Push the project to GitHub.
2. Open the repository.
3. Go to **Settings**.
4. Select **Pages**.
5. Choose the `main` branch.
6. Select the root folder.
7. Save.

Your application will then be available as a live website.

---

## 📊 Example Use Case

Imagine applying to 30 Data Analyst positions.

Without a tracker:

```text
LinkedIn
Excel
WhatsApp
Email
Notes
Browser bookmarks
```

It becomes difficult to remember:

* Who contacted you
* When you applied
* When to follow up
* Which companies responded
* Which interviews are scheduled

With this application:

```text
                JOB TRACKER
                     │
       ┌─────────────┼─────────────┐
       ↓             ↓             ↓
 Applications    Recruiters    Follow-ups
       │             │             │
       └─────────────┼─────────────┘
                     ↓
                Analytics
                     ↓
              Better Decisions
```

---

## 🎯 Why I Built This

I built this project to solve a real problem I encountered while organizing a Data Analyst job search.

More importantly, I wanted to build something that demonstrates that I can:

> **Identify a practical problem → design a solution → build it → manage data → visualize results → deploy it.**

The project combines my interest in **Data Analytics** with practical **web development**.

---

## 🔮 Future Improvements

Potential future versions could include:

* [ ] Firebase / Supabase database
* [ ] User authentication
* [ ] Cloud data synchronization
* [ ] Multi-device access
* [ ] Automated email reminders
* [ ] Calendar integration
* [ ] Advanced analytics
* [ ] Application success-rate analysis
* [ ] Recruiter response-time analysis
* [ ] Resume version tracking
* [ ] Job description keyword analysis
* [ ] AI-powered job matching
* [ ] Automated follow-up message generation

---

## 📌 Skills Demonstrated

### Data & Analytics

* Data organization
* KPI tracking
* Conversion-rate analysis
* Data filtering
* Data visualization
* Funnel analysis
* Performance measurement

### Development

* HTML5
* CSS3
* JavaScript
* DOM manipulation
* CRUD operations
* LocalStorage
* CSV processing
* Responsive design
* UI/UX implementation

### Problem Solving

* Requirement identification
* Workflow design
* Data modeling
* User-focused design
* Automation of repetitive tasks

---

## Features
- Dashboard with applications, interviews, offers, rejections, saved roles and follow-ups
- Add, edit, view and delete applications
- Automatic follow-up date: **5 business days after Date Applied**
- Search and filters
- Recruiter, connection and referral tracking
- Follow-up list with overdue highlighting
- Analytics and conversion rates
- CSV export for Excel / Google Sheets
- CSV import
- Dark mode
- Responsive/mobile layout
- Browser `localStorage` — no backend required

## I built the complete HTML/CSS/JavaScript Data Analyst Job Search Tracker.

🚀 Included

📊 Professional dashboard

➕ Add applications

✏️ Edit applications

🗑️ Delete applications

🔍 Search

🔽 Filter by status, location, priority and source

📅 Automatic 5-business-day follow-up date

🚨 Overdue follow-up tracking

👤 Recruiter tracking

🤝 Connection & referral tracking

🎯 Interview tracking

📈 Application/interview/offer analytics

📊 Application status chart

🌙 Dark mode

💾 Browser localStorage

📤 CSV export

📥 CSV import

📱 Responsive mobile design

🌐 GitHub Pages ready

📖 README with deployment instructions

## 👨‍💻 About Me

**Manjunath G L**

Aspiring **Data Analyst** with hands-on experience in:

**SQL • Python • Excel • Power BI • Data Visualization • Machine Learning**

I enjoy turning raw data into meaningful insights and building practical solutions that solve real-world problems.

### 🔗 Connect With Me

* **LinkedIn:** https://www.linkedin.com/in/manjunathgl/
* **Portfolio:** https://manjunathglo.github.io/
* **GitHub:** https://github.com/ManjunathGlO

---

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐.

Thank you for visiting!

---

<p align="center">

### 🚀 Built with curiosity, data, and JavaScript.

**Turning problems into practical solutions.**

</p>

