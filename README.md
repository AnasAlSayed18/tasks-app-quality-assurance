#  Quality Assurance Testing for Tasks Android App ✅

<img src="https://github.com/AnasAlSayed18/img/blob/07b99197c051797d732b9daff2fc39df0e3f6721/qalogo.png" width="250" />

## 📜 Overview
This project presents a full **Quality Assurance (QA) lifecycle** for the open-source [Tasks Android App](https://github.com/tasks/tasks), a productivity app built in Kotlin and Java.

As part of the **COMP438 – Software Testing & QA** course, we conducted requirement analysis, static testing, black-box and white-box testing, automation, and performance evaluation.

Our team applied diverse methodologies and tools including **JUnit**, **Appium**, **Selenium**, **JMeter**, and **Jira** to ensure comprehensive coverage.

---

## 🧪 Application Under Test

**App Name:** Tasks  
**Platform:** Android  
**Language:** Kotlin & Java  
**Architecture:** MVVM  
**Database:** Room  
**Features Tested:**
- Task creation, editing, completion
- Reminder setup
- Repeating tasks and notifications
- Tagging, attachments, and subtasks
- Calendar sync (CalDAV, Google)
- UI and accessibility

---

## 🎯 Testing Techniques Applied

| Testing Type        | Tools Used         | Scope                          |
|---------------------|--------------------|---------------------------------|
| Static Testing       | Manual Inspection  | Task.kt, ViewModels, DateTime.kt |
| Unit Testing         | JUnit              | Core logic and validation       |
| Black-Box Testing    | Manual             | GUI features and user flows     |
| White-Box Testing    | Statement, Branch  | Core functions in Task.kt       |
| Regression Testing   | Manual             | After updates/fixes             |
| Automation Testing   | Appium, Selenium   | Task creation/edit/delete       |
| Performance Testing  | JMeter             | Load simulation and response time|

---

## 📁 Key Test Artifacts

- ✅ **Test Plan Document** (scope, strategy, risks, traceability)
- 📋 **Black-box & White-box Test Cases** (with IDs and outcomes)
- ⚙️ **JUnit Unit Tests**
- 🤖 **Appium/Selenium Automation Scripts**
- 📊 **JMeter Performance Reports**
- 📌 **Jira Project** with all test cases, executions, and bugs

---

## 📸 Screenshots

### JUnit Unit Test Results
![JUnit Results](https://github.com/AnasAlSayed18/img/blob/07b99197c051797d732b9daff2fc39df0e3f6721/qa1.png)

### Appium Automated Testing
![Appium](https://github.com/AnasAlSayed18/img/blob/07b99197c051797d732b9daff2fc39df0e3f6721/qa2.png)

### JMeter Performance Test
![JMeter](https://github.com/AnasAlSayed18/img/blob/07b99197c051797d732b9daff2fc39df0e3f6721/qa3.png)

---

## 👨‍💻 Team Members & Responsibilities

- **Anas Al Sayed** – Requirements analysis, static inspection, black-box and white-box testing
- **Abd Al-Raheem Yaseen** – Regression testing, edge-case test design, static reviews
- **Rakan Omar** – Static testing for time logic, leap day validation
- **Ahmad Rimawi** – Jira test management, static ViewModel analysis
- **Mohammad Nemer** – JMeter performance testing, UI load validation

**Instructor:** Dr. Faisal Shehadeh  
**Course:** COMP438 – Software Testing & QA

---

## 🎬 Demo & Presentation

[Watch Demo (Coming Soon)](#)

---

## 🧩 Project Objectives Recap

- ✔ Analyze functional & non-functional requirements
- ✔ Apply static, dynamic, regression, and automation testing
- ✔ Track and document results in Jira
- ✔ Deliver full test plan, metrics, and traceability matrix

---

## 📚 References

- [Tasks App GitHub](https://github.com/tasks/tasks)
- [JUnit 5](https://junit.org/junit5/)
- [Apache JMeter](https://jmeter.apache.org/)
- [Appium](https://appium.io/)
- [Selenium WebDriver](https://www.selenium.dev/)
