[![Build Status](http://localhost:8080/job/Hello-Java-Maven-Build/badge/icon)](http://localhost:8080/job/Hello-Java-Maven-Build/)

# Hello Java Maven Project 🚀

Simple **Java HelloWorld** application built with **Maven** and integrated with **Jenkins** for Continuous Integration (CI).

## 📂 Project Structure

hello-java-maven/
├── src/
│ └── main/
│ └── java/
│ └── HelloWorld.java
├── pom.xml
├── .gitignore
└── README.md

## 🛠 Build Instructions

Run the following Maven command to build the project:

```bash
mvn clean package

Expected output:
[INFO] BUILD SUCCESS

🤖 Jenkins Integration

This project is built using Jenkins with a Freestyle Job:

Maven Goal: clean package

Output: BUILD SUCCESS

✅ Build Status

```

## 📸 Jenkins Build Screenshot

Here’s the proof of successful Jenkins build:

![Jenkins Build Success](screenshots/jenkins-build-success.png)
