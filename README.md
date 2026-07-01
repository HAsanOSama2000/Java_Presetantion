
# Universal Planner 📅
Contributors are Markus, Hasan and Maximilian.
This project serves as a mock personal planner software, specifically built to demonstrate foundational features and concepts covered in our object-oriented programming lectures. 

> **🎓 Academic Context:**  
> This collaborative project was developed for the course *"Objektorientierte Programmierung II: Grundlagen der objektorientierten Programmierung mit Java"*.  
> **Date of Presentation:** August 04, 2023  
> **Achieved Grade:** 1.3 (Excellent)  
> **Contributors:** Markus, Hasan, and Maximilian

---

## 🌟 Core Modules

The planner is divided into three main components:
* **Shopping List:** Manage your groceries and items, including quantities, descriptions, and categories[cite: 9, 16]. Data is persistently stored using JSON[cite: 16].
* **Calendar:** Track important dates and manage your schedule.
* **TODO:** Keep an overview of pending tasks and daily goals.

## 🛠️ Tech Stack

* **Language:** Java 20[cite: 8]
* **Build Tool:** Maven[cite: 8]
* **Dependencies:** `json-simple` (v1.1.1) for parsing and generating JSON data[cite: 8].

## 🚀 Environment Setup & Contribution Workflow

### 1. Clone the Repository
Clone the project to your local machine:
```bash
git clone [https://github.com/MaximilianVollmer/Java_Presetantion.git](https://github.com/MaximilianVollmer/Java_Presetantion.git)
\
If not already done set your git username and email:
```
git config --local user.name <Username>
git config --local user.email <Email>
```
Replace \<Username> and \<Email> respectively.\
If you like you can type to automatically set the upstream branch
```
git config --global push.autoSetupRemote true
```
\
\
Create a new branch from develop
```
git checkout -b <branch-name> develop
```
You can now work from the new branch
\
\
To get changes onto the remote repository
```
git add .
// . means "add all new files", git add README.md targets only the README file
git commit -m "Some Commit Message"
// Make commit, it's like saving the changes to git
git push 
or if error >> git push -u origin <remotebranch-name>
// pushes the changes into the remote repository
```
