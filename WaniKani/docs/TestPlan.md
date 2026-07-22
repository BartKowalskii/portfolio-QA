Test Plan - WaniKani

⸻

**1\. Scope & Purpose**

This test plan defines the approach for manual functional testing of the WaniKani studying app on Windows 10 (version 10.0.19045) , Google Chrome (version 140.0.7339.208).

The goal is to validate that the app's core features function correctly from an end-user perspective, with focus on frontend behavior and API responses.

Testing will be performed manually, end-to-end, with a combination of functional, regression, exploratory, and API testing.

⸻

**2\. Features to Be Tested**

• User Registration & Login

• Study session flow (radicals, kanji, vocabulary reviews)

• User profile & settings

• API: Authentication, GET endpoints (user, assignments, reviews), error handling

⸻

**3\. Features Not to Be Tested**

• Subscription payments

• Backend logic beyond API responses

• Third-party integrations (if any)

⸻

**4\. Test Objectives**

• Ensure all available features work as expected from a user's perspective.

• Validate UI flows, error handling, and data consistency.

• Confirm API endpoints return correct responses, including errors.

• Identify and document any functional, usability, or API-related defects.

⸻

**5\. Test Types**

• Functional Testing

• End-to-End Testing

• Regression Testing

• API Testing

• Exploratory Testing

⸻

**6\. Test Environment**

• Devices: Windows 10

• Browsers: Chrome \[140.0.7339.208\]

• Build/Version: \[To be confirmed\]

• Tools Used: Jira! Excel/TestRail, Postman

⸻

**7\. Test Data**

• Dedicated test account created for execution.

• Dummy registration/login data (valid & invalid).

• Edge cases: empty fields, invalid formats, long strings, special characters.

• For API: valid/invalid tokens, missing parameters.

⸻

**8\. Entry & Exit Criteria**

Entry Criteria:

• WaniKani site accessible and stable.

• Test account(s) available.

• API documentation and keys accessible.

Exit Criteria:

• All planned test cases executed.

• No Critical/Blocker bugs open.

• Test summary report prepared and delivered.

⸻

**9\. Risks & Dependencies**

Dependencies:

• Availability of stable production environment.

• Access to API documentation & test accounts.

Risks:

• Unstable API responses may block test execution.

• Limited test data may reduce coverage.

• Third-party system downtime could affect functionality.

⸻

**10\. Deliverables**

• Test Plan (this document)

• Test Cases (Excel / TestRail)

• Regression Suite

• Exploratory Session Report

• Bug Reports (Jira export)

• Test Summary Report

⸻

**11\. Roles & Responsibilities**

Tester :

• Create & execute test cases.

• Perform exploratory testing.

• Log bugs in Jira.

• Prepare test summary report.
