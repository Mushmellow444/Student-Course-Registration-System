# Student Course Registration System

## 📖 Overview
This project is a structured database system that simulates a student course registration platform. It manages relationships between students, courses, and enrollments, demonstrating relational database design and data organization.

---

## 🎯 Features
- Student records storage
- Course catalog management
- Enrollment tracking
- Relational table structure
- Query-ready schema

---

## 🛠 Technologies Used
- SQL
- Relational Database Design
- Data Modeling

---

## 🗂 Database Structure
Main tables include:

- Students
- Courses
- Enrollments

Relationships:
- One student → many enrollments
- One course → many students
- Junction table handles many-to-many relationships

---

## ▶️ How to Run
1. Open SQL environment (MySQL, SQLite, PostgreSQL)
2. Run table creation script
3. Insert sample data
4. Execute queries to test

---

## 💡 Example Query
```sql
SELECT Students.Name, Courses.CourseName
FROM Enrollments
JOIN Students ON Enrollments.StudentID = Students.StudentID
JOIN Courses ON Enrollments.CourseID = Courses.CourseID;
```

---

## 📚 Concepts Demonstrated
- Many-to-many relationships
- Primary & foreign keys
- Data normalization
- Structured queries

---

## 🚀 Future Improvements
- Add grades table
- Add instructor table
- Add login system
- Build UI frontend

---

## 👨‍💻 Author
Created by **Krin** as part of a database systems learning project.
