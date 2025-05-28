# Gamified Learning App (Kotlin Multiplatform)

## 📱 Overview

This is a cross-platform mobile app built with **Kotlin Multiplatform** and **Jetpack Compose Multiplatform** that offers **daily gamified learning challenges**. The app aims to personalize the learning experience using a Small Language Model (SLM) and provide smooth navigation with a beautiful UI on both Android and iOS.

---

## 🚀 Features

- Cross-platform UI using Jetpack Compose Multiplatform  
- Challenge List and Detail screens  
- State-based navigation with Kotlin sealed classes  
- Basic challenge data model with sample challenges  
- Future plans for login/signup, gamification (streaks, XP, badges), progress tracking  
- Offline support planned with SQLDelight  
- Personalized recommendations via Small Language Model (SLM)

---

## 🛠 Tech Stack

- Kotlin Multiplatform (KMP)  
- Jetpack Compose Multiplatform  
- SQLDelight (planned for local caching)  
- Ktor (for future network calls)  
- State-based navigation (shared between Android and iOS)  

---

## 📁 Project Structure

composeApp/
├── src/commonMain/kotlin/com/dailydevchallenge/androidapp/
│ ├── App.kt
│ ├── model/Challenge.kt
│ ├── ui/
│ │ ├── ChallengeListScreen.kt
│ │ ├── ChallengeDetailScreen.kt
│ │ └── components/ChallengeCard.kt
│ ├── navigation/AppScreen.kt
│ └── data/DummyChallenges.kt
├── androidApp/ # Android entry point
└── iosApp/ # iOS entry point



---

## 💡 How to Run

1. Clone the repo  
2. Open the project in IntelliJ IDEA or Android Studio with Kotlin Multiplatform support  
3. Run the Android app on an emulator or device  
4. Run the iOS app using Xcode or iOS simulator (requires Mac)  

---

## 🔮 Roadmap / Planned Features

- Login and Signup screens (cross-platform)  
- Gamified challenge system with streaks, XP, badges  
- Challenge progress tracking and analytics  
- Integration of Small Language Model (SLM) for personalized challenges  
- Offline data caching with SQLDelight  
- Backend sync or local sync features  

---

## 📬 Contact

For questions or feedback, reach out at:  
**kirankumarhs29@gmail.com**
