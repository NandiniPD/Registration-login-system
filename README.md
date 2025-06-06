# Registration-login-system

# 🌐 Registration & Login System

A clean, responsive, and minimalistic web-based user registration and login system built using **HTML**, **CSS**, and **JavaScript** with **Google Sheets (via SheetDB)** as the backend.

---

## 🚀 Features

- 📝 Multi-step registration form
- 🔐 Secure login with password verification
- 📁 Document upload via Google Drive links (College ID, Aadhar, PAN)
- ✅ Validation and duplicate email check
- 🔄 Redirects after registration to login
- 🧠 Age auto-calculation based on Date of Birth
- 📦 Data stored in Google Sheets via SheetDB API

---

## 📁 File Structure

├── page_1(main).html # Main registration form (basic info)
├── page_2.html # Additional registration details
├── login.html # User login page
├── success.html # Registration success message + redirect to login page
├── dashboard.html # (Optional) Landing page post login

---

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend (API):** [SheetDB.io](https://sheetdb.io) (connects to Google Sheets)
- **Storage:** Google Sheets (no traditional database!)

---

## 🔧 How to Run Locally

1. Clone this repo:
   ```bash
   git clone https://github.com/yourusername/registration-login-system.git
   cd registration-login-system


   Open page_1.html in your browser.

No build tools. No installs. Just open and go.

🧠 To-Do / Future Enhancements
🛡️ Hashing passwords before storing

✉️ Add email verification

🧾 Admin dashboard to manage users

📱 Improve mobile UX further


