# HTML Authentication System POC

## Project Overview

This project is a simple Proof of Concept (POC) of an HTML-based Authentication System.  
It is developed using only basic HTML structure as required in the assignment instructions.

The project contains 5 separate HTML pages that simulate a basic authentication workflow such as Login, Registration, Forgot Password, Reset Password, and Dashboard.

No CSS or JavaScript has been used in this project.  
All page navigation is implemented using anchor (<a>) tags only.

---

## Objective

The objective of this project is to:

- Understand basic HTML page structure
- Practice creating multiple HTML pages
- Implement navigation between pages using anchor tags
- Create and upload a public GitHub repository

---

## Technologies Used

- HTML5 (Basic Structure Only)
- Anchor Tag Redirection
- GitHub (for repository hosting)

No CSS, JavaScript, or external libraries are used.

---

## Project Structure

The project contains the following files:

1. login.html
2. register.html
3. forgot-password.html
4. reset-password.html
5. dashboard.html
6. README.md

---

## Page Description

### 1. Login Page (login.html)
- Allows user to enter email and password
- Contains links to:
  - Register Page
  - Forgot Password Page
- Login button redirects to Dashboard page

### 2. Register Page (register.html)
- Allows user to enter name, email, and password
- After clicking Register, user is redirected to Login page

### 3. Forgot Password Page (forgot-password.html)
- User enters email
- "Send Reset Link" redirects to Reset Password page

### 4. Reset Password Page (reset-password.html)
- User enters new password and confirm password
- After reset, user is redirected back to Login page

### 5. Dashboard Page (dashboard.html)
- Displays welcome message
- Contains Logout link
- Logout redirects back to Login page

---

## Navigation Flow

Login → Dashboard  
Login → Register → Login  
Login → Forgot Password → Reset Password → Login  
Dashboard → Logout → Login  

All navigation is implemented using anchor tags only.

---

## Important Notes

- This is a static HTML project.
- No real authentication or backend logic is implemented.
- This project is created only for educational and demonstration purposes.
- Repository is made PUBLIC as per assignment requirement.

---

## Author

Created as part of HTML Authentication System POC assignment submission.