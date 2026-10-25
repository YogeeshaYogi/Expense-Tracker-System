# 💰 Smart Expense Tracker — Android Application(SMS Parsing)

An Android expense-tracking application designed to help users manage and organize financial transactions. The project explores SMS-based transaction detection to reduce manual expense entry and simplify personal expense tracking.

## ✨ Key Features

- **SMS-Based Transaction Detection:** Identify relevant financial messages using transaction keywords.
- **Financial Message Filtering:** Filter transaction-related SMS messages and ignore unrelated messages.
- **Expense Tracking:** Organize financial transaction details for easier expense monitoring.
- **Android User Interface:** Build user-facing screens using Jetpack Compose.
- **Firebase Integration:** Explore cloud-based storage and transaction data management.
- **Transaction Validation:** Apply keyword-based filtering to identify potentially relevant financial messages.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Kotlin | Android application development |
| Jetpack Compose | Modern Android user interface |
| Firebase | Cloud database integration |
| Android SMS APIs | Accessing and processing SMS messages |

## ⚙️ How It Works

1. The application processes SMS messages that may contain financial transactions.
2. It checks messages for financial indicators, such as transaction keywords and currency references.
3. Relevant messages are filtered for transaction-related information.
4. Transaction details can be organized for expense tracking.
5. Firebase integration can support cloud-based transaction data management, depending on the configured implementation.

## 🔐 Permissions and Privacy

SMS access requires explicit Android runtime permissions.

- Request SMS permissions only when needed.
- Process financial messages according to the application's intended functionality.
- Avoid collecting or storing unnecessary personal information.
- Protect financial transaction data and Firebase access credentials.

**Privacy note:** SMS messages can contain sensitive information. Handle them securely and explain clearly to users why access is required.

## 🚀 Getting Started

### Prerequisites

- Android Studio
- Android SDK
- Kotlin development support
- An Android device or emulator
- Firebase project configuration, if using Firebase features

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YogeeshaYogi/Expense-Tracker-System.git
   ```

2. Open the project in Android Studio if the repository contains the complete Android project source.
3. Configure the required Android SDK and Gradle dependencies.
4. Configure Firebase if required by the application.
5. Run the application on a compatible Android device or emulator.

> **Note:** The current repository contains compiled `.dex` files rather than a complete Android Studio project. You should upload the original source code and Gradle configuration files to enable a standard build from source.

## 🎯 Project Objective

The objective is to simplify personal expense management by exploring automated transaction identification from financial SMS messages, reducing manual data entry, and organizing transaction information in an Android application.

## 🔗 Repository

[View Smart Expense Tracker on GitHub](https://github.com/YogeeshaYogi/Expense-Tracker-System)

## 👨‍💻 Developer

**Yogeesha E**

GitHub: [YogeeshaYogi](https://github.com/YogeeshaYogi)
