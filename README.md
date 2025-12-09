# Student Management System (C, File Handling)

A **console-based Student Management System (SMS)** developed in **C** using **structures and file handling** as part of my **2nd Semester B.Tech (AI & ML) Programming in C Project**.  
This system digitizes basic student record management such as adding, searching, updating, and deleting student records with **persistent storage**.

---

## Team Members
- Pooja Rajpurohit  
- Rohini S  
- Neysa Mary Pramod  
- Likhita Shree S D  

---

## My Contribution
- Implemented student record structure and grade calculation logic  
- Worked on file handling for data persistence (`students.dat`)  
- Assisted with input validation and search/update functionality  
- Debugging and testing across all modules  

---

## Features
- Add new student records  
- View all students  
- Search student by roll number  
- Update student details  
- Delete student records  
- Automatic **grade calculation**  
- Persistent storage using **binary file handling**

---

## Technology Stack
- **Language:** C  
- **Libraries:** stdio.h, stdlib.h, string.h, ctype.h  
- **Compiler:** GCC  
- **IDE:** Visual Studio Code  

---

## How the System Works
- Student data is stored using a `struct` containing:
  - Roll Number  
  - Name  
  - Marks  
  - Grade  
- Data is stored persistently in a binary file `students.dat`
- Temporary file `temp.dat` is used during update/delete operations for file safety
- Input validation ensures:
  - Alphanumeric roll number
  - Alphabetic names
  - Valid numeric marks

---
## Output

<img width="459" height="848" alt="Output 1" src="https://github.com/user-attachments/assets/dcc83189-c6e0-4b1e-a81f-d3393993d275" />
<img width="440" height="808" alt="Output 2" src="https://github.com/user-attachments/assets/d5ce4fc0-364d-4baa-a23b-0adbe1e69c56" />
<img width="459" height="343" alt="Output 3" src="https://github.com/user-attachments/assets/75214452-212c-4be5-9384-0f3059603862" />
