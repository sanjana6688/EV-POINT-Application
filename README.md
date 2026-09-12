🚗 EV POINT — Manual Testing Project

End-to-end manual testing of an EV charging-station web application, covering functional workflows, admin operations, user journeys, access control, session handling, and defect reporting.

📌 Project Overview

EV POINT is an EV charging-station web application that allows users to find charging stations, make bookings, manage their profile, and cancel bookings. The application also provides an admin portal for managing stations, users, feedback, and bookings.

This repository presents a structured manual testing project created from the Functional Requirements Specification (FRS), with traceable test scenarios, detailed test cases, execution results, and a consolidated defect report.

🎯 Testing Objectives

Validate critical business and user workflows.

Verify positive, negative, boundary, and validation scenarios.

Validate admin vs. standard-user access control.

Verify session and authentication behavior.

Perform database-level verification where required.

Identify, document, prioritize, and track application defects.

Provide clear evidence of application quality and release readiness.

🧪 Test Coverage

The test suite covers 19 functional scenarios across:

Area

Coverage

🔐 Authentication

Login, Logout, Forgot Password

👤 User Management

Dashboard, Profile

⚡ Charging Stations

Find Charger, Station Search, Manage Stations

📅 Booking

Create Booking, Cancel Booking

🛡️ Security

Access Control, Session Management

🧑‍💼 Admin Portal

Dashboard, Users, Feedback, Bookings

📩 Communication

Contact Us

🌐 UI & Navigation

Footer, About Us, navigation & responsiveness

Execution Snapshot

Test cases executed: 275

Passed: 238

Failed: 37

Pass rate: 86.55%

Defects logged: 38

High-severity defects: 11

Medium-severity defects: 19

Low-severity defects: 8

Quality signal: Core application workflows largely function as expected, while authentication/security, validation, booking rules, and edge-case handling contain the primary areas requiring attention.

🔍 Testing Approach

The project follows a practical manual QA lifecycle:

Requirements → Test Scenarios → Test Cases → Execution → Defect Logging → Retesting/Closure

Testing included:

Functional testing

Positive & negative testing

Boundary/value validation

UI and navigation testing

Role-based access testing

Session/security testing

Database verification

Browser validation

Error-message and form-validation checks

Responsive layout checks

🐞 Defect Management

Defects are documented with:

Unique Bug ID

Description

Steps to Reproduce

Expected Result

Actual Result

Severity

Priority

Screenshot/evidence field

The defect report contains 38 documented defects, with priority distribution focused heavily on High-priority issues, helping identify defects that should be addressed before release.

📂 Project Files

├── Manual Testing Project.xlsx
│   ├── Version
│   ├── Test Scenarios
│   └── Detailed test-case execution sheets
│
├── Defect Report.xlsx
│   └── Consolidated defect log
│
└── README.md

🏆 Key QA Highlights

Built a requirement-oriented test suite covering the complete application journey.

Validated both frontend behavior and backend/database outcomes.

Tested authorization boundaries between guest, standard user, and admin roles.

Identified defects in important areas such as authentication, validation, booking controls, and session handling.

Maintained structured execution results with clear PASS/FAIL evidence and linked defect IDs.

💡 Sample Validation Areas

Examples of high-value scenarios covered include:

Invalid login and repeated failed-login attempts

Unauthorized access to admin routes

Session behavior after logout/browser closure

Invalid email and form-field validation

Searching stations with different filter combinations

Booking with past dates or invalid time ranges

Booking when no charging ports are available

Preventing users from cancelling another user's booking

Database verification after booking/cancellation

Responsive UI and navigation validation

📊 Deliverables

Deliverable

Purpose

Test Scenarios

Defines functional scope and coverage

Test Cases

Provides detailed preconditions, steps, data, expected & actual results

Execution Results

Records PASS/FAIL status

Defect Report

Tracks defects with severity and priority

README

Provides a concise project and QA overview

👩‍💻 Tester

Sanjana
Manual QA / Software Testing Project
Project: EV POINT
Version: 1.0
Prepared: August 2026
