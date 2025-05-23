
🚀 Hello Java Maven - Jenkins CI/CD Project
📝 Overview
This project demonstrates how to set up Jenkins to build a simple Java application using Maven, a key step in the CI/CD pipeline for DevOps automation.

📌 Project Structure
hello-java-maven/
│── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── HelloWorld.java
│── pom.xml
│── README.md
🛠 Tech Stack & Tools
Jenkins 🏗️ - Continuous Integration Server

Maven 📦 - Build & Dependency Management

Java ☕ - Programming Language (JDK 8/11)

GitHub 🔗 - Version Control


🎯 Steps to Run the Project
1️⃣ Clone the Repository


2️⃣ Set Up Maven
Ensure Maven is installed:



3️⃣ Run the Build Locally
Compile and package the Java app:

mvn clean package



4️⃣ Set Up Jenkins



Then, configure:

Add Maven in Manage Jenkins > Global Tool Configuration

Create a Freestyle Job

Set Build Goals: clean package

Click Build Now




5️⃣ Verify Build Success
Check Console Output in Jenkins. You should see:



