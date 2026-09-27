Student Attendance & Performance Tracker
Overview
The Student Attendance & Performance Tracker is a MySQL-based database project developed to manage and analyze student attendance, academic performance, assessments, courses, and extracurricular activities.
The system integrates multiple educational datasets and generates meaningful insights to support academic decision-making. It helps identify high-performing students, monitor attendance trends, detect at-risk students, and evaluate overall academic performance.

## Project Objectives

- Analyze the impact of attendance on student performance.
- Identify high-performing students based on assessment scores.
- Track attendance patterns and student engagement.
- Detect students at academic risk.
- Evaluate course and department performance.
- Support data-driven educational decision-making.
- Implement advanced SQL concepts in a real-world database system.

## Database Features

### Core Entities

- Students
- Parents
- Teachers
- Departments
- Courses
- Classrooms
- Enrollments
- Attendance
- Assessments
- Grades
- Activities
- Student Activities

### Database Concepts Implemented

- Primary Keys
- Foreign Keys
- Constraints
- Normalization
- Indexing
- Views
- Triggers
- Stored Procedures
- Transactions
- Savepoints
- Temporary Tables
- Events
- JSON Data Handling
- User Roles & Permissions

## Research Questions Solved

1. Impact of extracurricular activities on student GPA.
2. Assessment categories with highest failure rates.
3. Relationship between attendance and academic performance.
4. Department performance analysis.
5. Identification of high-risk students.
6. Impact of lateness and absenteeism on marks.
7. Course-wise performance comparison.
8. Assessment weightage analysis.
9. Credit hours vs student performance.
10. Top-performing students ranking.

## Technologies Used

- MySQL
- SQL
- MySQL Workbench
- ER Modeling

## Database Schema

The database contains 12 relational tables:

- department
- teacher
- classroom
- course
- parent
- student
- enrollment
- attendance
- assessment_type
- assessment
- grade
- activity
- student_activity

## Advanced SQL Implementations

### Views
- LowAttendance
- ParentReport
- PerformanceDashboard
- FinalReview

### Triggers
- GradeChangeAudit
- AfterGradeInsert

### Stored Procedures
- GetStudentProfile()

### Transactions
- COMMIT
- ROLLBACK
- SAVEPOINT

### Indexing
- Student Email Index

### User Management
- Teacher Role Permissions
- Access Control using GRANT statements

## Key Business Insights

- Students with higher attendance generally achieve better academic performance.
- Participation in extracurricular activities shows a positive correlation with student grades.
- Students with attendance below 75% require academic intervention.
- Final examinations show higher failure rates compared to other assessments.
- Departments with better resource allocation tend to demonstrate stronger academic outcomes.

## Project Structure

├── SQL Course.sql
├── ER Diagram
├── Research Questions
├── Views
├── Triggers
├── Stored Procedures
├── Transactions
├── README.md

## Learning Outcomes

This project demonstrates practical implementation of:

- Relational Database Design
- Entity Relationship Modeling
- SQL Query Optimization
- Data Analysis using SQL
- Database Security
- Transaction Management
- Automation using Triggers and Events
- Advanced MySQL Features

## Future Enhancements

- Power BI Dashboard Integration
- Student Performance Prediction
- Attendance Alert System
- Parent Notification Module
- Web-Based Student Portal
- Automated Reporting Dashboard

## Author

Developed as a Capstone Project for Managing and Querying Database.

