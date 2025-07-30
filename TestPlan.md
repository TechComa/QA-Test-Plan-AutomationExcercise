# 🧪 QA Test Plan: AutomationExercise.com

## 📌 Project Overview
This project is a beginner-friendly QA test plan focused on validating core functionalities of [AutomationExercise.com](https://automationexercise.com).  
The goal is to simulate real-world QA tasks including test planning, execution, and bug reporting.

---

## 🎯 Test Objectives
- Validate that key features (login, signup, cart, contact form, etc.) work as expected
- Identify any functional issues or UI/UX inconsistencies
- Simulate a real QA process for portfolio and learning purposes

---

## 🧰 Tools Used
- Manual Testing (Browser-based)
- Bug Reporting: Markdown in `BugReport.md`
- Project Tracking: GitHub Projects Board
- Version Control: Git & GitHub

---

## 📋 Test Scenarios & Cases

| Test ID | Feature            | Test Scenario                                   | Expected Result                            | Status |
|--------|--------------------|------------------------------------------------|--------------------------------------------|--------|
| TC01   | Homepage            | Verify homepage loads with correct title/logo  | Homepage displays title/logo correctly     | ✅     |
| TC02   | Signup/Login        | Test new user signup                           | User should be registered successfully     | ⬜     |
| TC03   | Signup/Login        | Test login with correct credentials            | User logs in successfully                  | ⬜     |
| TC04   | Cart Functionality  | Add item to cart                               | Item is added and reflected in cart        | ⬜     |
| TC05   | Contact Us          | Submit form with valid data                    | Confirmation message is shown              | ⬜     |
| TC06   | Search              | Search for “shirt”                             | Matching results should display            | ⬜     |
| TC07   | Footer Navigation   | Click on “Subscription”                        | Page scrolls and validates email input     | ⬜     |

✅ = Passed | ❌ = Failed | ⬜ = Not Tested

---

## 🧪 Test Data

| Scenario        | Test Data                      |
|----------------|-------------------------------|
| Signup         | Name: Julia Johnson  <br> Email: julia_test@mail.com <br> Password: Test@123 |
| Login          | Email: julia_test@mail.com <br> Password: Test@123 |
| Contact Form   | Name: Julia <br> Email: test@mail.com <br> Subject: Testing <br> Message: Hello! |

---

## 🔄 Test Environment

| Environment     | Details                        |
|----------------|--------------------------------|
| OS              | Windows 11                     |
| Browser         | Chrome (v114+)                 |
| Website         | [https://automationexercise.com](https://automationexercise.com) |
| Tools           | Git Bash, GitHub, VS Code      |

---

## 📌 Notes
- This test plan is created as part of a beginner QA portfolio.
- Bugs will be documented in `BugReport.md` with screenshots and steps to reproduce.
