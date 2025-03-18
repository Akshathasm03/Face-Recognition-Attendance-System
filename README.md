# Face-Recognition-Attendance-System

![Project Screenshot](https://github.com/Khushikuma4i/Face-Recognition-Attendance-System/blob/main/project1.png?raw=true)

### **Face Recognition Attendance System**  

#### **Project Overview**  
The **Face Recognition Attendance System** is an automated solution that marks attendance using facial recognition technology. It ensures that only registered individuals can be recognized, enhancing security and efficiency in attendance tracking. The system leverages **Tkinter for the GUI**, **OpenCV for face detection and recognition**, **NumPy & Pandas for data processing**, and **MySQL Workbench for database management**.  

---

### **Key Features & Workflow**  

#### **1. Graphical User Interface (Tkinter - Frontend)**  
- A **user-friendly interface** created using Tkinter.  
- Provides options to **register new users**, **mark attendance**, and **view attendance logs**.  
- Displays a **real-time camera feed** to capture and recognize faces.  

#### **2. Face Detection & Recognition (OpenCV & Haarcascade)**  
- Uses the **Haarcascade algorithm** to detect human faces in real-time.  
- Captures facial features and stores them in the database.  
- Recognizes faces by comparing them with the registered dataset.  

#### **3. Data Processing & Management (NumPy & Pandas)**  
- **NumPy** processes image arrays efficiently for face detection.  
- **Pandas** stores and manages attendance records in tabular format.  
- Enables easy analysis and retrieval of attendance data.  

#### **4. Secure Database (MySQL Workbench)**  
- Stores user details such as **Name, ID, and Face Embeddings**.  
- Maintains an **attendance log** with timestamps.  
- Ensures **data integrity** and prevents unauthorized access.  

#### **5. Automated Attendance Marking**  
- When a **registered face** is detected, attendance is automatically recorded.  
- If an **unregistered face** is detected, it shows an **"Unknown User"** error.  
- Prevents **duplicate entries** and ensures each person is marked once per session.  

#### **6. Security & Error Handling**  
- Only **pre-registered users** can mark attendance.  
- Handles **error cases**, such as **poor lighting or incorrect angles**.  
- Protects against **spoofing** by requiring **live detection**.  

---

### **Project Benefits**  
✅ Eliminates manual attendance marking.  
✅ Reduces fraud by ensuring only registered users are recognized.  
✅ Increases efficiency in schools, offices, and organizations.  
✅ Provides a secure and automated attendance solution.  

Would you like a **detailed project report** or **code implementation** next? 🚀
