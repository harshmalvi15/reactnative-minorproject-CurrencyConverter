# 💱 Currency Converter App

A simple currency converter built with **React Native** and **TypeScript**. This app allows users to convert between different currencies using a predefined exchange rate. Designed with a user-friendly interface and informative snackbars for better user feedback.

---

## ✨ Features

- Convert entered amount to selected currency
- Error handling using `Snackbar` for missing or invalid input
- Responsive UI with clean design
- Built using **TypeScript** for better type safety

---

## 🛠️ Tech Stack

- [React Native](https://reactnative.dev/)
- [TypeScript](https://www.typescriptlang.org/)
- [Snackbar](https://www.npmjs.com/package/react-native-snackbar)

---

## 📁 Project Structure

CurrencyConverter/
├── android/
├── ios/
├── src/
│ ├── components/
│ │ └── CurrencyButton.tsx
│ ├── App.tsx
│ ├── constants.ts
│ └── ...
├── .eslintrc.js
├── .prettierrc.js
├── app.json
└── babel.config.js
---

## 🚀 Getting Started

### Prerequisites

- Node.js
- React Native CLI
- Android Studio / Xcode (for emulators)

### Installation

```bash
git clone https://github.com/your-username/currency-converter-app.git
cd currency-converter-app
npm install
npx react-native run-android # or run-ios
