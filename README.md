# 🔐 User Sign In / Sign Up App (iOS)

A clean and simple **iOS Authentication App** built using **SwiftUI**.  
It demonstrates how to implement **Sign Up**, **Login**, and **Welcome** screens with proper validation and navigation logic.

---

## ✨ Features
- 🧍 User Sign-Up and Login functionality  
- ✅ Input validation for email and password  
- 🔒 Local credential storage using in-memory variables (no backend)  
- 🏠 Welcome screen after successful login  
- 🚫 Disabled “Login” button until user signs up  
- 🎨 Simple, responsive SwiftUI layout  

---

## 🧰 Tech Stack
| Category         | Tools / Frameworks             |
|------------------|--------------------------------|
| **Language**     | Swift                          |
| **Framework**    | SwiftUI                        |
| **Architecture** | MVVM (Model-View-ViewModel)    |
| **Storage**      | Local variables / `@State`     |
| **IDE**          | Xcode                          |

---

## 🗂️ Project Structure
UserSigninSignUp/
├── UserSigninSignUpApp.swift # App entry point
├── Models/
│ └── UserModel.swift # User structure for signup/login data
├── ViewModels/
│ └── AuthViewModel.swift # Handles validation and navigation logic
├── Views/
│ ├── LoginView.swift # Login screen
│ ├── SignUpView.swift # Registration screen
│ └── WelcomeView.swift # Post-login welcome screen
├── Assets.xcassets/ # App icons and color assets
├── Info.plist # App configuration
└── README.md
