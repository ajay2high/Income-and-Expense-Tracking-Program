# Income-and-Expense-Tracking-Program
This project is a Python program for tracking income and expenses. It allows users to add, view, and summarize transactions. I learned basic Python such as loops, lists, conditions, and file handling. I also used AI to help with ideas and debugging, but the program may still have some limitations.

## ✨ Features

- Add income records
- Add expense records
- View transaction history
- Calculate total income and expenses
- Show current balance
- Automatic file saving
- Simple terminal-based interface

- # 💰 Income and Expense Program

โปรแกรมบันทึกรายรับ-รายจ่ายแบบง่ายด้วย Python สามารถเพิ่มรายการรายรับ รายจ่าย ดูประวัติทั้งหมด และสรุปยอดคงเหลือได้ พร้อมบันทึกข้อมูลลงไฟล์อัตโนมัติ

## 🛠️ วิธีการติดตั้ง (Installation)

### 1. ติดตั้ง Python

ดาวน์โหลด Python ได้ที่:

https://www.python.org

ติดตั้งตามขั้นตอนปกติ และอย่าลืมติ๊ก

**"Add Python to PATH"**

### 2. ตรวจสอบการติดตั้ง

เปิด Command Prompt (CMD) แล้วพิมพ์

```bash
python --version
```

หากแสดงหมายเลขเวอร์ชัน แสดงว่าพร้อมใช้งานแล้ว

### 3. ไม่ต้องติดตั้งไลบรารีเพิ่มเติม

โปรแกรมนี้ใช้เฉพาะโมดูลมาตรฐานของ Python (`os`) เท่านั้น

---

## ▶️ วิธีการใช้งาน (How to Use)

รันโปรแกรมด้วยคำสั่ง

```bash
python main.py
```

จากนั้นจะปรากฏเมนูหลัก

```text
1 = Add Income
2 = Add Expense
3 = View All Records
4 = Show Summary
5 = Exit Program
```

### เมนูต่าง ๆ

**1. Add Income**

* เพิ่มรายการรายรับ
* กรอกจำนวนเงินที่ได้รับ
* ระบบจะบันทึกข้อมูลอัตโนมัติ

**2. Add Expense**

* เพิ่มรายการรายจ่าย
* กรอกจำนวนเงินที่ใช้จ่าย
* ระบบจะบันทึกข้อมูลอัตโนมัติ

**3. View All Records**

* แสดงรายการรายรับและรายจ่ายทั้งหมด
* แสดงจำนวนเงินของแต่ละรายการ

**4. Show Summary**

* แสดงยอดรายรับรวม
* แสดงยอดรายจ่ายรวม
* คำนวณยอดคงเหลือ (Balance)

**5. Exit Program**

* ออกจากโปรแกรม

---

## 💡 หมายเหตุ

* โปรแกรมทำงานผ่าน Terminal / Command Prompt
* ข้อมูลถูกเก็บไว้ในไฟล์ `data.txt`
* สามารถเปิดใช้งานใหม่ได้โดยข้อมูลเดิมยังคงอยู่
* หากยังไม่มีไฟล์ `data.txt` โปรแกรมจะสร้างให้อัตโนมัติเมื่อมีการบันทึกข้อมูลครั้งแรก

# 💰 Income and Expense Program

A simple Income and Expense Tracker built with Python. Users can record income, expenses, view transaction history, and check their financial summary. All data is automatically saved to a text file.

## 🛠️ Installation

### 1. Install Python

Download Python from:

https://www.python.org

Install it normally and make sure to check:

**"Add Python to PATH"**

### 2. Verify Installation

Open Command Prompt and run:

```bash
python --version
```

If a version number appears, Python is installed successfully.

### 3. No Additional Libraries Required

This project only uses Python's built-in module (`os`).

---

## ▶️ How to Use

Run the program with:

```bash
python main.py
```

The main menu will appear:

```text
1 = Add Income
2 = Add Expense
3 = View All Records
4 = Show Summary
5 = Exit Program
```

### Menu Options

**1. Add Income**

* Record a new income transaction
* Enter the amount received
* The data will be saved automatically

**2. Add Expense**

* Record a new expense transaction
* Enter the amount spent
* The data will be saved automatically

**3. View All Records**

* Displays all income and expense transactions
* Shows the amount for each record

**4. Show Summary**

* Calculates total income
* Calculates total expenses
* Displays the current balance

**5. Exit Program**

* Closes the application

---

## 💡 Notes

* The program runs in the terminal/command line.
* All records are stored in `data.txt`.
* Previous data remains available after reopening the program.
* If `data.txt` does not exist, it will be created automatically when the first transaction is saved.

