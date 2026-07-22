Test plan - BetPinnacle

⸻

1\. Scope & Purpose

This test plan defines the approach for functional testing of the betting app on iOS (iPhone 15 Pro, iOS 18.6). The goal is to validate that the app's core features work correctly from a normal user's perspective, focusing on frontend behavior. Testing is performed manually, end-to-end, with no automation.

2\. Features to Be Tested

The following features will be tested as and when available in the development build:

• User Registration & Login

• Deposits & Withdrawals (frontend flow, no real transactions)

• Placing Bets (including sports, races, live betting)

• Bet Bonuses

• Responsible Gambling - Setting Limits

• Account Management (profile, settings, logout, etc.)

• Document Verification (KYC flow, upload & status checks)

• Transaction History

3\. Features Not to Be Tested

• Backend services, payment gateway processing, or odds calculation logic.

• Features not yet available in the development build.

4\. Test Objectives

• Ensure all available features work as expected from a user's point of view.

• Validate UI flows, error handling, and data consistency in the frontend.

• Identify and document any functional bugs or usability issues.

5\. Test Types

• Functional Testing (manual execution of user flows)

• End-to-End Testing (simulating real user journeys: registration → deposit → betting → history)

• Regression Testing (on new builds, ensure previous features still work)

6\. Test Environment

• Device: iPhone 15 Pro

• OS: iOS 18.6

• Build: app version 1.0.0 (12)

7\. Test Data

• Dedicated test account created for execution.

• Dummy input data for registration, deposits, withdrawals, and verification (no real money used).

• Both valid and invalid data for edge cases (e.g., empty fields, incorrect formats, insufficient balance).

8\. Entry/Exit Criteria

Entry Criteria:

• App build successfully installed on device.

• Feature available in development build.

• Test account available.

Exit Criteria:

• All planned test cases executed.

• No critical/blocker bugs open.

• Test summary report documented.

9\. Risks & Dependencies

• Dependencies: Availability of development build, backend stability, third-party integrations (e.g., document verification).

• Risks: Some features not implemented yet; scope of testing may be limited.

10\. Deliverables

• Test Cases

• Executed Test Results (pass/fail)

• Bug Reports

• Test Summary Report

11\. Roles & Responsibilities

• Tester: Responsible for creating test cases, executing tests, logging bugs, and preparing summary reports.
