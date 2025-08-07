# 🏃‍♂️ Fitness Tracker App

A React Native app to track your fitness activity — including daily steps, calories, and more. Built with SQLite and Firebase, this app stores your progress, supports custom goals, and offers a clean, gradient-based UI using Tailwind-inspired styling.

---

## 🧩 Key Features

- Track daily steps, calories, and personal health metrics
- Persist progress with SQLite + AsyncStorage
- Smooth navigation and onboarding flow
- Context-based state management
- Firebase-ready architecture
- Offline-first support
- Dark/light theme support

---

## 🚀 Getting Started

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/fitness-tracker-app.git
cd fitness-tracker-app
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run the App
```bash
npx react-native run-android
# or
npx react-native run-ios
```

---

## 🧱 Folder Structure
```
.
├── android/                   # Android-specific code
├── ios/                      # iOS-specific code
├── src/
│   ├── assets/               # Fonts, images, icons
│   ├── components/           # Shared UI components
│   ├── configs/              # App-level configuration
│   ├── constants/            # Static values
│   ├── contexts/             # App-wide Context Providers
│   │   ├── LanguageContext.jsx
│   │   ├── StepsTrackingContext.jsx
│   │   └── themeContext.jsx
│   ├── dbHelpers/            # SQLite helpers
│   │   ├── StepsHelper.jsx
│   │   └── stepsHelper.js
│   ├── hooks/                # Custom React hooks
│   │   ├── useAds.jsx
│   │   ├── usePersonal.jsx
│   │   └── useSteps.jsx
│   ├── layouts/              # Layout components
│   ├── navigations/          # Stack and tab navigators
│   ├── screens/              # App screens
│   │   ├── FAQs.jsx
│   │   ├── Home.jsx
│   │   ├── OnBoard.jsx
│   │   ├── Register.jsx
│   │   ├── Settings.jsx
│   │   └── Tracker.jsx
│   └── ui-components/        # Buttons, cards, icons
├── App.tsx                   # Main entry point
└── ...
```

---

## 🧠 State Management

Using Context API for global state:

- `StepsTrackingContext`: Handles step data and logic
- `ThemeContext`: Dark/light mode
- `LanguageContext`: Multi-language support (planned)

---

## 🧬 Custom Hooks

- `useSteps`: Manages SQLite step data
- `usePersonal`: Loads user details (age, gender, goal)
- `useAds`: [Future] AdMob or rewarded video integration

---

## 🗃️ Database Helpers

- `StepsHelper`: Insert, read, delete step data
- `PersonalHelper`: Save/load user profile metrics

---

## 📱 Screens

| Screen    | Purpose                            |
|-----------|------------------------------------|
| OnBoard   | First-time intro to app            |
| Register  | Capture personal details           |
| Home      | Step counter and dashboard         |
| Tracker   | Graphs and history of activity     |
| Settings  | App settings and theme/language    |
| FAQs      | Help and common questions          |

---

## 📦 Dependencies

Includes essential packages:

- axios
- moment, dayjs
- @react-navigation/native, stack, bottom-tabs
- @react-native-async-storage/async-storage
- react-native-sqlite-storage
- react-native-safe-area-context, gesture-handler, screens
- react-native-linear-gradient
- react-native-wind (Tailwind CSS-like styling)
- react-native-heroicons, react-native-svg
- react-native-firebase/app
- lottie-react-native
- uuid, react-native-rename

---

## 🖋 Fonts

- Poppins
- Montserrat

---

## 🔮 Future Improvements

- Google Fit / Apple HealthKit Integration
- Firebase Authentication & Cloud Sync
- Weekly/Monthly analytics
- Language translations (i18n)
- Notification reminders for activity

---

## 🙋 Author

**Abdul Rehman**  
Full Stack Developer (React Native, PHP, Node.js)

- 🌐 [LinkedIn](https://www.linkedin.com/in/rehmanthedeveloper/)
- 💼 [Portfolio](https://me.infinitibytech.com/)
- 📫 Email: hi@rehman.developer@outlook.com
