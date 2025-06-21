# 🧩 MicroServicesApp – Modular Distributed Application

MicroServicesApp is a microservices-based distributed application demonstrating scalable backend development using the **.NET ecosystem**, **RESTful APIs**, and **containerized services**. It follows best practices in domain-driven design, communication via API gateways, and independent deployment of services.

---

## 🚀 Features

- 🧱 Service-oriented architecture using clean separation of concerns  
- 📡 RESTful communication between services  
- 🐳 Container-ready with Docker support  
- 🔁 CI/CD integration with Azure DevOps or GitHub Actions  
- 🔐 Authentication-ready with support for JWT/OAuth2  
- 📊 Integrated monitoring and centralized logging support  

---

## 🛠 Tech Stack

### 💻 Backend
- **.NET 6**, **C#**
- **ASP.NET Core Web API**
- **Entity Framework Core**
- **SQL Server**

### 🧰 DevOps & Containers
- **Docker** for containerization  
- **Azure DevOps**, **GitHub Actions** for CI/CD pipelines  
- **Swagger** for API documentation  
- **Postman** for testing  

---

## 📦 Microservices

- `ProductService`: Manages product-related endpoints and data  
- `OrderService`: Handles order placement and tracking  
- `UserService`: Manages user accounts and profiles  
- `GatewayAPI`: Acts as the API gateway for routing between services  

---

## 📂 Project Structure

```bash
MicroServicesApp/
├── ProductService/
├── OrderService/
├── UserService/
├── GatewayAPI/
├── Shared/
└── README.md

⚙️ Getting Started
🔧 Prerequisites
.NET 6 SDK

Docker (optional for container deployment)

SQL Server

🔄 Run Locally
Clone the repository:

bash

git clone https://github.com/yourusername/MicroServicesApp.git
cd MicroServicesApp
Navigate to each service folder and run:

bash

dotnet restore
dotnet run
Or use Docker Compose (if provided):

bash

docker-compose up --build

