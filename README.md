# Everyday-AI--Task
A repo for the given task by GDSC.
A code explanation video https://drive.google.com/file/d/1Jv5PRf6jAs-2XOMHAUn40tDapzbml6IJ/view?usp=drive_link
A submission of form to check everything is working https://drive.google.com/file/d/1Y5fAJfWVB9jOtR6Z3ov-5JSd2jzuL1bO/view?usp=drive_link

# 📄 Everyday AI Registration Automation - GDSC Task

This project automates the registration process for the **"Everyday AI"** event organized by GDSC. It uses **Google Forms**, **Google Sheets**, and **Apps Script** to collect responses, send confirmation emails automatically, and generate a summary dashboard — improving efficiency and reducing manual work.

---

## ✅ Features

- 📋 Custom Google Form for event registration  
- 📨 Auto email confirmation to each participant on form submission  
- 📊 Live-updating dashboard showing:
  - Total Registrations
  - Technical vs Non-Technical count
  - Department-wise breakdown  
- 🛡️ Response validation for email
- 🔁 Trigger-based automation using Apps Script

---

## 🧠 Technologies Used

- **Google Forms** — for collecting responses  
- **Google Sheets** — for storing data and generating dashboard  
- **Google Apps Script** — for automation (email + dashboard update)

---

## 🚀 How It Works

### 1. Google Form Setup

- Fields included:
  - Name (Required)
  - Email Address (Required + validated)
  - Gender
  - Department
  - Are you from a technical or non-technical background? (Required)
  - Why do you want to attend this event? 
  - Do you want to receive email updates? (Required)
  - Prior experience with AI or tech tools

- All responses are sent to a linked **Google Sheet**.

---

### 2. Automated Email on Form Submission

- A script is triggered when someone submits the form.
- The email script reads the "Name" and "Email Address" from the form.
- It sends a thank-you confirmation email like:
