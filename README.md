

# Monolithic to Microservices

This project demonstrates the transformation of a monolithic application into a microservices architecture. Each arithmetic function is implemented as an independent microservice.

## Project Structure

- **Landing Folder**: Entry point for the application.
- **Microservices**:
  - **Addition Service**
  - **Subtraction Service**
  - **Multiplication Service**
  - **Division Service**
  - **Exponent Service**
  - **GCD Service**
  - **Modulus Service**
  - **App Service**

## Diagram

### Monolithic Architecture
![image](https://github.com/abdul-bit/Monolithic-to-Microservices/assets/59999587/c4a721c7-9f87-4c10-8e18-c53424a693cd)

### Microservices Architecture
![image](https://github.com/abdul-bit/Monolithic-to-Microservices/assets/59999587/2decddfb-0843-486e-9138-e97bcd4d279c)

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/abdul-bit/Monolithic-to-Microservices.git

   cd Monolithic-to-Microservices
   ```
2. Navigate to the microservices directory:
```bash
   cd microservices
```
3. Build and start the services:
```bash
docker-compose up --build
```

4. Access the landing page:
```bash
http://localhost:5050
```
## Microservices
Each microservice is designed to handle a specific arithmetic function and runs on a separate server/container.

- **Addition Service:** Handles addition operations.
- **Subtraction Service:** Handles subtraction operations.
- **Multiplication Service:** Handles multiplication operations.
- **Division Service:** Handles division operations.
- **Exponent Service:** Handles exponentiation operations.
- **GCD Service:** Handles greatest common divisor calculations.
- **Modulus Service:** Handles modulus operations
