# Automated CI/CD Pipeline for Full-Stack Application Deployment

This project demonstrates the development and implementation of an automated CI/CD pipeline using Jenkins for seamless deployment of a **Full-Stack Application**. The application consists of an **Angular frontend** and a **Java Spring Boot backend**. This project showcases modern DevOps practices by integrating various tools and technologies like Docker, Kubernetes, AWS, Prometheus, and Grafana.

---

## 🔧 Technologies and Tools Used
- **CI/CD Pipeline**: Jenkins  
- **Frontend**: Angular  
- **Backend**: Java Spring Boot  
- **Containerization**: Docker  
- **Orchestration**: Kubernetes  
- **Cloud Infrastructure**: AWS  
- **Code Repository**: GitHub  
- **Monitoring**: Prometheus & Grafana  

---

## 📋 Project Workflow

1. **Code Management**  
   - All source code is maintained and version-controlled using **GitHub**.

2. **CI/CD Pipeline Setup**  
   - Configured **Jenkins** for automating build, test, and deployment processes.
   - Pipeline triggered on every **code commit** to the GitHub repository.

3. **Containerization and Orchestration**  
   - **Docker** is used to containerize the Angular frontend and Java backend.
   - **Kubernetes** ensures efficient orchestration and scaling of containers.

4. **Cloud Infrastructure**  
   - Deployed on **AWS**, leveraging cloud services for high availability and scalability.

5. **Monitoring and Performance Tracking**  
   - Integrated **Prometheus** for collecting metrics and **Grafana** for real-time visualization and monitoring of system performance.

---

## ⚙️ How to Run Locally

### Prerequisites
- **Docker** and **Kubernetes** installed  
- **Jenkins** server setup  
- AWS account with necessary permissions  
- **Node.js** (for Angular frontend)  
- **Java** (for Spring Boot backend)  

### Steps

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/fullstack-ci-cd-pipeline.git
   cd fullstack-ci-cd-pipeline
