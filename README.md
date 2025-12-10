# To-Do Application (Spring Boot + Vite + MySQL + Docker)

This is a full-stack To-Do application built with:

- **Backend:** Spring Boot (Java 25 , Spring Boot 4)
- **Frontend:** Vite + React (served by Nginx)
- **Database:** MySQL 8
- **Containerization:** Docker & Docker Compose

## 🧱 Project Structure

```text
to-do-application/
  backend/          # Spring Boot API
    Dockerfile
    pom.xml
    src/
  front-end/        # Vite + React frontend
    Dockerfile
    nginx.conf
    package.json
    src/
  docker-compose.yml
```
## 🚀 Prerequisites

To run this app, you only need:
  - Docker Desktop installed and running
  - Git (to clone the repo)

## How to Run the App

1. Clone the repository:
   ```bash
   git clone <YOUR_REPO_URL>
   cd to-do-application
   ```
2. Build and start all services (backend, frontend, MySQL):

