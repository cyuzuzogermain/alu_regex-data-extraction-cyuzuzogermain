# Input Validation Form (JavaScript)

This project is a simple HTML + CSS + JavaScript form that validates various input fields using **regular expressions (regex)**.  
It checks whether the user inputs follow the correct format for common data types such as email, phone numbers, URLs, credit cards, and more.

---

## Features
- **Email validation** (e.g., `user@example.com`, `firstname.lastname@company.co.uk`)  
- **URL validation** (e.g., `https://example.com`, `https://sub.example.org/page`)  
- **Phone numbers** in multiple formats (e.g., `(123) 456-7890`, `123-456-7890`, `123.456.7890`)  
- **Credit card numbers** with spaces or dashes (e.g., `1234 5678 9012 3456`, `1234-5678-9012-3456`)  
- **Time formats**: 24-hour (`14:30`) and 12-hour (`2:30 PM`)  
- **HTML tags** (e.g., `<p>`, `<div class="example">`, `<img src="x.jpg" />`)  
- **Hashtags** (e.g., `#example`, `#ThisIsAHashtag`)  
- **Currency amounts** (e.g., `$19.99`, `$1,234.56`)  
- Each field displays **validation results** (Valid / Invalid) directly below the input.  
- All fields are **required** before submission.  

---

## Project Structure

alu_regex-data-extraction-cyuzuzogermain
┣  index.html # Main form with validation logic
┗  README.md # Project documentation


---

## How It Works
1. Open `index.html` in any modern browser.  
2. Fill in all the input fields.  
3. Click **Validate**.  
4. The results (Valid/Invalid) will appear under each corresponding field.  

---

## Styling
- Clean **modern design** using plain CSS.  
- Responsive layout with shadows, rounded corners, and hover effects.  

---

## Example Inputs
- **Email** → `user@example.com`  
- **URL** → `https://www.example.com`  
- **Phone** → `(123) 456-7890`  
- **Credit Card** → `1234-5678-9012-3456`  
- **Time (24h)** → `14:30`  
- **Time (12h)** → `2:30 PM`  
- **HTML Tag** → `<p>Hello</p>`  
- **Hashtag** → `#CoolProject`  
- **Currency** → `$1,234.56`  

---

## Requirements
- Works in any **modern web browser** (Chrome, Firefox, Edge, Safari).  
- No external libraries required.  
