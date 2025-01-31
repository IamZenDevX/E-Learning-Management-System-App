# E-Learning-Management-System-App

# **Introduction:**

The **E-Learning Management System (ELMS)** is a Designed to manage students, teachers, classes, and user identification, the E-Learning Management System (ELMS) is a strong and scalable tool meant to enable online learning. It offers a flawless forum for teachers, colleges, and students to engage effectively. The technology guarantees simple enrollment, and ordered course delivery.

# **Key Features:**

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

# **Tools Used:**

![Untitled design (19).png](attachment:8e034e87-f6c5-4925-99b9-05126258ce45:Untitled_design_(19).png)

## Testing Tools Used:

![PostMan Github.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3f690236-03bd-47db-ac0f-28b089483950/0d6d1c89-f506-4ac0-8d04-9f5ff3d35244/PostMan_Github.png)

### **Library :**

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

# Use Cases:

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

# **Development with ZenDevx:**

# **🐦 Contact With Me:**

           

![download (1).png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3f690236-03bd-47db-ac0f-28b089483950/90e12aba-9757-4c54-ab2d-9357fddb8a83/download_(1).png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3f690236-03bd-47db-ac0f-28b089483950/23afd96a-1373-48f9-b3ea-d10ed0b03463/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3f690236-03bd-47db-ac0f-28b089483950/decfc413-8d87-4ea1-9982-958d8f7dc958/image.png)

I hope you like the project. Thanks for reading :)
