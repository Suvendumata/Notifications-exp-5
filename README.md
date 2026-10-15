# Exp-5 Android Notification Demo

## Objective

To develop an Android application that demonstrates how to display notifications using Kotlin.

---

## Concept

Android Notifications are used to inform users about important events even when the application is not open. When the notification is tapped, it opens another activity in the application.

---

## Technology Used

- Kotlin
- Android Studio
- Android SDK
- NotificationManager
- NotificationCompat
- PendingIntent

---

## Scenario

The application contains a button named **Show Notification**. When the user clicks the button, a notification is displayed. Tapping the notification opens the second activity.
## 📁 Project Structure

```text
Notifications-exp-5/
├── app/
│   └── src/
│       └── main/
│           ├── java/
│           │   └── your_package_name/
│           │       ├── MainActivity.kt
│           │       └── SecondActivity.kt
│           ├── res/
│           │   ├── layout/
│           │   │   ├── activity_main.xml
│           │   │   └── activity_second.xml
│           │   ├── drawable/
│           │   ├── mipmap/
│           │   └── values/
│           └── AndroidManifest.xml
├── screenshots/
│   ├── activity_main_design.png
│   ├── activity_second_design.png
│   ├── Screenshot 2026-08-07 195734.png
│   └── Screenshot 2026-08-07 195816.png
├── gradle/
│   └── wrapper/
├── build.gradle.kts
├── settings.gradle.kts
├── gradle.properties
├── gradlew
├── gradlew.bat
├── .gitignore
└── README.md
```


## Screenshots

### 1. Main Activity Design

![Main Activity Design](screenshots/activity_main_design.png)

---

### 2. Second Activity Design

![Second Activity Design](screenshots/activity_second_design.png)

---

### 3. Main Screen Output

![Main Screen Output](screenshots/Screenshot%202026-08-07%20195734.png)


---

### 4. Second Screen Output

![Second Screen Output](screenshots/Screenshot%202026-08-07%20195816.png)


---

## Name & USN Verification

Name: Suvendu Mata

USN: 25MCAR0136

## Conclusion

This experiment demonstrates how to create and display Android notifications using Kotlin and how a notification can be used to navigate between activities.
