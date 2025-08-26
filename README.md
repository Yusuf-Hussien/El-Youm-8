# El-Youm 8 🎓

**El-Youm 8** is a production-ready system that helps search Egypt's Thanaweya Amma (الثانوية العامة) results by **name** or **seat number**.  
It combines multiple components into one solution:

- 📡 **RESTful API**
- 🌐 **Web Application** (desktop & mobile responsive)
- 🤖 **Telegram Bot**
- 🐳 **Dockerized Deployment**

The system is optimized for large datasets, typo-tolerant searches, and seamless integration in different environments.

---

## 🚀 Features

- 🔍 **Typo-Tolerant Search**: Flexible name matching (handles variations like "ه/ة" or "ا/أ").
- 📊 **Calculated Fields**: Rank, duplicated rank, and percentage are automatically computed.
- ⚡ **Optimized Querying**: Uses indexes and composite indexes for fast lookups.
- 🌐 **RESTful API**: Search functionality for programmatic access.
- 🤖 **Telegram Bot Integration**: Access search directly from Telegram.
- 🖥️ **Web Interface**: MVC interface with Thymeleaf.
- 📱 **Mobile-Responsive and Desktop-Responsive Design**: Optimized for Desktop & mobile users.
- 💥 **Robust Error Handling**: Exception handling and form validation included.
- 📦 **Data Migration**: Batch imports from Excel with asynchronous insertions.
- 🐳 **Dockerized Deployment**: Easy to run using Docker and Docker Compose.
- 🗄️ **Multi-Database Support**: Compatible with **MySQL**, **PostgreSQL**, and **SQL Server**.

---

## 🧠 Tech Stack

- **Java**: 21  
- **Framework**: Spring Boot, Spring MVC  
- **Frontend**: Thymeleaf (mobile responsive)  
- **Concurrency**: ExecutorService for async inserts  
- **Databases**: MySQL, PostgreSQL, SQL Server  
- **Containerization**: Docker & Docker Compose  
- **Inter-Service Communication**: Feign Client
- **Bot Integration**: Telegram Bot API  
- **Build Tool**: Maven  

---

## 📂 Project Structure

```
el-youm-8/
├── .gitmodules
├── docker-compose.yml
├── El-Youm-8-web-app/
│   ├── src/                      # Spring Boot code (web & REST API)
│   ├── pom.xml                   # Build configuration
│   └── [README.md]               # (Optional) Documentation specific to the web app
├── El-Youm-8-telegram-bot/
│   ├── src/                      # Telegram bot service code
│   ├── pom.xml                   # Build configuration
│   └── [README.md]               # (Optional) Documentation specific to the bot
└── README.md                     # Central README with overview, setup, and instructions
```

---

## 🛠️ Setup Instructions

### 1. Clone the Repository (with submodules)
```bash
git clone --recurse-submodules https://github.com/Yusuf-Hussien/El-Youm-8.git
cd El-Youm-8
```


### 2. Run with Docker (Recommended for Production)
```bash
docker-compose up --build
```

This will start the application, database, and required services.


---

---

## 📧 Contact

For questions or feedback, open an issue on the [GitHub Issues](https://github.com/Yusuf-Hussien/El-Youm-8/issues) page.
