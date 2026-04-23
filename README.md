# Student Record Management System

This is a comprehensive Android application designed to manage student records efficiently. The project is split into several modules that need to be merged into a single workspace for full functionality.

## Features
* Student data entry and management.
* Record synchronization between modules.
* User-friendly interface built with Android Studio.

## Installation & Setup

Follow these steps carefully to set up the project on your local machine.

### 1. Extract the Files
You must unzip the project files in the following specific order to ensure the file structure is correct:

1.  **Extract `Student Record System 1.rar`**: Create a main project folder (e.g., `Student-Record-Project`) and extract the contents of this file there first.
2.  **Extract `app 1.rar`**: Unzip this file and move its contents into the same main folder.
3.  **Extract `app 2.rar`**: Unzip this file and move its contents into the same main folder.

**Note:** Ensure all files and folders (from all three archives) are consolidated into a single root directory.

### 2. Open in Android Studio
1.  Launch **Android Studio**.
2.  Select **File > Open**.
3.  Navigate to the folder where you unzipped all the files and select the root folder.
4.  Wait for Android Studio to finish the **Gradle Sync**. (Ensure you have an active internet connection to download necessary dependencies).

### 3. Build and Run
1.  Once the sync is successful, click on the **Build** menu and select **Make Project**.
2.  Connect an Android device via USB or start an Emulator.
3.  Click the green **Run** button (or press `Shift + F10`) to install the app on your device.

## Prerequisites
* Android Studio Flamingo or newer.
* Android SDK (API level 30 or higher recommended).
* Gradle 7.0 or higher.

## Project Structure
* `Student Record System`: Main logic and database handling.
* `app 1`: Interface module / Component A.
* `app 2`: Interface module / Component B.
