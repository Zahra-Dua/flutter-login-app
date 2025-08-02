Flutter Login App
A beautiful and modern Flutter login application with form validation, smooth navigation, and stunning UI design.

Login Screen

Beautiful gradient background
Clean and modern design
Form validation with error messages
Loading animation during login

Home Screen

Welcome message with user email
Quick action cards
Logout functionality
Professional dashboard layout

Requirements

Flutter SDK (>=3.7.0)
Dart SDK (>=2.19.0)
Android Studio / VS Code
Git

Installation & Setup
1. Clone the Repository
bashgit clone https://github.com/Zahra-Dua/flutter-login-app.git
cd flutter-login-app
2. Install Dependencies
bashflutter pub get
3. Run the Application
bashflutter run
📁 Project Structure
lib/
├── main.dart                 # App entry point
├── screens/
│   ├── login_screen.dart    # Login screen with form validation
│   └── home_screen.dart     # Home screen after login
└── utils/
    └── validators.dart      # Form validation logic

assets/
└── (Add your images here)

pubspec.yaml                 # Dependencies and project config
README.md                    # Project documentation
🎯 How to Use
Login Screen

Enter a valid email address
Enter a password (minimum 6 characters)
Click "Login" button
Enjoy the loading animation
Navigate to home screen

Form Validation Rules

Email: Must be in valid email format (example@domain.com)
Password: Cannot be empty, minimum 6 characters required

Test Credentials
You can use any valid email format and any password with 6+ characters for testing.
🔧 Dependencies
yamldependencies:
  flutter:
    sdk: flutter
  cupertino_icons: ^1.0.2
  email_validator: ^2.1.17

dev_dependencies:
  flutter_test:
    sdk: flutter
  flutter_lints: ^2.0.0
🎨 Design Features
Color Palette

Primary Gradient: #667eea to #764ba2
Secondary Gradient: #6190E8 to #A7BFE8
Accent Colors: Various colors for action cards
Text: White and dark gray combinations

UI Components

Custom Cards with shadow effects
Gradient Backgrounds for modern look
Icon Integration with Cupertino icons
Responsive Layout using flexible widgets
Smooth Animations for better UX

 Author
Zahra Dua

GitHub: @Zahra-Dua
Project: Flutter Login App


