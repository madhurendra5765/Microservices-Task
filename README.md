# Microservices-Task

## Overview
This document provides details on testing various services after running the `docker-compose` file. These services include User, Product, Order, and Gateway Services. Each service has its own endpoints for testing purposes.

---

## Services and Endpoints

### **User Service**
- **Base URL:** `http://localhost:3000`
- **Endpoints:**
  - **List Users:**  
    ```
    curl http://localhost:3000/users
    ```
    Or open in your browser: [http://localhost:3000/users](http://localhost:3000/users)
<img width="1027" height="425" alt="gateway_dockerfile" src="https://github.com/user-attachments/assets/681dc5cf-f3a4-4155-964f-3d4ff5c29133" />


---

### **Product Service**
- **Base URL:** `http://localhost:3001`
- **Endpoints:**
  - **List Products:**  
    ```
    curl http://localhost:3001/products
    ```
    Or open in your browser: [http://localhost:3001/products](http://localhost:3001/products)
<img width="1017" height="606" alt="product_dockerfile" src="https://github.com/user-attachments/assets/1428bd5b-614e-4363-a52f-9911779e6cb4" />

---

### **Order Service**
- **Base URL:** `http://localhost:3002`
- **Endpoints:**
  - **List Orders:**  
    ```
    curl http://localhost:3002/orders
    ```
    Or open in your browser: [http://localhost:3002/orders](http://localhost:3002/orders)

---

### **Gateway Service**
- **Base URL:** `http://localhost:3003/api`
- **Endpoints:**
  - **Users:**  
    ```
    curl http://localhost:3003/api/users
    ```
  - **Products:**  
    ```
    curl http://localhost:3003/api/products
    ```
  - **Orders:**  
    ```
    curl http://localhost:3003/api/orders
    ```
<img width="971" height="671" alt="user_dockerfile" src="https://github.com/user-attachments/assets/eff60995-6bc1-49f6-8ae1-4f4d4950ff6b" />

---

## Instructions
1. Start all services using the `docker-compose` file:
   ```
   docker-compose up
   ```

   <img width="915" height="742" alt="Docker_compose_yaml" src="https://github.com/user-attachments/assets/9510cea6-d42a-4445-aaeb-49a2d54d1d53" />

2. Once the services are running, use the above endpoints to verify the functionality.

Happy testing!
