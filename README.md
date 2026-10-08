# Iron Ledger

**Train consistently. Track intelligently. Get stronger.**

Iron Ledger is a personal fitness tracker designed to help you log workouts, build routines, monitor your progress, and keep your training history organized.

🌐 **[Open Iron Ledger](https://raagasura1.github.io/Iron-Ledger/)**

## ✨ Features

### 🏋️ Workout

* Start and log workouts.
* Choose between Gym, Calisthenics, and Cardio training modes.
* Use predefined routines or create your own training sessions.
* Record exercises, sets, repetitions, weights, and other relevant measurements.
* Log workouts you have already completed.

### 📋 History

* Review previous workouts.
* Browse your training history.
* Revisit recorded exercises and workout details.

### 📈 Progress

* Monitor workout statistics and training consistency.
* Track personal records and progress over time.
* Review your training history to understand your development.

### 💪 Exercises

* Browse the exercise library.
* Find exercises and manage custom exercises.

### 📏 Body

* Record body measurements.
* Monitor changes in your measurements over time.

### 💾 Data Management

* Export workout history as CSV.
* Export body measurements as CSV.
* Create a complete JSON backup.
* Restore your data from a backup.

---

## 🚀 Getting Started

1. Open [Iron Ledger](https://raagasura1.github.io/Iron-Ledger/).
2. Choose your preferred training mode.
3. Start a workout, select a routine, or log a previously completed workout.
4. Add exercises and record your training data.
5. Finish your workout and review your progress in the History and Progress sections.

You can use Iron Ledger directly in your browser without installing anything.

---

## 📱 Installation on Android

Android users can install Iron Ledger using the APK provided in this repository.

1. Open the [Iron Ledger GitHub repository](https://github.com/RaagAsura1/Iron-Ledger).
2. Find **Iron Ledger.apk** in the repository's file list.
3. Download the APK to your Android phone.
4. Open the downloaded file.
5. If prompted, allow your browser or file manager to install apps from this source.
6. Follow the on-screen instructions to complete the installation.
7. Open Iron Ledger and start tracking your workouts.

**Security note:** Android may warn you when installing an APK downloaded outside the Google Play Store. Only install APKs from sources you trust.

Alternatively, you can use the [web version](https://raagasura1.github.io/Iron-Ledger/) directly in your mobile browser.

---

## 🍎 Installation on iPhone (iOS)

iOS users can create a Home Screen shortcut to a working Iron Ledger artifact using the Claude app.

Unlike Android, iOS does not allow you to install this APK. Follow the steps below to set up the web-based version on your iPhone.

### Step 1: Install Claude

1. Open the Apple App Store.
2. Search for **Claude** by Anthropic.
3. Install the app and sign in.

### Step 2: Download the HTML file

1. Open the [Iron Ledger GitHub repository](https://github.com/RaagAsura1/Iron-Ledger).
2. Select `index.html`.
3. Download the file to your iPhone.

Make sure you download the actual HTML file, not a screenshot or a copy of the source code displayed as text.

### Step 3: Create your Iron Ledger artifact in Claude

1. Open the Claude app.

2. Start a new chat.

3. Upload the downloaded `index.html` file.

4. Copy and send Claude the following prompt:

   > Create a new, fully functional Claude artifact named "Iron Ledger" from this uploaded HTML file. Preserve the complete design, all existing features, workout tracking functionality, sample data, and data persistence. Make sure all buttons, tabs, forms, charts, and other interactive elements work as intended. Do not remove, simplify, or replace any existing functionality. Make the artifact accessible through a published URL that I can open on my iPhone and add to my Home Screen. Do not just display the HTML source code; run it as a working interactive application.

5. Allow Claude to create the artifact.

6. Test the application. Check that the tabs, workout logging, routines, history, progress tracking, and settings work as expected.

7. Publish the artifact if prompted to do so.

8. Copy the published artifact URL.

**Important:** Claude may not reproduce every feature of the original application exactly. Test the published version before using it as your primary workout tracker. Data stored in the original browser-based app may not automatically transfer to the Claude artifact.

### Step 4: Create an Iron Ledger shortcut

Use Apple's built-in **Shortcuts** app to add an icon to your iPhone Home Screen.

1. Open the **Shortcuts** app.
2. Tap the **+** button to create a new shortcut.
3. Tap **Add Action**.
4. Search for **Open URLs** and select the action.
5. Paste the published Iron Ledger artifact URL from Claude into the URL field.
6. Tap the shortcut name at the top and rename it **Iron Ledger**.
7. Open the shortcut's details or sharing menu and select **Add to Home Screen**. The exact menu location may vary by iOS version.
8. Set the Home Screen name to **Iron Ledger**.
9. Choose a custom icon if desired.
10. Tap **Add** to finish.

You should now see an Iron Ledger icon on your iPhone Home Screen. Tap it to launch the published artifact.

**Please note:** This creates a shortcut to a web-based application, not a native iOS app. An internet connection may be required, and the availability of your workout data depends on the artifact's storage implementation.

---

## 🔐 Back Up Your Data

Your workout history is valuable. Back it up regularly.

1. Open Iron Ledger.
2. Go to **Settings**.
3. Find the **Export and backup** section.
4. Select **Full backup (JSON)**.
5. Save the downloaded backup file somewhere safe.

To restore your data, open Settings and select **Restore backup**, then choose your saved JSON backup.

You can also export workout history and body measurements as CSV files for use in spreadsheet applications.

### Important data-storage information

The original web application stores data in your browser's local storage. This means:

* Your data does not automatically synchronize between devices.
* Different browsers may have separate copies of your data.
* Clearing browser data may remove your saved workouts.
* The original web version and a Claude artifact may store data separately.

**Always create a backup before switching devices, clearing browser data, or moving to another version of Iron Ledger.**

---

## 🛠️ Technology

Iron Ledger is distributed as a web application, with an Android APK also provided in the repository.

* **Web application:** HTML, CSS, and JavaScript.
* **Web hosting:** GitHub Pages.
* **Android:** APK distribution.
* **iOS:** Web-based artifact with a Home Screen shortcut.

---

## 🐛 Feedback and Feature Requests

Found a bug or have an idea for an improvement?

Open an issue in the [Iron Ledger GitHub repository](https://github.com/RaagAsura1/Iron-Ledger/issues).

Contributions and suggestions are welcome.

---

*Iron Ledger — Train consistently. Track intelligently. Get stronger.*
