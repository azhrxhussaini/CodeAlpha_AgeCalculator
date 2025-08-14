# CodeAlpha_AgeCalculator
# 🕒 Age Calculator

A web-based **Age Calculator** built as part of the **CodeAlpha Web Development Internship – Task 1**.

It allows users to enter their date of birth and calculates their exact age in **years, months, and days**.

---

## 📌 Features
- 📅 User inputs their **Date of Birth**.
- 🔍 Calculates **exact age** in years, months, and days.
- 🚫 Prevents **future date selection**.
- ✅ **Responsive** design using **Bootstrap**.
- 🎨 Clean, user-friendly interface.

---

## 🔑 Key Concepts Used
### **1. DOM Manipulation**
- Selecting elements using `document.getElementById`.
- Updating the page dynamically with `.innerHTML`.

### **2. Working with JavaScript Date & Time**
- Using the `Date()` object to:
  - Get the current date.
  - Parse the user’s date of birth.
  - Calculate the difference in years, months, and days.

### **3. Input Validation**
- Ensuring a date is selected before calculation.
- Setting the **max date** to today to prevent future dates.
- Displaying error messages for invalid inputs.

---

## 🛠 Tech Stack
- **HTML** – Structure
- **CSS + Bootstrap** – Styling & Layout
- **JavaScript** – Logic & Calculations

---

## 📸 Screenshot
![Age Calculator Screenshot](screenshot.png)  
*(Replace with your actual screenshot file)*

---

## 🚀 Live Demo
🔗 **Live Project:** [https://yourusername.github.io/CodeAlpha_AgeCalculator/](https://yourusername.github.io/CodeAlpha_AgeCalculator/)  
📂 **Source Code:** [https://github.com/yourusername/CodeAlpha_AgeCalculator](https://github.com/yourusername/CodeAlpha_AgeCalculator)

---

## 📚 How It Works
1. User selects their date of birth.
2. The script checks for:
   - Empty input.
   - Invalid future dates.
3. Calculates:
   - Years → `currentYear - birthYear`
   - Months → Adjusted if current month < birth month
   - Days → Adjusted if current day < birth day
4. Displays the result dynamically.

---

## 📄 License
This project is open-source and free to use.
