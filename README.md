# internship_task_6
# Contact Form with Client-side Validation ✉️

This project is a simple contact form built using HTML, CSS, and JavaScript. It performs client-side validation for **Name**, **Email**, and **Message** fields and displays real-time feedback for incorrect or empty input.

## 🚀 Features

- HTML form with Name, Email, and Message fields
- Client-side validation using JavaScript
- Regular Expression (Regex) used to validate email format
- Inline error messages for each field
- Prevents form submission if inputs are invalid
- Shows success message on valid submission
- Responsive and clean UI using CSS

---

## 📁 Files Included

- `index.html` – main form structure
- `style.css` – styling for the form
- `script.js` – input validation logic
- `README.md` – project details and usage

---

## 🧪 How to Use

1. Clone this repository or download the ZIP.
2. Open `index.html` in a web browser.
3. Try submitting the form with:
   - Empty fields (should show error)
   - Invalid email (should show error)
   - Valid inputs (should show success message)

---

## 🧠 Concepts Used

- Form Elements (`<form>`, `<input>`, `<textarea>`)
- Event Handling (`submit` event)
- DOM Manipulation (`document.getElementById`)
- JavaScript Validation
- `preventDefault()` to stop real submission
- Regular Expressions (Regex) for email format

---

## 🔒 Validation Logic

```javascript
const emailPattern = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
