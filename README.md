# **📌 DormEase — Hostel Management System**

DormEase is a GUI-based Java application built to streamline and automate hostel operations. It offers dedicated dashboards for students, wardens, and mess administrators, enabling efficient management of daily activities. The system focuses on reducing food wastage through a meal-confirmation mechanism where students confirm meal attendance, and fines are issued for unconfirmed absences. It also supports student enrollment, attendance tracking, room allocation, and provides intuitive panels for both students and administrators to simplify hostel management.

---

## **🚀 Tech Stack**

* Java
* Spring Boot
* MySQL
* JavaServerPages (JSP)
* HTML
* CSS
---

## **✨ Key Features**

### 🧑‍🎓 **1. Student Enrollment & Information Management**

* Students can enroll/register into the hostel system
* View and update their personal details
* Check fee status and hostel information
* Weekend meal confirmation (Yes/No)

### 🧑‍🏫 **2. Warden Module**

* Manage hostel attendance
* Create and publish notices for students
* Oversee student data and daily hostel operations
* Simple GUI screens for quick admin actions

### 🍽️ **3. Mess Administration**

* Track student meal attendance
* Manage daily/weekly meal planning
* Built-in *Weekend Meal Confirmation Form*
* Helps reduce food wastage through pre-attendance tracking

### ⚠️ **4. Meal Confirmation & Fine System**

* Students confirm their weekend meal attendance
* Non-attendance (without confirmation) results in fine
* Ensures accountability and optimized mess resource usage

---

## **📂 Project Structure**

```
DormEase/
 ├── src/main/java/       # All Java source files
 ├── target/              # Build artifacts
 ├── pom.xml              # Maven config
 └── README.md
```

---

## **🖥️ GUI Preview**
<img src="GUI images/hms1.png" width="600">
<img src="GUI images/hms2.png" width="600">
<img src="GUI images/hms3.png" width="600">
<img src="GUI images/hms4.png" width="600">
<img src="GUI images/hms5.png" width="600">
<img src="GUI images/hms6.png" width="600">
<img src="GUI images/hms7.png" width="600">
<img src="GUI images/hms8.png" width="600">
<img src="GUI images/hms9.png" width="600">
<img src="GUI images/hms10.png" width="600">
<img src="GUI images/hms11.png" width="600">
<img src="GUI images/hms12.png" width="600">


## **🛠️ Installation & Setup**

### 1. Clone the repository

```bash
git clone https://github.com/NilayPatil12/DormEase---Hostel-Management-System.git
```

### 2. Open project

Import into **IntelliJ IDEA** / **Eclipse** as a **Maven Project**

### 3. Build project

Your IDE will automatically download Maven dependencies.

### 4. Run the application

Inside your IDE, run the **main class** from the `src/main/java` directory.

---

## ✨ Features

### 🧑‍🎓 Student Module
- Student enrollment and profile management  
- View room allocation and hostel details  
- Weekend meal confirmation to reduce food wastage  
- View fines, fee status, and hostel notices  
- Simple and responsive student dashboard  

### 🧑‍🏫 Warden Module
- Mark and monitor daily student attendance  
- Manage room allocations and student records  
- Create and publish hostel notices  
- Access a dedicated admin dashboard for quick actions  

### 🍽️ Mess Administration
- Track daily and weekend meal attendance  
- Auto-generate fines for unconfirmed weekend meals  
- Reduce food wastage through pre-meal confirmation  
- View mess-related statistics and attendance summaries  

### ⚙️ System Utilities
- Clean GUI built using Java Swing  
- Modular, maintainable object-oriented structure  
- Easy to extend with additional admin/student tools  
- Ready for future integration with a database or web interface  

---

## **🧩 Architectural Notes**

* Follows **Modular OOP Design**
* Separate classes for Student, Warden, MessAdmin, etc.
* GUI forms mapped to feature-based modules
* Easy to extend (add database, middleware layer, etc.)

---

## **🤝 Contributing**

Pull requests and suggestions are welcome!

