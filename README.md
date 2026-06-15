# SpendScope – Modern Personal Budget Tracker

## Overview

SpendScope is a modern Android Personal Budget Tracker application developed in Kotlin. The application helps users manage their finances by tracking expenses, setting spending goals, viewing spending trends, and earning rewards for maintaining good budgeting habits.

The app was developed as part of the **OPSC6311/w – Open-Source Coding (Introduction)** Portfolio of Evidence (POE) at The Independent Institute of Education (IIE).

---

## Features

### User Authentication
- User registration
- Secure login using username and password
- Session management

### Expense Management
- Add expenses with:
  - Amount
  - Date
  - Description
  - Category
- View all expenses
- Filter expenses by date range
- Edit and delete expenses

### Categories
Users can create and manage custom expense categories such as:
- Groceries
- Entertainment
- Transport
- Utilities
- Education

### Budget Goals
Users can:
- Set minimum monthly spending goals
- Set maximum monthly spending goals
- Set category spending limits
- Track progress toward goals

### Expense Receipt Photos
- Attach receipt images to expenses
- Store images locally
- View stored receipts

### Reports and Analytics
The app provides:
- Spending reports
- Category summaries
- Monthly analysis
- Spending insights

### Graphs and Visualisations
Users can view:
- Spending trends over time
- Spending per category
- Minimum and maximum budget goals on graphs

The graphs are implemented using **MPAndroidChart**.

### Progress Dashboard
The dashboard displays:
- Total spending
- Remaining budget
- Spending progress
- Categories exceeding limits

Overspending categories are highlighted visually to help users stay within budget.

---

## Gamification

SpendScope introduces gamification to make budgeting more engaging.

Users can earn:

- Bronze Saver Badge
- Silver Saver Badge
- Gold Saver Badge
- Consistency Rewards

Badges are awarded when users:
- Stay within budget
- Consistently log expenses
- Reach savings goals

---

# Additional Features

## 1. Reminders

Users can create reminders for:

- Paying bills
- Recording expenses
- Saving money
- Monthly budget reviews

This feature helps users develop good financial habits.

---

## 2. Spending Reports

SpendScope generates reports that help users:

- Analyse their spending habits
- Identify expensive categories
- Compare spending across periods
- Make informed budgeting decisions

---

# User Interface

The application uses a modern Material Design-inspired user interface with:

- Consistent colours
- Custom icons
- Rounded cards and buttons
- Responsive layouts
- Easy navigation

The UI was designed to be intuitive and user-friendly.

---

# Technologies Used

| Technology | Purpose |
|-----------|---------|
| Kotlin | Android development |
| SQLite | Local data storage |
| MPAndroidChart | Graphs and charts |
| Android SDK | Mobile development |
| Material Components | User interface |
| Git | Version control |
| GitHub | Source code hosting |
| GitHub Actions | Automated builds |

---

# Database

The application uses SQLite to store:

- User accounts
- Categories
- Expenses
- Budget goals
- Badges
- Reports
- Reminders

All data is stored locally on the device.

---

# GitHub and Version Control

Git was used throughout the development process to:

- Track changes
- Manage versions
- Maintain backups
- Collaborate effectively

The project is hosted on GitHub.

Regular commits were made during development to document progress and maintain version history.

---

# GitHub Actions

GitHub Actions was used to automate the build process.

The workflow automatically:

- Builds the Android project
- Verifies code compilation
- Runs automated tests
- Ensures the application can be built successfully on environments other than the developer's machine

This improves reliability and code quality.

# Demonstration Video

YouTube Video Link:

**[Insert your unlisted YouTube link here]**

---

# Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/SpendScope.git
```

2. Open the project in Android Studio.

3. Sync Gradle files.

4. Build and run the app on:

- Android Emulator, or
- Physical Android device.

---

# Project Structure

```
app/
├── activities/
├── adapters/
├── database/
├── managers/
├── models/
├── utils/
├── res/
│   ├── drawable/
│   ├── layout/
│   ├── mipmap/
│   └── values/
└── AndroidManifest.xml
```

---

# Future Improvements

Possible future enhancements include:

- Cloud synchronization
- Export reports to PDF
- Dark mode
- AI-powered spending recommendations
- Biometric authentication
- Multi-device synchronization

 Author

**VHUTSHILO MUGWEDI**

IIE Diploma in Information Technology in Software Development

Module: **OPSC6311/w – Open-Source Coding (Introduction)**

Rosebank College

2026

---

# License

This project was developed for academic purposes as part of the OPSC6311/w Portfolio of Evidence.
