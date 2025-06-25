# Online Banking System – Python GUI Application with Admin Panel

A desktop-based **Banking Management System** built using Python and **CustomTkinter**, featuring user registration, multiple account types (Saving, Checking, Loan), interest & balance handling, and a secured **Administrator Panel** to manage the system.

---

## 🎯 Key Features

### 👨‍💼 User Portal (Customer Side)

-  User Sign-Up / Login with password
-  Saving Account:
  - Interest on deposits (20%)
  - Withdrawals with validations
-  Checking Account:
  - Overdraft protection up to Rs. 10,000
-  Loan Account:
  - Dynamic interest rates based on loan size
  - Duration handling and penalty for late repayment
-  Transaction History stored in file
-  Forgot Password support
-  Balance Enquiry with timestamp

### 🛠️ Administrator Panel

-  Admin Login using secure credentials from `admin.txt`
-  Change Admin Password
-  View all registered user files in the system
-  Access `users/` folder containing all user records

---

## 🖼️ GUI Overview

- Built using **CustomTkinter**
- Styled message dialogs using `CTkMessagebox`
- Interactive pop-ups for:
  - Errors (e.g. incorrect login)
  - Success messages (e.g. deposit confirmed)
  - Transaction summaries

---

## 🔐 File Storage Structure

Each user file is a `.txt` file structured as a Python list:
```python
[
  {username: password},
  {saving_accounts},
  {checking_accounts},
  {loan_accounts},
  {
    "Saving": [...],
    "Checking": [...],
    "Loan": [...]
  }
]
```

admin.txt 
```python 
["admin_id", "admin_password"]
```
---
## 💻 Getting Started

### Run Locally
```python
https://github.com/Muhammad-Zunain/Online-Bank-System.git
cd Online-Bank-System
pip install customtkinter CTkMessagebox
python RUN.py
```
---
## 📸 Screenshots

#### Main Interface
![image](https://github.com/user-attachments/assets/1618d097-ca86-47de-9819-a8d3fc2eddf8)

#### Select User Interface
![image](https://github.com/user-attachments/assets/fae8a23b-23b6-49b6-8d19-a6e4570b5672)

#### Sign Up
![image](https://github.com/user-attachments/assets/723c5433-c9c1-4f7c-9a93-aac9b3afba6f)

#### Account Creation
![image](https://github.com/user-attachments/assets/a6e39a35-a056-4dea-9e4e-29e0ef811954)

#### Transaction History
![image](https://github.com/user-attachments/assets/0026037e-e961-44d3-a639-04f65793a906)




