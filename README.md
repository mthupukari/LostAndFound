# 🔍 Lost and Found System

**LostAndFound** is a web application designed to help users report, search, and manage lost and found items on campus or within an organization. The system enables users to create posts for lost or found items and search the database to reconnect people with their belongings.

## 🌟 Features

- Submit lost or found item reports with descriptions and categories
- Browse and search through listed items
- Match lost items with found items using keyword filtering
- Simple and intuitive interface for users

## 🛠 Tech Stack

- **Backend**: Spring Boot (Java), Spring MVC, Spring Data JPA
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: H2 (in-memory for development)

## 🚀 Getting Started

### Prerequisites
- Java 11+
- Maven

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/mthupukari/LostAndFound.git
   cd LostAndFound
   ```

2. Build and run the Spring Boot app:
   ```bash
   ./mvnw spring-boot:run
   ```

3. Open your browser and go to:
   ```
   http://localhost:8080
   ```

## 📁 Project Structure

```
LostAndFound/
├── src/
│   ├── main/
│   │   ├── java/com/lostandfound/        # Java source files (controllers, services, models)
│   │   └── resources/                    # HTML templates and config
├── pom.xml                               # Maven project file
└── README.md                             # Project description and setup guide
```

## 🧩 Possible Improvements

- Add user authentication and profiles
- Enable image uploads for lost/found items
- Email notifications for matched items
- Pagination and filtering improvements

## 👨‍💻 Author

**Mahit Thupukari**  
[GitHub](https://github.com/mthupukari)

---

Feel free to fork and contribute to make this project more robust!
