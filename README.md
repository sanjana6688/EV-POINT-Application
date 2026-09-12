# EV POINT — Manual Testing Project

## Project Overview

**EV POINT** is an EV charging-station web application that allows users to find charging stations, make bookings, manage their profiles, and cancel bookings.

The application also provides an **Admin Portal** for managing charging stations, users, feedback, and bookings.

This repository contains a complete **Manual Testing / QA project** created based on the application's Functional Requirements Specification (FRS). The project includes requirement-oriented test scenarios, detailed test cases, execution results, and a consolidated defect report.

---

## Testing Objectives

The primary objectives of this project are to:

- Validate critical business and user workflows.
- Verify positive, negative, boundary, and validation scenarios.
- Validate access control between different user roles.
- Verify authentication and session management.
- Validate booking and cancellation workflows.
- Perform database-level verification where required.
- Identify, document, prioritize, and track application defects.
- Validate UI, navigation, and responsive behavior.
- Provide clear test execution evidence.
- Assess the overall quality and release readiness of the application.

---

## Test Coverage

The test suite covers **19 functional scenarios** across the following application areas:

| Area | Coverage |
|------|----------|
| 🔐 Authentication | Login, Logout, Forgot Password |
| 👤 User Management | Dashboard, Profile |
| ⚡ Charging Stations | Find Charger, Station Search, Manage Stations |
| 📅 Booking | Create Booking, Cancel Booking |
| 🛡️ Security | Access Control, Session Management |
| 🧑‍💼 Admin Portal | Dashboard, Users, Feedback, Bookings |
| 📩 Communication | Contact Us |
| 🌐 UI & Navigation | Footer, About Us, Navigation & Responsiveness |

---

## Test Execution Summary

| Metric | Result |
|--------|--------|
| Test Cases Executed | **275** |
| Passed | **238** |
| Failed | **37** |
| Pass Rate | **86.55%** |
| Defects Logged | **38** |
| High Severity | **11** |
| Medium Severity | **19** |
| Low Severity | **8** |

### Quality Summary

The core application workflows largely function as expected. However, defects were identified primarily in:

- Authentication and security
- Form validation
- Booking rules and restrictions
- Session handling
- Negative and boundary scenarios
- Edge-case handling

These areas require attention before the application can be considered fully release-ready.

---

## Testing Approach

The project follows a structured manual QA lifecycle:


Requirements
     ↓
Test Scenarios
     ↓
Test Cases
     ↓
Test Execution
     ↓
Defect Logging
     ↓
Defect Closure

---

## Tester

Sanjana
Manual QA / Software Testing Project

Project: EV POINT
Version: 1.0
Prepared: August 2026

---

## Conclusion

The EV POINT manual testing project demonstrates an end-to-end QA approach covering functional testing, validation, security, access control, session management, database verification, UI testing, and defect management.

The project provides structured and traceable testing documentation that can be used to assess application quality, identify high-risk areas, support defect resolution, and determine release readiness.

---

## Project Focus

Manual Testing | Functional Testing | Test Case Design | Defect Management | SQL/Database Validation | Security Testing | UI Testing | QA Documentation
