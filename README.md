

# 📱 Student Record System (Android)

## 📌 Overview

The **Student Record System** is an Android-based application developed to manage student information in a structured and efficient manner. The application enables users to perform essential data management operations such as creating, viewing, updating, and deleting student records.

This project demonstrates the implementation of a mobile-based database system using local storage and a clean user interface.

---

## 🎯 Objectives

* To design a simple and efficient student data management system
* To implement CRUD (Create, Read, Update, Delete) operations
* To utilize a local database for persistent data storage
* To develop a user-friendly Android application

---

## 🛠️ Technologies Used

* **Programming Language:** Java / Kotlin
* **Development Environment:** Android Studio
* **Database:** SQLite
* **User Interface:** XML Layouts

---

## 📂 Project Structure

```
Student-Record-System/
│── app/
│   ├── java/com/example/...       # Application source code
│   ├── res/                      # UI resources (layouts, drawables, values)
│   └── AndroidManifest.xml       # App configuration
│
│── Gradle Scripts                # Build configuration files
│── build.gradle
```

---

## ⚙️ System Requirements

* Android Studio (latest stable version recommended)
* Android SDK
* Java Development Kit (JDK 8 or higher)
* Android Emulator or Physical Device

---

## ▶️ Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/tajulislamsaidul/Student-Record-System.git
```

### Step 2: Open the Project

* Launch **Android Studio**
* Select **Open an Existing Project**
* Navigate to the cloned repository folder and open it

### Step 3: Gradle Synchronization

* Allow Android Studio to sync Gradle files
* Resolve any dependency prompts if required

### Step 4: Configure Device

* Connect a physical Android device with USB debugging enabled
  **or**
* Launch an emulator using AVD Manager

### Step 5: Build and Run

* Build the project using **Build > Make Project**
* Run the application using the **Run** button

---

## 🗄️ Database Design

The application uses a **local SQLite database** to store student information. Data is maintained within the device storage and persists between sessions.

Typical attributes include:

* Student ID
* Student Name
* Department / Course
* Additional relevant details

---

## 🔧 Key Functionalities

* Insert new student records
* Retrieve and display stored records
* Update existing entries
* Delete records from the database

---

## 📌 Notes

* The application is intended for academic and learning purposes
* The system operates entirely offline using local storage
* The architecture follows standard Android development practices

---