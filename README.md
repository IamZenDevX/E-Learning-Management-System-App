# E-Learning-Management-System-App

<h2 align="left">Introduction:</h2>


The **E-Learning Management System (ELMS)** is a Designed to manage students, teachers, classes, and user identification, the E-Learning Management System (ELMS) is a strong and scalable tool meant to enable online learning. It offers a flawless forum for teachers, colleges, and students to engage effectively. The technology guarantees simple enrollment, and ordered course delivery.

<h2 align="left">Key Features:</h2>
### 🔑 **User control**

- Safe login and permission ( Administrators, teachers, students).
- Correct management of authorization is guaranteed by role-based access control (RBAC).
- Consumer profile management including flexible specifics.

### 🎓 **Student Module**

- Students can register in classes and track their development by access to study materials and assignments.

### 👨‍🏫 **Instructor Module**

- Create and supervise classes including clearly defined content.
- Track students and provide remarks.

### 🏫 **Class Management**

- Create, modify, then destroy class schedules.
- Assignment teachers to specific courses.

### 

<h2 align="left">Tools Used:</h2>

![Zendevx Technology](https://github.com/user-attachments/assets/36c979fe-929e-44a4-8958-9c15dc466e35)


<h2 align="left">Testing Tools Used:</h2>

![PostMan Github](https://github.com/user-attachments/assets/3381c639-715f-40b9-85d3-08384553ee12)


<h2 align="left">Library:</h2>

- mysql2
- nodemailer
- dotenv
- uuid
- bcryptjs
- path
- body-parser
- cors
- express
- nodemon

## **Database Structure:**

The platform will require a relational database to manage User , student, instructor and  Class  . Below is a proposed database structure with the key tables.

### **Tables**:

---

### a) user

| **Field Name** | **Type** |
| --- | --- |
| user_id | char(PK) |
| username | char |
| email | char |
| password | char |
| type | char |
| firstname | char |
| lastname | char |

### b) student

| **Field Name** | **Type** |
| --- | --- |
| student_id | char(PK) |
| first_name | char |
| last_name | char |
| email | char |
| class | char |

### c) instructor

| **Field Name** | **Type** |
| --- | --- |
| instructor_id | char(PK) |
| first_name | char |
| last_name | char |
| email | char |

### d) Class

| **Field Name** | **Type** |
| --- | --- |
| class_id | char(PK) |
| title | char |
| description | char |
| instructor_id | char |
| img_url | char |
| lesson_number | char |
| lesson_title | char |
| lesson body | char |

<h2 align="left">Use Cases:</h2>

### Planning and Course Organization

- ELMS allows teachers to create, plan, and track courses with exactly specified structures including modules, courses of instruction.
- Every course element including PDFs and assignments is kept in one location for simple access by instructors and students.

### **improved learning**

- Taken all together, chat rooms, discussion forums, and collaboration tools allow student-instructor and peer-to-peer interactions, hence improving engagement.
- Badges, leaderboards, and progress monitoring gamification tools excite student interest and drive.

### **Time & Resource Efficiency**

- ELMS helps teachers to lighten their workload by simplifying administrative tasks including grading, attendance monitoring, and scheduling. Good utilization of resources guarantees classrooms, digital tools, and human resources to increase production.

### * Integration & Scale

- Designed to interact with Learning Management Systems (LMS), Student Information Systems (SIS), and other commercial tools, it might aid companies of all kinds from large institutions to small coaching centers.
- Can integrate with Learning Management Systems (LMS), Student Information Systems (SIS), and other enterprise applications.

<h2 align="left">Development with ZenDevx:</h2>

<a href="https://www.zendevx.com/" target="blank"><img align="center" src="https://github.com/user-attachments/assets/7dd7220f-e83c-4490-9ac2-beab3bcf8c35" alt="ZenDevX" height="auto" width="auto" /></a>



<h2 align="left">🐦 Connect with me:</h2>
         
 
<p align="left">

<a href="https://www.linkedin.com/company/zendevx/" target="blank"><img align="center" src="https://github.com/user-attachments/assets/9a6080ca-4265-43e5-8652-9454651970a9" alt="ZenDevX" height="50" width="50" /></a>
<a href="https://www.youtube.com/@zendevx" target="blank"><img align="center" src="https://github.com/user-attachments/assets/1beefdd6-fa17-49c9-bde7-e8f30f539b96" alt="ZenDevX" height="50" width="50" /></a>
<a href="https://x.com/IamZenDevX" target="blank"><img align="center" src="https://github.com/user-attachments/assets/f1eeb865-3d23-407a-9a2b-d76b4e85c6dd" alt="ZenDevX" height="50" width="50" /></a>
</p>


I hope you like the project. Thanks for reading :)

