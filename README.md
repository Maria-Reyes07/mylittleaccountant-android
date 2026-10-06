# My Little Accountant

My Little Accountant is a personal finance mobile application designed to help users manage their everyday finances. Users can track income and expenses, manage bills, set savings goals, and monitor their available balance in one place.

## Features

* User registration and secure authentication
* Income and expense tracking
* Bill tracking and money set aside for bills
* Savings goals and progress tracking
* Available balance calculations
* Transaction search and filtering
* Financial tips related to loans, debt, and interest
* Password recovery
* CRUD functionality for financial records

## Technologies

### Android

* Java
* Android Studio
* Room Database
* REST APIs
* XML layouts

### Development & Deployment

* Git / GitLab / GitHub
* Microsoft Azure
* Azure Blob Storage

## Getting Started

### Prerequisites

To run the Android version, you will need:

* Android Studio
* Android SDK
* Java
* An Android emulator or physical Android device

## Android Setup

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/my-little-accountant.git
```

2. Open the project in **Android Studio**.

3. Allow Android Studio to sync the Gradle dependencies.

4. Create or select an Android emulator, or connect an Android device with USB debugging enabled.

5. Build and run the application using Android Studio.

## Project Structure

```text
My Little Accountant
├── Android
│   ├── UI
│   ├── Database
│   ├── DAO
│   ├── Entities
│   └── Utilities
```

## Security

User passwords are not stored as plaintext. The Android application uses salted PBKDF2 password hashing to securely store authentication credentials.

## Deployment

A signed Android release build was created and deployed using Microsoft Azure Blob Storage for testing and distribution.

## Author

**Maria Reyes**

Software Engineering Student | Mobile Application Developer

## License

This project was developed as a software engineering capstone project and is provided for educational and portfolio purposes.
