# Campus Course & Records Manager (CCRM)

## 1. Problem Statement

Managing student academic records such as student details, courses, enrollments, grades, and transcripts can become difficult when information is maintained manually or across multiple files.

The **Campus Course & Records Manager (CCRM)** is designed to provide a centralized Java-based system for managing these academic records. The system allows users to maintain student and course information, manage enrollments and grades, generate transcripts, and perform data import, export, and backup operations.

The project also demonstrates the practical application of important **Java programming concepts**, including Object-Oriented Programming, collections, exception handling, file handling, Java Streams, Date/Time API, and design patterns.

## 2. Scope of the Project

The scope of CCRM includes the management and processing of academic information within a campus environment.

The system covers:

* Student record management.
* Course and instructor management.
* Student enrollment and unenrollment.
* Grade recording and academic result processing.
* Transcript generation.
* CSV-based data import and export.
* File and data backup operations.
* Academic reports and record processing.
* Input validation and exception handling.
* Command-line based interaction.

The current project is focused on a **Java SE console application with file-based storage**. It does not currently aim to provide a web-based interface, mobile application, or centralized database system.

## 3. Target Users

The primary target users of the CCRM system are:

### 3.1 Academic Administrators

Administrators can manage student and course records, handle enrollments, maintain grades, perform data operations, and generate reports.

### 3.2 Faculty / Instructors

Instructors can use the system's academic record functionality to work with course-related information and student grades.

### 3.3 Students

Students can be considered end users of academic information such as enrollment details, grades, and transcripts.

### 3.4 Project Developers / Students

The system is also useful as an educational project for students learning Java programming, OOP, file handling, collections, exception handling, Streams, and software design patterns.

## 4. High-Level Features

### Student Management

* Add and maintain student records.
* Search and view student information.
* Update student details.
* Manage student status.

### Course Management

* Create and maintain course records.
* Store course code, title, credits, and instructor information.
* Search and view available courses.

### Enrollment Management

* Enroll students in courses.
* Remove students from courses.
* Prevent invalid or duplicate enrollment operations.

### Grade Management

* Record student grades.
* Process academic results.
* Maintain grade information for enrolled courses.

### Transcript Generation

* Generate a student's academic transcript.
* Display course, enrollment, and grade information.
* Support academic result processing.

### Data Import & Export

* Import academic records from CSV files.
* Export records to CSV files.
* Support file-based data management.

### Backup & Reports

* Perform backup operations for stored data.
* Generate useful academic reports.
* Provide file-processing utilities.

### Validation & Exception Handling

* Validate user input and academic operations.
* Handle invalid operations using appropriate exceptions.
* Use custom exceptions for domain-specific errors.

### Java-Based Architecture

* Object-Oriented design.
* Service-based separation of business logic.
* Java NIO.2 for file operations.
* Collections and Stream API for data processing.
* Singleton and Builder design patterns where appropriate.
