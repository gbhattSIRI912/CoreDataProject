# 📱 Simple Core Data Project

A beginner-friendly iOS app built using UIKit and Core Data to demonstrate persistent storage of user information. The app allows users to add, edit, and delete employee data, all displayed neatly in a `UITableView`.

## 📝 Description

This project is a simple demonstration of how to use Core Data in a UIKit-based app. It stores user data including:

- Name
- Email
- Technology
- Employee ID

Users can:

- Add new user details
- View saved data in a table view
- Edit existing entries
- Delete entries directly from the list

## 🚀 Features

- Persistent storage using Core Data
- Interactive `UITableView` to display user data
- Ability to update and remove records
- UI built using Storyboard
- Clean and beginner-friendly architecture

## 🧰 Requirements

- macOS: 15.3
- Xcode: 16.2.1
- iOS: 15.0+
- Swift: 5.0+

## 📸 Screenshots

| Home View |
|-----------|
| ![Simulator Screenshot - iPhone 16 Pro - 2025-04-12 at 10 06 52](https://github.com/user-attachments/assets/934b6985-c1ad-40c7-8236-fae0bf1d3971)
 ![Simulator Screenshot - iPhone 16 Pro - 2025-04-12 at 10 07 17](https://github.com/user-attachments/assets/9847cc52-1d90-47c2-8ea0-ae711e2226ba)
![Simulator Screenshot - iPhone 16 Pro - 2025-04-12 at 10 07 31](https://github.com/user-attachments/assets/5e5fec91-3af5-47da-825a-e36d65b775b0)
![Simulator Screenshot - iPhone 16 Pro - 2025-04-12 at 10 07 34](https://github.com/user-attachments/assets/4db19d0e-6a06-4f85-b440-eea9b24e51bc)
|

> 📌 Add your screenshot in the `Screenshots/` folder and name it `home_view.png`, or update the filename above accordingly.

## 🛠️ Project Structure

- `AppDelegate.swift` — Contains Core Data stack (`persistentContainer`)
- `ViewController.swift` — Main view controller with logic to display, update, and delete user data
- `Storyboard` — UI components such as text fields, buttons, and table view
- `User+CoreDataClass.swift` & `User+CoreDataProperties.swift` — Core Data entity class

## 📦 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/gbhattSIRI912/CoreDataProject.git
