# Hospital Management System (HMS) — End-to-End QA & Software Testing Suite

![Project Type](https://img.shields.io/badge/Project-DEPI%20Graduation%20Project-blue)
![Testing Types](https://img.shields.io/badge/Testing-Manual%20%7C%20API%20%7C%20UI%20Automation%20%7C%20Performance-green)
![Tech Stack](https://img.shields.io/badge/Stack-Java%2017%20%7C%20Selenium%20%7C%20Cucumber%20BDD%20%7C%20Postman%20%7C%20JMeter-orange)

## 📌 Project Overview
This repository contains the complete Quality Assurance and Software Testing suite for the **Hospital Management System (HMS)**, developed as part of the Digital Egypt Pioneers Initiative (DEPI) software testing track.

The target system under test (SUT) is a full-stack hospital management web application designed to digitize administrative workflows, role-based access control (RBAC), appointment scheduling, patient admissions, billing, and automated transactional WhatsApp notifications.

---

## 🏗 System Architecture Under Test
* **Frontend:** React + Vite (served via NGINX in Docker)
* **Backend:** Java 17, Spring Boot 3 (Web, Data JPA, Spring Security + JWT)
* **Database:** PostgreSQL 16
* **External Integrations:** Google OAuth 2.0, WhatsApp Notification Outbox Worker

---

## 🧪 Testing Scope & Methodology
Our QA strategy spans multiple testing methodologies to ensure functional reliability, security, data integrity, and performance:

1. **Requirements Analysis & Manual Testing:** Comprehensive test suite design covering 100% of core user workflows (Admin, Doctor, Receptionist).
2. **Backend API Testing:** Functional, authentication, RBAC, and payload validation using **Postman** and CLI automated runs via **Newman**.
3. **UI Test Automation:** Automated end-to-end regression testing using **Selenium WebDriver (Java 17)** with **Page Object Model (POM)** architecture and **Cucumber BDD (Gherkin syntax)**.
4. **Performance & Load Testing:** System baseline, load, and stress testing using **Apache JMeter**.
5. **Defect Management:** Centralized tracking, severity mapping, and sprint traceability using **Jira Software**.

---

## 🛠 Technology Stack & Tools

| Domain | Tools & Technologies |
| :--- | :--- |
| **Language & Frameworks** | Java 17, Maven |
| **UI Automation** | Selenium WebDriver, Page Object Model (POM), Cucumber BDD |
| **API Testing** | Postman, Newman CLI, Swagger UI / OpenAPI |
| **Performance Testing** | Apache JMeter |
| **Environment & Deployment**| Docker, Docker Compose, PostgreSQL 16 |
| **Defect Tracking & Management** | Jira Software, Xray |
| **Version Control & CI** | Git, GitHub, Jenkins CI |

---

## 📅 Project Milestones & Execution Schedule

| Phase | Activity | Duration | Deliverables |
| :---: | :--- | :---: | :--- |
| **Phase 1** | Environment Setup & Requirements Analysis | 2 Days | Environment Baseline, Requirements Matrix |
| **Phase 2** | Manual Testing & Test Case Design | 10 Days | Manual Test Suites, Bug Reports |
| **Phase 3** | API Testing (Postman & Newman) | 7 Days | Postman Collections, Newman CLI Reports |
| **Phase 4** | UI Test Automation (POM & BDD) | 14 Days | Selenium Automation Framework, BDD Feature Files |
| **Phase 5** | Performance & Load Testing | 7 Days | JMeter Test Plans (`.jmx`), Summary Report |
| **Phase 6** | CI/CD Pipeline & Tool Integration | 3 Days | Jenkinsfile Pipeline, Traceability Matrix |
| **Phase 7** | System Regression & Retesting | 3 Days | Retest Execution Logs, Final Defect Report |
| **Phase 8** | Document Integration & Final Submission | 2 Days | Integrated Test Plan PDF & Project Package |

---

## 👥 QA Team & Roles (DEPI Project)

* **Ahmed Hussein** — Team Leader / Senior QA Specialist *(Schedule, Strategy, Automation Architecture, Integration)*
* **Shaza Rabee** — QA Engineer / Business Analyst *(Product Analysis, Scope Definition, Manual Test Suite Design)*
* **Esraa Fathy** — QA Engineer / Test Strategist *(SMART Objectives, Quality Metrics, Entry/Exit Criteria)*
* **Alaa Shehata** — QA Engineer / Infrastructure Lead *(Test Environment Setup, DB Configuration, CI/CD Integration)*
* **Madeha Mahmoud** — QA Engineer / Deliverables Lead *(Test Deliverables Tracking, RACI Matrix, Status Reporting)*
* **Toqa Adel** — QA Engineer / Risk Analyst *(Risk Management, Bottlenecks, Contingency Planning)*

---

## 🚀 Running Tests Locally

### Prerequisites
* Java 17 (JDK) & Apache Maven installed
* Node.js & npm
* Docker Desktop (for backend/frontend/PostgreSQL stack)
* Apache JMeter & Postman / Newman CLI

### 1. Clone the Repository
```bash
git clone [https://github.com/](https://github.com/)<your-username>/HMS-Software-Testing-Suite.git
cd HMS-Software-Testing-Suite
