# Academic Assessment & Coursework Portal 🎓
> Engineering College Mid-I & Mid-II Assignment & Evaluation System  
> Aligned with JNTUH R25 & R22 Curriculum Guidelines

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Status: Production Ready](https://img.shields.io/badge/Status-Active-emerald.svg)
![Curriculum: JNTUH R25 & R22](https://img.shields.io/badge/Regulation-R25%20%7C%20R22-indigo.svg)

---

## 📌 Overview
The **Academic Coursework Portal** is a modern, responsive web application engineered for undergraduate engineering departments. It streamlines assignment distribution, format compliance validation, tamper-evident submission proof receipts, and dual-pane split-screen rubric grading for instructors.

---

## ✨ Key Features

### 👨‍🎓 1. Student Portal
* **Year & Semester-wise Subject Navigation:**
  * **II B.Tech I Semester (Regulation R25):** Java Programming, DBMS, Software Engineering, Computer Organization & Architecture, Discrete Mathematics, Innovation & Entrepreneurship, Environmental Science.
  * **III B.Tech I Semester (Regulation R22):** DAA, Computer Networks, DevOps, Principles of Programming Languages, Distributed Databases.
  * **IV B.Tech I Semester (Regulation R22):** Cryptography & Network Security, Compiler Design, Cloud Computing, Software Process & Project Management, Natural Language Processing.
* **Branch Switcher:** Fast toggling between **CSE** and **IT** department curriculums.
* **Drag-and-Drop Dropzone:** Real-time extension validation (`PDF`, `PNG`, `ZIP`), size limits, and animated upload progress bars.
* **Local Draft Persistence:** Save in-progress coursework locally to resume anytime.
* **Cryptographic Submission Receipts:** Downloadable `.txt` verification receipt with unique Receipt ID, timestamp, and SHA-256 checksum.
* **Marks & Rubric Feedback Modal:** Transparent evaluation breakdown with letter grades and qualitative faculty remarks.

---

### 👩‍🏫 2. Faculty / Evaluator Portal
* **Sequential Roll Number Ledger:** Student submissions ordered sequentially for fast attendance and grading verification.
* **Instant Roll Search:** Filter immediately by typing roll numbers.
* **Single-Click "Copy Missing Roll Numbers":** Solves the real-world faculty hassle of manually typing unsubmitted roll numbers for classroom broadcast announcements.
* **Dual-Pane Split-Screen Grading (65% / 35%):**
  * **Left Pane (Document Viewer):** Zoomable sheet preview (50% - 200%) showing code snippets and answer sheets.
  * **Right Pane (Rubric Scoring):** Theory, Code correctness, and Presentation criteria with live tallying and instant syncing to the student portal.

---

## 🎨 Design System
* 🟢 **Green (Emerald):** Submitted / On-Time (`bg-emerald-100 text-emerald-800`)
* 🔴 **Red (Rose):** Overdue / Missing (`bg-rose-100 text-rose-800`)
* 🟡 **Amber (Amber):** Due Soon / Action Required (`bg-amber-100 text-amber-800`)
* 🔵 **Blue (Sky):** Graded / Evaluated (`bg-sky-100 text-sky-800`)

---

## 🚀 How to Run Locally

### Option 1: Direct Browser Access
Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).

### Option 2: Local HTTP Server (Python)
```bash
python -m http.server 8000
```
Then navigate to [http://localhost:8000](http://localhost:8000).

---

## 📄 License
This project is open source and available under the [MIT License](LICENSE).
