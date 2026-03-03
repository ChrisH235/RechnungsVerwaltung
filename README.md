# 📑 RechnungsVerwaltung – Invoice & Reminder App (Python Desktop)

A modular desktop application built with Python to manage digital invoices, track payment status, categorize expenses and handle due-date reminders.

---

## 🎯 Motivation

Digital invoices often get lost in email inboxes or download folders.  
Missed due dates can lead to late fees and poor financial overview.

This project provides a structured, local-first invoice management system.

---

## ✨ Core Features

- Add invoice with image upload
- Automatic image → PDF conversion
- Status tracking (Open / Paid / Reminder)
- Due-date & reminder-date handling
- Category system with filtering
- Double-click to open archived PDF
- Reminder check on application startup
- Local SQLite database

---

## 🛠 Tech Stack

Python • Tkinter • SQLite • Pillow • tkcalendar

---

## ▶️ Run

```bash
pip install -r requirements.txt
python main.py
