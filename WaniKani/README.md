 # WaniKani App Testing
 
![Manual Testing](https://img.shields.io/badge/Testing-Manual-blue)
![API](https://img.shields.io/badge/API-Postman-orange)
![Jira](https://img.shields.io/badge/Jira-Bug%20Tracking-blue)

## Overview
This project demonstrates manual functional and API testing of **WaniKani**, a Japanese learning web and desktop application.  
The goal was to validate key user workflows, frontend behavior, and API response accuracy from an end-user perspective.  
Testing was performed using an Agile/Scrum-style approach with Jira for bug tracking and TestRail/Excel for test management.

---

## 📊 QA Metrics Summary

* **UI Test Cases:** 20 Test Cases (`test-cases/UI_TestCases.md`)
* **API Test Cases:** 12 Test Cases (`test-cases/API_TestCases.md`)
* **Regression Suite:** 10 Selected Scenarios (`test-cases/RegressionSuite.md`)
* **Postman API Evidence:** 2 Visual Proof Screenshots (`Postman/`)
* **Bugs Logged:** 3 Defects in Jira (`docs/JiraExport.md`)

---

## 📑 Test Breakdown (32 Total Test Cases)

### 1. UI & Functional Suite (20 Test Cases)
* **Registration Flow (`REG-01` to `REG-14`):** 14 Test Cases covering password policies, checkbox validation, email formats, and empty states.
* **Login Flow (`LOG-01` to `LOG-06`):** 6 Test Cases covering valid/invalid credentials, empty input handling, and redirects.

### 2. API Test Suite (12 Test Cases)
* **Authentication & Endpoints:** GET requests for User details, Assignments, and Study Reviews.
* **API Validation:** Authorization headers, valid/invalid tokens, status codes (200, 401, 404), and JSON response structure.

---

## 🐛 Logged Defects (3 Jira Bugs)

1. **JIRAWK-01 (High):** Invalid email format allowed during registration.
2. **JIRAWK-02 (Medium):** Weak password missing complexity requirements is accepted.
3. **JIRAWK-03 (Medium):** API endpoint response time exceeds threshold under standard GET payload.

---

## Scope
Testing covered:
- User Registration & Login
- Lesson & Review Sessions (radicals, kanji, vocabulary)
- Profile & Settings
- API validation for `/user`, `/assignments`, and related endpoints

Not in scope:
- Payment/subscription features
- Backend logic beyond API responses
- Third-party service integrations

---

## Objectives
- Ensure the core study and login flows function as expected.
- Validate API endpoints return correct, consistent data.
- Verify UI feedback for errors and edge cases.
- Identify usability and functional issues across supported environments.

---

## Test Types
- Functional Testing  
- End-to-End Testing  
- Regression Testing  
- API Testing (Postman)  
- Exploratory Testing

---

## Environment
- Platforms: Windows 10, Chrome [140.0.7339.208]
- Tools: Jira, TestRail, Excel, Postman
- Build: Web application (latest production build)
- Methodology: Agile / Scrum-style workflow

---

## Deliverables
- **Test Plan:** overall testing strategy and scope  
- **Test Cases:** functional and API test scenarios  
- **Regression Suite:** critical workflow verification  
- **Bug Reports:** logged in Jira with screenshots and steps to reproduce  

---

## Sample Test Areas
**UI Tests**
- Registration and login validation (positive & negative)
- Lesson flow behavior (correct/wrong answers, typos, case sensitivity)
- Input field handling (long inputs, empty fields, special characters)

**API Tests**
- Authentication validation with valid/invalid tokens
- GET requests for user data and assignments
- Error handling for bad parameters and unsupported methods

---

## Summary
The WaniKani app’s core flows (study sessions, login, API data fetches) performed as expected in stable environments.  
Minor issues were identified in input validation and error handling, particularly in registration and synonym recognition during lessons.

---

## Tools Used
- **Jira** – defect tracking  
- **TestRail / Excel** – test management  
- **Postman** – API testing  
- **Word** – documentation

---

**Tester:** Bart  
**Role:** Manual QA (Agile/Scrum style)  
**Duration:** 1-week testing cycle (functional + API)  
