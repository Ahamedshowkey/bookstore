# 📚 Web-Based Book Store  


## 🚀 Project Overview  
The **Web-Based Book Store** is a full-featured e-commerce platform designed to modernize traditional book purchasing. It provides a seamless digital experience for browsing, searching, and ordering books, with dedicated dashboards for customers, staff, and administrators.

---

## ✨ Features  

### 👤 User Features  
- Secure user registration & login  
- Browse & search books by title, author, genre, ISBN  
- Shopping cart with quantity management  
- Secure checkout & order placement  
- Order history & real-time tracking  

### 🛠️ Admin Features  
- Manage book inventory (CRUD operations)  
- View & update customer orders  
- User account management  
- Moderate book reviews  

### ⚙️ System Features  
- Role-based access control (Customer, Staff, Admin)  
- Secure authentication with JWT & Spring Security  
- Responsive UI using Thymeleaf  
- MySQL database with JPA/Hibernate  
- Payment-ready architecture  

---

## 🛠️ Tech Stack  

| Category            | Technology/Tool                     |
|---------------------|-------------------------------------|
| Backend Framework   | Spring Boot 3.3.2                  |
| Language            | Java 17                            |
| Database            | Microsoft SQL Server               |
| ORM                 | Spring Data JPA / Hibernate        |
| Security            | Spring Security, JWT               |
| Frontend Templates  | Thymeleaf                          |
| Build Tool          | Apache Maven                       |
| IDE                 | IntelliJ IDEA                      |
| Version Control     | Git                                |

---

## 📁 Project Structure  
```
src/
├── main/
│   ├── java/com/bookstore/
│   │   ├── controller/     # REST & MVC controllers
│   │   ├── model/          # JPA entities
│   │   ├── repository/     # Spring Data repositories
│   │   ├── service/        # Business logic
│   │   ├── security/       # Security config & filters
│   │   └── config/         # Application configuration
│   ├── resources/
│   │   ├── static/         # CSS, JS, images
│   │   ├── templates/      # Thymeleaf HTML pages
│   │   └── application.properties
│   └── ...
├── test/                   # Unit & integration tests
└── pom.xml                # Maven dependencies
```

---

## 🚀 Getting Started  

### Prerequisites  
- Java 17 or higher  
- Maven 3.6+  
- Microsoft SQL Server  
- Git  

### Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/web-based-bookstore.git
   cd web-based-bookstore
   ```

2. Configure database connection in `src/main/resources/application.properties`:  
   ```properties
   spring.datasource.url=jdbc:sqlserver://localhost:1433;databaseName=bookstore_db
   spring.datasource.username=your_username
   spring.datasource.password=your_password
   ```

3. Build and run the application:  
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

4. Open your browser and navigate to:  
   ```
   http://localhost:8080
   ```

---

## 📌 Key Diagrams  

### Use Case Diagram  
![Use Case Diagram](docs/usecase-diagram.png)  

### EER Diagram  
![EER Diagram](docs/eer-diagram.png)  

### UI Screenshots  
| Home Page | Login | Book Dashboard |
|-----------|-------|----------------|
| ![Home](/home.png) | ![Login](/login.png) | ![Books](/books.png) |

| Cart | Orders | Admin Panel |
|------|--------|-------------|
| ![Cart](docs/cart.png) | ![Orders](docs/orders.png) | ![Admin](docs/admin.png) |

---

## 📅 Agile Development  

The project followed an **Agile approach** with 4 sprints:  

| Sprint   | Focus Areas                                      |
|----------|--------------------------------------------------|
| Sprint 1 | User authentication, registration, security      |
| Sprint 2 | Book browsing, search, cart management           |
| Sprint 3 | Order placement, inventory management            |
| Sprint 4 | Admin features, order tracking, reviews          |

Detailed user stories and sprint logs are available in the [project documentation](docs/).

---

## ✅ Achievements  
- ✅ Fully functional e-commerce platform  
- ✅ Secure authentication & role-based access  
- ✅ Complete CRUD operations for books & orders  
- ✅ Responsive & user-friendly UI  
- ✅ Scalable Spring Boot architecture  
- ✅ Payment-ready integration points  

---

## 🧠 Challenges Faced  
- Implementing multi-role authentication  
- Maintaining data consistency across dashboards  
- Designing responsive layouts  
- Ensuring secure session management  

---

## 🔮 Future Enhancements  
- Multi-vendor support for publishers/booksellers  
- E-book integration with reading platform  
- Subscription service & loyalty programs  
- International shipping & multi-currency support  
- Mobile app development  

---

## 👥 Team  
- **Sowkey A.A** –

---

## 📚 References  
1. [Spring Boot 3.3.2 Documentation](https://docs.spring.io/spring-boot/docs/3.3.2/reference/html/)  
2. [Java SE 17 API](https://docs.oracle.com/en/java/javase/17/docs/api/)  
3. [Spring Data JPA Docs](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/)  
4. [Microsoft JDBC Driver for SQL Server](https://learn.microsoft.com/en-us/sql/connect/jdbc/microsoft-jdbc-driver-for-sql-server)  

---

## 📄 License  
This project is for academic purposes as part of the **SE2030 - Software Engineering** course at Sri Lanka Institute of Information Technology.
