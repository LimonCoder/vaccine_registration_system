# Vaccine Registration System

## Prerequisites

- Docker and Docker Compose installed on your machine.

## Installation Process

Follow these steps to set up and run the project:

1. **Clone the Repository**
   ```bash
   git clone https://github.com/LimonCoder/vaccine_registration_system.git

2. **Navigate to the Project Root Directory**
   ```bash
   cd vaccine_registration_system

3. **Build and Start the Docker Containers**
   ```bash
   docker-compose up --build -d

4. **Access the application container.**
   ```bash
   docker exec -it application bash

5. **Install Project Dependencies Inside the application container, run:**
   ```bash
   composer install

6. **Access the Application Open your web browser and navigate to:**
   ```bash
   http://localhost:8000
