# 💈 Customer Appointment Booking System

A beginner-friendly Windows Forms application built using **C# (.NET Framework)** that allows a salon or barbershop to manage customer information and book appointments — all stored in RAM without using a database or file system.

---

## 🧩 Features

- 📇 Add new customers (first name, last name, phone number)
- 🆔 Automatically assign a unique ID to each customer
- 📆 Book appointments using a calendar (future dates only)
- ✂️ Choose from predefined salon services
- ✅ Validate customer ID and service selection
- 📋 View all appointments in a clear ListView (table)

---

## 🛠️ Technologies Used

- C# (.NET Framework)
- Windows Forms (Visual Studio Designer)
- ListView, ComboBox, MonthCalendar, TextBox
- Object-Oriented Programming (Classes, Lists, Validation)

---

## 📂 Project Structure

- `Customer` class → stores customer details (ID, name, phone)
- `Appointment` class → links service, customer, and selected date
- `List<Customer>` → stores all customers in memory
- `List<Appointment>` → stores all appointments in memory

---

## 🚀 How to Run

1. Clone this repository or download the `.zip`
2. Open the solution in **Visual Studio 2022**
3. Build and run the project (`F5`)
4. Add customers and book appointments using the UI

---

## ⚠️ Limitations

- ❌ No persistent storage — appointments are lost on app close
- ❌ No customer editing or deleting
- ❌ No overlapping appointment validation (yet)

---

## 🧠 What You’ll Learn (if you're a beginner)
(this is only if you try to do it yourself)

- Working with C# classes and lists
- Windows Forms UI and event-driven programming
- Managing input and data validation
- Structuring code for reusability and clarity

---

## 📌 Future Improvements (for expansion)

- Save/load data from a file or database
- Edit/delete appointments or customers
- Filter appointments by date or customer name
- Add login system for admin/staff

---

## 📄 License

This project is released under the MIT License. You are free to use and modify it for personal or educational purposes.

---

## ✍️ Author

Developed by Porsuq
Feel free to fork, share, and improve it ✨
- If I'm bothered enough, I may massively improve it with way better UI, work with actually saving it in a local database system and improving the application overall.

