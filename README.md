# 💰 BudgetMate – Personal Finance Management App  

**BudgetMate** is a cross-platform mobile application built with **React Native**, **Expo**, and **Firebase** to help users manage their personal finances, track expenses, visualize spending, and achieve their budgeting goals.

---

## 🔧 Tech Stack  

### Frontend / Mobile  
- ⚛️ **React Native 0.81.4**  
- 📦 **Expo SDK 54**  
- 💨 **NativeWind (Tailwind CSS)**  
- 🧭 **React Navigation v7**  
- 🎨 **Expo Vector Icons & Lucide React Native**  
- 🔔 **React Native Toast Message**  

### Backend / Services  
- 🔥 **Firebase (Authentication + Firestore)**  
- ☁️ **EAS Build & Expo Dev Client**  

### Other Libraries  
- 🎚️ **Reanimated & Gesture Handler** for animations and gestures  
- 📊 **React Native Chart Kit** for visualizing spending trends  

---

## 📱 Features  

- ✅ **User Authentication** – Secure login and signup with Firebase  
- 💵 **Expense Tracking** – Add, update, delete daily expenses  
- 📊 **Charts & Insights** – Visualize income vs expenses  
- 🎨 **Modern UI** – Styled using Tailwind CSS with NativeWind  
- 🔔 **Toast Notifications** – Inform users of important actions  
- ⚙️ **Expo EAS Build Ready** – Seamless Android/iOS build pipeline  

---

## 📂 Project Structure  

```
BudgetMate-App/
├── app/ # App Router Screens (Home, Login, Dashboard, etc.)
├── components/ # Shared UI components (buttons, inputs, cards)
├── assets/ # Images, icons, fonts
├── android/ # Native Android project after prebuild
├── hooks/ # Custom React hooks (useAuth, useTheme, etc.)
├── context/ # Context Providers (AuthContext, ThemeContext)
├── services/ # API or Firebase service wrappers
├── tailwind.config.js # TailwindCSS config
├── package.json
└── README.md
```

### Explanation of Key Folders  

- **app/** – Screens for navigation (Login, Home, Dashboard, Add Expense).  
- **components/** – Reusable UI parts such as buttons, text fields, charts.  
- **assets/** – Static files like images, logos, and custom fonts.  
- **android/** – Native Android build output generated after `expo prebuild`.  
- **hooks/** – Custom hooks to manage app state or reusable logic.  
- **context/** – React Contexts for authentication, theme, or global state.  
- **services/** – Firebase/REST API service calls and helper functions.  
- **tailwind.config.js** – TailwindCSS configuration file for NativeWind.  

---

## ⚙️ Installation & Setup  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Shehara2007/BudgetMate
   cd BudgetMate-App

2. **Install dependencies**  
    ```bash
    npm install

3. **Install Expo Dev Client (if needed)**  
    ```bash
    npx expo install expo-dev-client

4. **Configure TailwindCSS (Make sure tailwind.config.js exists at the root:)**
    ```bash
    npx expo install expo-dev-client

---

## 🚀 Running the App

1. **Development (Expo Go or Dev Client)**  
    ```bash
   npx expo start

2. **Android Debug Build (locally)**  
    ```powershell
   cd android
    .\gradlew.bat assembleDebug

3. **Production Build with EAS**  
    ```bash
   eas build --platform android





