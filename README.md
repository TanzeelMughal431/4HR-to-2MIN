# 4HR to 2MIN - ArwenSOC Flow 🚀

An automated QRadar report cleaner and SOC team management tool designed to reduce a tedious 4-hour manual triage task down to just 2 minutes.

---

## 🛠️ How to Run & Use the App

1. **Access the App:** Open the hosted link in any modern web browser (Chrome, Edge, Firefox).
2. **Team Login:** 
   * Enter your authorized team email in the login screen.
   * If your email is in the authorized whitelist, you will be granted access to the app interface.
3. **QRadar Report Cleaning:**
   * Go to **"1. Upload Excel / CSV File"** and select your raw QRadar report (`.xlsx`, `.xls`, or `.csv`).
   * Click **"Clean and Process Data"**.
   * View real-time **Statistics Dashboard** (High, Medium, and Low severity counts based on custom IFS rules) and color-coded keyword previews.
   * Click **"Download Cleaned Excel File"** to export the structured report with exact column widths and custom naming (`lexel cleaner`).

---

## 👑 Admin Panel & Management Guide

If you log in with an authorized admin email, an **"Open Admin Panel & Reports"** button will appear at the top of the dashboard.


### **Admin Panel Features:**
2. **Authorized Emails Management:**
   * Add new team member emails to grant them access or remove existing ones dynamically.
3. **Team Activity & Attendance Reports:**
   * Automatically tracks user `LOGIN` and `LOGOUT` timestamps.
   * Admins can download structured activity reports for the **Day**, **Week**, or **Month** as Excel files with one click.
4. **Switch Mode:**
   * Use the **"Switch to App Mode"** button inside the admin panel to easily jump back to the main report cleaner interface.
