# 🌱 Spring Boot User Management Demo

> A minimal yet powerful Spring Boot project to get you started with **annotations**, **dependency injection**, **layered architecture**, and **unit testing** — all using an in-memory setup! Perfect for Spring Boot beginners. 🚀

---

## 🔧 Tech Stack

> Built with modern tools and best practices:

- 💻 **Java 17**
- 🌐 **Spring Boot**
- ✅ **JUnit 5**
- 🛠️ **Gradle**

---

## 📂 Project Structure

```bash
spring-boot-user-demo/
├── build.gradle
├── README.md
└── src/
    ├── main/java/com/example/demo/
    │   ├── DemoApplication.java          # Main Spring Boot entry point
    │   ├── model/User.java               # User model
    │   ├── repo/FakeRepoInterface.java   # Interface for repository
    │   ├── repo/FakeRepo.java            # In-memory implementation
    │   ├── service/UserService.java      # Service interface
    │   └── service/UserServiceImpl.java  # Service implementation
    └── test/java/com/example/demo/
        └── service/UserServiceTests.java # Unit tests
