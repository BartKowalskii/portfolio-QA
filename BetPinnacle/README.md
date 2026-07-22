
# Betting App BetPinnacle – Manual QA Project

![Manual Testing](https://img.shields.io/badge/Testing-Manual-blue)
![Jira](https://img.shields.io/badge/Jira-Bug%20Tracking-blue)

## Overview
This project documents manual QA testing performed for a mobile betting application (iOS).
The goal was to validate key user journeys and ensure stable functionality, UI consistency, and smooth user experience across registration, authentication, betting, and account management features.

⸻

## 📊 QA Metrics Summary

* **Functional Test Cases:** 28 Test Cases (`test-cases/TestCases.md`)
* **Regression Suite:** 10 Selected Scenarios (`test-cases/RegressionSuite.md`)
* **Exploratory Testing:** 1 Session / 60 Minutes (`docs/ExploratorySessionReport.md`)
* **Bugs Logged:** 4 Defects in Jira (`docs/JiraExport.md`)

---

## 📑 Test Cases Breakdown (28 Test Cases)

| Module | Test Cases Count | Focus Area |
| :--- | :---: | :--- |
| **Registration & Login** | **8 TC** | Field validations, edge cases, error messaging |
| **Betting Engine (Sports & Races)** | **8 TC** | Odds selection, bet slips, race options |
| **KYC & Document Verification** | **6 TC** | Upload flow, status handling, app stability |
| **Deposits & Responsible Gambling** | **6 TC** | Deposit UI flow, daily/monthly limits |
| **TOTAL** | **28 TC** | |

---

## 🐛 Logged Defects (4 Jira Bugs)

1. **BB-5 (Critical):** App crashes upon entering document verification screen.
2. **BB-2 (Medium):** Option selection unresponsive on Race screen.
3. **BB-6 (Low):** "Boxed" text misaligned in Exotics section.
4. **BB-9 (Low):** HTML/XML tags displayed raw on loading screen.

## Objectives
	•	Verify core frontend functionality through manual end-to-end testing.
	•	Identify and document functional, usability, and UI issues.
	•	Maintain structured documentation for test planning, execution, and reporting.
	•	Collaborate in an Agile/Scrum-style workflow with iterative builds and sprint-based testing cycles.

⸻

## Scope

Frontend testing only — backend logic, payment processing, and real transaction handling were excluded.
Testing was conducted on iPhone 15 Pro (iOS 18.6) using development builds provided by the project developer.

⸻

## Process & Approach
	•	Created a Test Plan defining test objectives, scope, and environment setup.
	•	Designed detailed Test Cases covering positive, negative, and edge scenarios.
	•	Conducted Exploratory Testing sessions to uncover UI/UX inconsistencies.
	•	Logged and tracked defects using Jira, verified fixes in subsequent builds.
	•	Maintained regression suite and reports in TestRail and Excel.
	•	Participated in sprint planning, test execution, and sprint review meetings as part of a Scrum-style Agile process.

⸻

## Tools & Environment

Category	Tools / Details
Device	iPhone 15 Pro (iOS 18.6)
Test Management	TestRail, Excel, Word
Bug Tracking	Jira
Methodology	Scrum-style Agile


⸻

## Deliverables
	•	Test Plan
	•	Test Cases
	•	Regression Suite
	•	Exploratory Testing Report
	•	Bug Reports (Jira)


⸻

## Key Findings
	•	Several validation errors and UI alignment issues identified during exploratory sessions.
	•	One critical crash in the document verification flow resolved after fix verification.
	•	Improved error message clarity and user flow logic after QA feedback.
	•	All high and critical defects closed before the release candidate build.

⸻

## Collaboration

This project was completed in collaboration with a startup developer (project collaborator).
I was responsible for the entire QA process — from test planning through execution, reporting, and final verification. The app is currently in pre-release development phase.

⸻

## Outcome
	•	All major user journeys validated.
	•	No open critical issues after retesting.
	•	Established a reusable regression suite and documented QA process for future builds.

