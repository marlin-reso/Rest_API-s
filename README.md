# Project Summary

<p align="center">
  <img src="https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif" width="600" />
</p>

![API Framework Banner](https://img.shields.io/badge/REST%20Assured-API%20Testing-blue?style=for-the-badge) ![Maven](https://img.shields.io/badge/Maven-Build%20Tool-orange?style=for-the-badge) ![TestNG](https://img.shields.io/badge/TestNG-Testing%20Framework-green?style=for-the-badge) ![Jenkins](https://img.shields.io/badge/Jenkins-CI%2FCD-red?style=for-the-badge) ![Docker](https://img.shields.io/badge/Docker-Containerized-lightblue?style=for-the-badge) ![Allure](https://img.shields.io/badge/Allure-Reporting-purple?style=for-the-badge)

## Rest Assured API Automation Framework

This project is a **Rest Assured-based API Automation Framework** built using industry-standard tools and best practices. It is designed for scalable, maintainable, and CI/CD-ready API testing.

---

## 🚀 **Tech Stack & Tools Used**

### **1. Rest Assured**

* Core library for API automation
* Supports GET, POST, PUT, DELETE, PATCH, Auth, Headers, Cookies, Logging

### **2. Maven**

* Build and dependency management
* Supports multi-module structure and clean execution

### **3. TestNG**

* Testing framework for managing test execution
* Supports:

  * Data Providers
  * Parallel execution
  * Groups
  * Assertions
  * Suites

### **4. Jenkins**

* CI/CD integration for automated pipeline execution
* Integrated with Git & Maven
* Test execution after every commit/merge

### **5. Docker**

* Containerized execution of API tests
* Removes environment dependency
* Enables running tests on any machine or CI server

### **6. Allure Reporting**

* Beautiful, interactive HTML reports
* Provides insights like:

  * Test Summary
  * Steps
  * Attachments
  * Logs
  * Failure analysis

---

## 📁 **Framework Highlights**

* Modular folder structure
* Reusable utility classes
* Base URI & environment configuration
* Request & response specification builders
* Custom listeners for logging
* Assertions using Hamcrest matchers
* Maven command support (`mvn clean test`)
* Allure report generation

---

## 🧪 **Execution Commands**

### **Maven Test Execution:**

```
mvn clean test
```

### **Allure Report Generation:**

```
allure serve allure-results
```

### **Docker Execution:**

```
docker build -t api-framework .
docker run api-framework
```

---

## 📌 **CI/CD Integration (Jenkins)**

* Git webhook triggers Jenkins job
* Maven executes API tests inside pipeline
* Allure plugin publishes report
* Dockerized tests run on any agent

---

## 🏁 Conclusion

This Rest Assured framework provides a **robust, scalable, and CI/CD-ready solution** for API testing using modern tools like Maven, TestNG, Jenkins, Docker, and Allure. It is designed for flexibility, reusability, and professional enterprise use.
