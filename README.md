# RPC Framework

> C++ gRPC microservice framework with service discovery

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
C++, gRPC, PostgreSQL, CMake, Docker

## 🏗️ Architecture
Backend service with C++, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/rpc-framework
cd rpc-framework

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
