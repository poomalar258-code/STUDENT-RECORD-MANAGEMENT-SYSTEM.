# 🎓 Student Record Management System

A simple **Student Record Management System** developed in **C** using **Singly Linked List** and **File Handling**. This project provides a menu-driven interface to efficiently manage student records. It demonstrates data structures, dynamic memory allocation, modular programming, and file operations in C.

---

## 📌 Features

- ➕ Add Student Record
- 📋 Display All Student Records
- 🔍 Search Student by Roll Number
- ✏️ Modify Student Details
- ❌ Delete Student Record
- 💾 Save Records to File
- 📂 Load Records from File
- 📊 Sort Student Records

---

## 🛠️ Technologies & Tools Used

- C Programming
- GCC Compiler
- Linux
- Makefile
- Data Structures (Singly Linked List)
- File Handling

---

## 📚 Concepts Used

- Singly Linked List
- Dynamic Memory Allocation (`malloc()`, `free()`)
- Structures
- Functions
- Header Files
- Modular Programming
- File Handling (`fopen()`, `fclose()`, `fprintf()`, `fscanf()`)

---

## 📁 Project Structure

```text
STUDENT-RECORD-MANAGEMENT-SYSTEM/
├── main.c
├── student.h
├── student_add.c
├── student_del.c
├── student_show.c
├── student_mod.c
├── student_save.c
├── student_load.c
├── student_sort.c
├── Makefile
└── README.md
```

---

## 📸 Sample Output

### Main Menu

```text
=========================================
      STUDENT RECORD MANAGEMENT SYSTEM
=========================================

1. Add Student
2. Display Students
3. Search Student
4. Modify Student
5. Delete Student
6. Sort Students
7. Save Records
8. Load Records
9. Exit

Enter your choice: 1
```

### ➕ Add Student

```text
Enter Roll No : 101
Enter Name    : Poomalar
Enter Age     : 21
Enter Marks   : 92.5

Student record added successfully.
```

### 📋 Display Students

```text
--------------------------------------------------
Roll No     Name          Age       Marks
--------------------------------------------------
101         Poomalar      21        92.5
102         Arun          20        88.0
103         Priya         21        95.0
--------------------------------------------------
```

### 🔍 Search Student

```text
Enter Roll No: 102

Student Found

Roll No : 102
Name    : Arun
Age     : 20
Marks   : 88.0
```

### ✏️ Modify Student

```text
Enter Roll No to Modify: 102

Current Marks : 88.0
Enter New Marks: 91.5

Student record updated successfully.
```

### ❌ Delete Student

```text
Enter Roll No to Delete: 101

Student record deleted successfully.
```

### 📊 Sort Students

```text
Sorting student records...

Records sorted successfully.
```

### 💾 Save Records

```text
Saving records to file...

Records saved successfully.
```

### 📂 Load Records

```text
Loading records from file...

Records loaded successfully.
```

---

## ⚙️ Compilation

### Using Makefile

```bash
make
```

### Or Compile Manually

```bash
gcc *.c -o student
```

---

## ▶️ Run the Program

```bash
./student
```

---

## 👩‍💻 Author

Poomalar R

- GitHub: https://github.com/poomalar258-code

---

## 📄 License

This project is licensed for **educational and learning purposes only**. You are free to use, modify, and share this project for academic or personal learning with proper credit to the author.

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub!
