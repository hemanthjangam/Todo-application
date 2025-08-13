# 📝 Todo Application

A simple **Java-based To-Do List Application** supporting task creation, update, completion, and deletion, built as a web application using **Spring Boot**, **Thymeleaf** (server-side template engine), and **Bootstrap CSS** for modern, responsive UI.

***

## 🚀 Features
- Add new tasks
- Mark tasks as completed
- Delete tasks
- View all tasks in a list
- Responsive design powered by Bootstrap
- Persistent storage (H2/MySQL)

***

## 🛠 Tech Stack
- **Language:** Java
- **Frameworks:** Spring Boot, Thymeleaf
- **Templating:** Thymeleaf server-side
- **Frontend:** HTML, Bootstrap CSS, minimal JS
- **Backend:** Spring Boot (REST Controllers/Services)
- **Build Tool:** Maven
- **Database:** H2/MySQL
- **Version Control:** Git & GitHub

***

## 📂 Project Structure
```
Todo-application/
│
├── src/
│   ├── main/java/         # Java source code (Controllers, Services, Repos)
│   ├── main/resources/
│       ├── templates/     # Thymeleaf HTML templates
│       └── static/        # Static files (Bootstrap CSS, images)
│   └── test/java/         # Unit tests
│
├── pom.xml
├── .gitignore
└── README.md
```

***

## 🔧 Installation & Setup

### Prerequisites
- Java 17+
- Maven
- MySQL (if not using H2 in-memory)

### How to Run
1. Clone the repo
   ```
   git clone https://github.com/hemanthjangam/Todo-application.git
   cd Todo-application
   ```
2. Build and run
   ```
   mvn clean install
   mvn spring-boot:run
   ```
   The app will be live at:
   ```
   http://localhost:8080
   ```

***

## 🖼 Sample Screenshots
![Screenshot of Todo Application](./Screenshot-2025-08-13-at-11-49-55.png)


***

## 🤝 Contributing
Pull requests are welcome. Major changes? Please discuss via issues first.

***

## 📜 License
MIT License.

***

## 👨💻 Author
**Hemanth Jangam**  
GitHub: [@hemanthjangam](https://github.com/hemanthjangam)
