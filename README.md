## 🧑‍💻 Author

Tanvir Hasan
Mobile App Developer (Flutter)
💡 Focused on clean, scalable, and pixel-perfect Flutter apps

# 🌐 Flutter WebView App

A simple and lightweight **Flutter WebView** template that instantly converts any website into a mobile app.  
Built with **GetX** for state management and navigation, and optimized for **smooth performance** across Android and iOS.

---

## 🚀 Features

✅ Load any website inside the app using WebView  
✅ Splash screen support  
✅ Loading indicator while page loads  
✅ Back navigation handling  
✅ Error and offline page support  
✅ Works on both Android & iOS  

---

## 🏗️ Folder Structure

<pre>
lib/
│
├── core/
│   ├── utilities/         → App colors, constants, and helpers
│   ├── custom_widgets/    → Common widgets like loader or retry button
│   └── network/           → Internet connectivity check (optional)
│
├── features/
│   ├── webview/
│   │   ├── controller/    → WebViewController for URL and state handling
│   │   └── presentation/
│   │       ├── screens/   → Main WebView screen
│   │       └── widgets/   → Loading or error widgets
│
└── main.dart              → App entry point
</pre>

---

## ⚙️ Setup Instructions

```bash
# 1. Clone the repository
git clone <your-repo-url>

# 2. Install dependencies
flutter pub get

# 3. Run the project
flutter run





