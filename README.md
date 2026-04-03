# QA Testing Portfolio: User Registration & Login System

## 📌 Project Overview
This repository contains a comprehensive End-to-End (E2E) testing suite for a User Registration and Login system. The goal was to validate the system across three layers: **Frontend (UI)**, **API (Integration)**, and **Database (Data Integrity)**.

## 🛠️ Tech Stack & Tools
*   **Test Management:** Excel (Test Cases, Traceability)
*   **API Testing:** Postman (Collection, Environments, Schema Validation)
*   **Database Testing:** SQL (Data Validation, Security, Integrity)
*   **Methodologies:** Boundary Value Analysis (BVA), Equivalence Partitioning (EP), Data-Driven Testing (DDT)

## 📁 Repository Structure
*   `/Test-Cases/`: Detailed test cases covering UI, API, DB, and E2E scenarios.
*   `/Postman/`: API Collection and Environment files (includes Schema Validation and DDT examples).
*   `/SQL-Queries/`: Scripts used for database validation and security checks.

## 🚀 Key Testing Highlights

### 1. Frontend (UI) Testing
*   Validated form field constraints using **BVA** (min/max lengths).
*   Performed exhaustive **Negative Testing** on email and password formats.
*   Verified UI/UX elements like loaders, button states, and password masking.

### 2. API Testing (Postman)
*   **Schema Validation:** Utilized the Ajv library to validate API contract response structures.
*   **Data-Driven Testing (DDT):** Integrated CSV data handling to efficiently test multiple input scenarios (e.g., missing mandatory fields).
*   **Scripted Checks:** Wrote JavaScript-based assertions to verify status codes, response times, and data accuracy.
*   **Security Vulnerabilities:** Wrote test cases for SQL Injection, XSS, Rate Limiting.
*   *Note: Postman scripts are included as a PoC to demonstrate automation logic for core scenarios.*

### 3. Database Validation
*   Verified that sensitive data (passwords) is stored as **hashes**, not plain text.
*   Ensured **Data Integrity** through uniqueness constraints and NULL value checks.
*   Validated auto-increment and timestamp (created_at) functionality.

---
*Created by Javaria Arshad - QA Engineer*
