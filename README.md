# React Native App

A beautiful mobile application for built with React Native, Expo, TypeScript, and NativeWind (Tailwind CSS for React Native).

## 🚀 Features

- Modern React Native with Expo
- TypeScript for type safety
- NativeWind (Tailwind CSS) for styling
- Expo Router for navigation
- Responsive design
- Splash screen with auto-navigation
- Onboarding flow

## 🛠️ Tech Stack

- **Framework:** React Native with Expo
- **Language:** TypeScript
- **Styling:** NativeWind (Tailwind CSS v3)
- **Navigation:** Expo Router (file-based routing)
- **Package Manager:** npm

## 📋 Prerequisites

Before running this project, ensure you have:

- Node.js (v16 or higher)
- Expo CLI installed globally
- Android Studio (for Android emulator)
- Xcode (for iOS simulator, macOS only)
- Git

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd coffee-shop-app

## ⚠️ Common Issues & Solutions

1. ### NativeWind Configuration Challenges
- **Problem**: Only Tailwind CSS version 3 is compatible with NativeWind.

- **Solution**: Ensure correct versions, e.g **npm install nativewind@latest npm install tailwindcss@^3.0.0**

2. ### Android Emulator Performance
- **Problem**: Low RAM causes emulator to run slowly or crash.

- **Option A**: Use Physical Device
- **Option B**: Optimize Emulator Settings, Reduce RAM allocation to 2048MB, Use lower resolution device (Pixel 3 instead of Pixel 6)
