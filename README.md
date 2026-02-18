# Mini Learning Management System (LMS)

A simple **console-based** Learning Management System built in Python with separate roles for **Teachers** and **Students**.  
Perfect as a beginner-to-intermediate Python + OOP learning project.

## Features

### 🧑‍🏫 Teacher Capabilities
- Add new courses (title + number of lessons)
- List all courses with enrollment count
- View students enrolled in any course
- Check detailed progress of any student

### 👩‍🎓 Student Capabilities
- Browse all available courses
- Enroll in a course
- Update number of completed lessons
- View personal progress (completed/total lessons + percentage)

### General
- Role-based login (Teacher / Student)
- Students auto-register on first login (no admin approval needed)
- Clean, colorful console menu
- In-memory data storage (resets on exit – great for demo/learning)

## Default Teacher Credentials

| Username  | Password |
|-----------|----------|
| teacher1  | 1234     |
| admin     | admin    |

Students: Just enter **any username** + **any password** — a new account is created automatically.

## How to Run

### Requirements
- Python 3.6+ (no external packages needed!)

### Method 1: Terminal / Command Line (Quickest)

1. Save the program code as **`lms.py`**
2. Open terminal / cmd / PowerShell
3. Navigate to the folder containing `lms.py`:

   ```bash
   cd path/to/your/folder
