# ecommerce-cake-factory

A Spring Boot–based e-commerce web application featuring REST APIs, JPA/Hibernate persistence, and business logic for managing products, customers, and orders.

This project is the **final capstone** of Manning’s *Web Application* LiveProject series:  
https://www.manning.com/liveprojectseries/web-application-ser

It consolidates the work completed across the previous five projects and adds the final step of packaging and deploying the application to **AWS Elastic Beanstalk**, using **Amazon RDS** for database persistence.

---

## 📦 Features
- REST API built with Spring Boot  
- JPA/Hibernate persistence layer  
- Layered architecture (Controller → Service → Repository)  
- Input validation and error handling  
- Dockerized application image  
- Deployment to AWS Elastic Beanstalk  
- MySQL database hosted on Amazon RDS  
- Environment-based configuration for cloud deployment  

---

## 🛠️ Technology Stack
**Backend:**  
- Java 17  
- Spring Boot  
- Spring Web  
- Spring Data JPA  
- Hibernate  

**Database:**  
- MySQL (Amazon RDS)

**Cloud Deployment:**  
- AWS Elastic Beanstalk  
- AWS RDS  
- Docker  
- AWS EC2 + Load Balancer  

---

## 🚀 Deployment Overview (AWS)
1. Build the JAR (`./mvnw package`)  
2. Build Docker image (`docker build -t <image> .`)  
3. Push image to a container registry (ECR or Docker Hub)  
4. Create an Elastic Beanstalk environment  
5. Configure EB environment variables for RDS connection  
6. Deploy the image and test endpoints  

---

## 📁 Project Structure
