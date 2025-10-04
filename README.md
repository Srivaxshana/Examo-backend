# Examo Backend  

The **backend** of Examo – a Digital Exam Platform built using **Spring Boot** and **MySQL**.  
It provides APIs for user authentication, exam creation, question management, and result handling.  

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
### Configure Database
Edit the src/main/resources/application.properties file:

spring.datasource.url=jdbc:mysql://localhost:3306/examo_db
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

### Build and Run Application
```bash
mvn spring-boot:run

