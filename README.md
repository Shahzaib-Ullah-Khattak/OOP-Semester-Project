# Interactive Exam Portal System

##  Group Members

| Name | Student ID | Section |
|------|-----------|---------|
| Shahzaib Ullah Khattak | 023-25-0182 | C |
| Muhammad Safdar Khan | 023-25-0169 | C |

---

##  Project Description

The **Interactive Exam Portal System** is a comprehensive Java-based application that enables educational institutions to conduct online examinations efficiently. This system provides separate portals for teachers and students, where teachers can create and manage quizzes with a question bank, while students can attempt quizzes and receive instant feedback on their performance.

### Problem Statement
Traditional exam systems are manual, time-consuming, and prone to errors. This system automates the quiz creation, distribution, and result tracking process, making it easier for educators to conduct assessments and for students to practice.

### Target Users
- **Teachers/Instructors** - Create quizzes, manage questions, and view student results
- **Students** - Attempt quizzes and track their performance

---

##  Core Modules & Architecture

### **1. Database Layer**
- MySQL database management with JDBC connectivity
- Connection pooling and error handling
- Tables: `teachers`, `students`, `question_bank`, `quizzes`, `questions`, `results`

### **2. Authentication Module**
- User login and registration system
- Role-based access control (Teacher/Student)
- Credential validation and session management

### **3. Teacher Portal**
- **Question Bank Management:** Add, bulk import, delete questions
- **Quiz Creation:** Create quizzes from question bank with codes and passwords
- **Quiz Management:** Edit quiz details, add/remove questions dynamically
- **Results Analytics:** View student performance by quiz

### **4. Student Portal**
- **Quiz Attempt:** Search and attempt quizzes with code and password
- **MCQ Interface:** Interactive real-time question display
- **Instant Results:** Auto-graded with detailed feedback
- **Performance History:** Track all quiz attempts

### **5. GUI Component** (Swing/AWT)
- Card-based navigation between panels
- Responsive and user-friendly interface
- Custom styling with consistent color scheme

---

##  OOP Features Implemented

**Encapsulation** - Private fields with controlled access via getters/setters  
**Inheritance** - Base User class with Teacher/Student specialization  
**Polymorphism** - Method overriding for different user roles  
**Abstraction** - Question class abstracts question data structure  
**Collections** -Arrays

**Exception Handling** - Comprehensive try-catch with user feedback  
**Database Operations** - JDBC with PreparedStatements for SQL injection prevention  
**File I/O** - Bulk question import from text

---

## Disclaimer
**SQL:** 
    this code donot run until you created a local database with the tables give in sql file 
beacuse it is build for the local host and include my sql password and local host changing the
password and the the host name to your instead of me then ot will satrt working and retrive the
data from the daatbase otherwose it doesnot.

---

## Demo Video
**Link:**
fasdjfasfgjai

## How to run:
** Compilation:**

###**Enter to the folder oop-semester-project and open the cmd their and compile the code with below **
        javac -cp ".;mysql-connector-j-9.6.0.jar" src\ExamPortal.java
        
###**Run:** 
    java -cp ".;mysql-connector-j-9.6.0.jar;src" ExamPortal
    
    ---
    


