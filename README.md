# E-commerce Application

## Overview
This is a full-stack **E-commerce Application** built using **Spring Boot** for the backend and **React.js** for the frontend. The application allows users to browse products, search for items, and manage product listings.

## Tech Stack
### **Backend:**
- Spring Boot
- Spring Data JPA
- PostgreSQL / MySQL
- Hibernate
- RESTful APIs
- Lombok

### **Frontend:**
- React.js
- Vite
- Bootstrap
- Axios (for API calls)

## Features
### **Backend (Spring Boot):**
- Developed RESTful APIs for handling products and search functionality.
- Integrated Spring Data JPA with PostgreSQL to manage product records efficiently.
- Configured CORS to allow communication between backend and frontend.
- Used Hibernate to manage database operations.

### **Frontend (React.js):**
- Fetches product data from the backend using Axios.
- Displays products dynamically with a search functionality.
- Uses Bootstrap for responsive UI design.
- Implements a background video for enhanced UI/UX.

## Setup & Installation

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/Ecommerce-App.git
cd Ecommerce-App
```

### **2. Backend Setup (Spring Boot)**
#### **Navigate to backend directory:**
```bash
cd backend
```
#### **Configure Database in `application.properties` (Update with your DB credentials):**
```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/ecommerce_db
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```
#### **Run the Spring Boot application:**
```bash
mvn spring-boot:run
```

### **3. Frontend Setup (React.js + Vite)**
#### **Navigate to frontend directory:**
```bash
cd ../frontend
```
#### **Install dependencies:**
```bash
npm install
```
#### **Start the development server:**
```bash
npm run dev
```

## API Endpoints
| Method | Endpoint | Description |
|--------|------------|-------------|
| GET | `/api/products` | Fetch all products |
| GET | `/api/products/{id}` | Fetch product by ID |
| GET | `/api/products/search?keyword=value` | Search products |
| POST | `/api/products` | Add new product |
| DELETE | `/api/products/{id}` | Delete product |

## Deployment
### **Backend Deployment (Spring Boot)**
- Use **Heroku**, **Render**, or **Railway.app** to deploy.
- Configure database credentials in environment variables.

### **Frontend Deployment (React.js)**
- Deploy using **Vercel**, **Netlify**, or **GitHub Pages**.
- Set the backend URL in `.env` for production mode.

## Contributing
1. Fork the repo
2. Create a new branch (`feature-branch`)
3. Commit your changes (`git commit -m 'Added new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a pull request

## Author  
GitHub: [Kumar Sanu](https://github.com/your-username)

