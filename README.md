# 📋 Manual Testing Report – Daraz Website

This repository contains a structured manual testing report for the **Daraz e-commerce platform**. It covers test planning, test case design, execution details, and key observations made during testing.

---

## 🔍 Project Overview

**Application Under Test (AUT):** [Daraz](https://www.daraz.com/)

**Testing Type:** Manual Functional Testing

**Platform Tested On:**
- Desktop (Chrome, Firefox)
- Mobile Browser (Android)
- OS: Windows 10, Android 12

---

## 🧪 Test Coverage

The following areas of Daraz were tested manually:

1. **Homepage and Navigation**
2. **User Login and Registration**
3. **Search and Filters**
4. **Product Details Page**
5. **Cart Functionality**
6. **Checkout Process**
7. **Order Management**
8. **Notifications and Popups**
9. **Mobile Responsiveness**
10. **Security and Session Management**

---

## 📄 Sample Test Case

| Test Case ID | TC-001 |
|--------------|--------|
| Title        | Login with Valid Credentials |
| Priority     | High |
| Precondition | Registered user exists |
| Steps        | 1. Open Daraz <br> 2. Click Login <br> 3. Enter valid credentials <br> 4. Click Submit |
| Expected Result | User is redirected to dashboard |
| Actual Result   | As expected |
| Status       | ✅ Pass |

---

## 🐞 Sample Bugs Found

| Bug ID | BUG-003 |
|--------|---------|
| Title  | No error message for invalid password |
| Steps  | Login with incorrect password |
| Expected | Show "Invalid password" message |
| Actual   | Page refreshes silently |
| Severity | Medium |
| Status   | Open |

---

## ✅ Tools Used

- Browser Developer Tools (Chrome DevTools)
- Notepad/Google Sheets for test case tracking
- Lighthouse (basic performance/accessibility checks)

---

## 📌 Observations

- **Strengths:** Smooth UI/UX, fast search, responsive design.
- **Issues:** Some validation bugs, missing alert messages, inconsistent filter behavior.

---

## 📁 Folder Structure

