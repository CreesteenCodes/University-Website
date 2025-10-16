# 🌐 University Website
* Frontend: HTML / CSS / JavaScript (Bootstrap used for responsiveness and quicker UI)
* Backend: Python (Flask)
* Database: MySQL (XAMPP). SQL script included to create database/tables and seed admin & instructor users.

# 🚀 How to run locally?
1. Install Python packages:
   ```bash
   pip install flask mysql-connector-python pandas openpyxl werkzeug
3. Start XAMPP and MySQL server.
4. In phpMyAdmin (or via CLI), create DB by running `create_db.sql`.
5. Put the project files into folder university-website.
6. Edit config section in `app.py` to set your MySQL username/password if needed.
7. Run `app.py`.
8. Open the IP address of your local computer with its given port in your browser.

# 🧾 Google Sheet Syncing
1. Enable Google Sheets API
* Go to Google Cloud Console.
* Create a project and enable Google Sheets API and Google Drive API.
* Create Service Account Credentials and download the credentials.json file.
* Share your Google Sheet with the service account email with Editor access.
2. In your virtual environment, install:
  ```bash
  pip install gspread oauth2client


# 🔐 Hashed Password
👉 To generate the hashed password, open a Python terminal and run:
```bash
from werkzeug.security import generate_password_hash
print(generate_password_hash("yourpassword"))







