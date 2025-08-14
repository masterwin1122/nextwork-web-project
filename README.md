# NextWork Web Project

This is a **Maven-based Java web application** deployed on **AWS EC2** using **Jetty** and **Nginx**.  
It is part of my learning journey, completed in 7 days.

## 🚀 Features
- Simple Java JSP web app (`index.jsp`)
- Built with **Maven**
- Runs on **Jetty** server
- Reverse-proxied with **Nginx** on EC2
- Source control with **Git** and hosted on **GitHub**
- CI pipeline using **GitHub Actions**

## 📂 Project Structure
nextwork-web-project/
│── src/main/webapp/
│ ├── index.jsp
│ └── WEB-INF/web.xml
│── pom.xml
│── .gitignore


## 🛠 Deployment Steps
1. **Clone the repository**
   ```bash
   git clone git@github.com:masterwin1122/nextwork-web-project.git
   cd nextwork-web-project
Build and run locally

mvn jetty:run


Deploy to AWS EC2

Install Maven & Java

Run Jetty server on port 8080

Configure Nginx as a reverse proxy

🌐 Live Demo

http://ec2-3-121-42-138.eu-central-1.compute.amazonaws.com

📜 License

This project is for educational purposes.
