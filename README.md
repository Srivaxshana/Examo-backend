# Examo Backend  

**Examo Backend** is the server-side of **Examo – a Digital Exam Platform**, developed as my **4th-semester project for the Web Application Development module**.  
It provides secure and scalable RESTful APIs for authentication, exam management, question handling, and result processing.   

---

## 🚀 Features
- 🔐 Secure authentication (JWT or session-based)  
- 🧑‍🏫 Admin APIs to manage exams, questions, and results  
- 🧑‍🎓 Student APIs for exam participation  
- 🗄️ MySQL integration for data storage  
- ⚙️ RESTful API design  

---

## 🛠️ Tech Stack
- **Backend Framework:** Spring Boot  
- **Database:** MySQL  
- **Build Tool:** Maven  
- **Language:** Java  
- **API Testing:** Postman  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Srivaxshana/Examo-backend.git
cd examo-backend

```
### 2️⃣ Configure Database
Edit the src/main/resources/application.properties file:
```bash
spring.datasource.url=jdbc:mysql://localhost:3306/examo_db
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```
### 3️⃣ Build and Run Application
```bash
mvn spring-boot:run

