# HelloWorld Spring Boot Application

![Java](https://img.shields.io/badge/Java-24-blue?logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.5-brightgreen?logo=springboot)
![Maven](https://img.shields.io/badge/Maven-3.9+-orange?logo=apachemaven)
![Build](https://img.shields.io/badge/build-passing-success)

A simple **Spring Boot 3.5.5** application built with **Java 24** and **Maven**.  
This project demonstrates a REST endpoint `/hello` that returns a greeting message for the HelloWorld project.

---

## 🚀 Tech Stack
- Java 24  
- Spring Boot 3.5.5  
- Maven 3.9.x  

---

## 📂 Project Structure
```
HelloWorld
 ├── src
 │   ├── main
 │   │   ├── java/com/example/HelloWorld
 │   │   │   ├── HelloWorldApplication.java       # Main Spring Boot app
 │   │   │   └── HelloController.java            # REST endpoint
 │   │   └── resources/application.properties
 │   └── test/java/com/example/HelloWorld
 │
 ├── pom.xml
 └── README.md
```

---

## ▶️ Run Locally

### 1. Clone the project
```bash
git clone https://github.com/your-username/HelloWorld.git
cd HelloWorld
```

### 2. Build and run with Maven
```bash
mvn spring-boot:run
```

Or build a JAR:
```bash
mvn clean package
java -jar target/HelloWorld-0.0.1-SNAPSHOT.jar
```

---

## 🌐 REST API

### **GET /hello**
Returns a greeting message.

#### Example Requests
```http
GET http://localhost:8080/hello
```
Response:
```
Hello, World!
```

```http
GET http://localhost:8080/hello?name=Ganesh
```
Response:
```
Hello, Ganesh!
```

---

## 🛠️ Requirements
- Java 24 (or Java 21 LTS)
- Maven 3.6.3+  

---

## 📜 License
This project is licensed under the MIT License.

