auth_dashboard_boilerplate
A foundational Flutter boilerplate project providing a clean, structured starting point for applications requiring user authentication and a dashboard interface. This repository sets up the basic architecture, including screen, model, and service layers, with mock authentication ready for integration with real backend services.

✨ Features
User Authentication:

Login Screen: UI and logic for user sign-in.

Sign-Up Screen: UI and logic for new user registration.

Mock Authentication Service: Simulated login and sign-up functionality (hardcoded users in AuthService) for immediate testing and development.

Dashboard Screen: A basic placeholder screen accessible after successful login.

Clean Architecture Structure: Organized screens, models, and services directories for maintainable and scalable code.

Responsive UI: Designed with standard Flutter widgets for adaptive layouts across devices.

Google Fonts Integration: Uses the 'Inter' font for a modern typographic look.

📊 Latest Updates
I've recently enhanced this boilerplate with the following improvements:

Improved UI/UX
Refined the visual styling of both Login and Sign-Up screens for a more modern and intuitive user experience. Enhanced input field aesthetics and button feedback.

Robust Mock Authentication
Strengthened the mock authentication service to include more comprehensive error handling and basic password validation during sign-up, making it a more realistic placeholder for future API integration.

🚀 Getting Started
To run this project locally, follow these steps:

Prerequisites
Flutter SDK installed.

IDE (VS Code, Android Studio, IntelliJ IDEA) with Flutter and Dart plugins.

Installation
Clone the repository:

git clone https://github.com/YOUR_USERNAME/auth_dashboard_boilerplate.git
cd auth_dashboard_boilerplate

(Remember to replace YOUR_USERNAME with your actual GitHub username and adjust the repo name if it differs.)

Install dependencies:

flutter pub get

Run the application:

flutter run

The app will start on your configured device or emulator, presenting the login screen.

🔑 Authentication Details
The project uses a mock AuthService (lib/services/auth_service.dart) with hardcoded credentials for demonstration:

Login:

Email: test@example.com

Password: password123

Email: user@domain.com

Password: secretpass

Sign-Up: You can register new users; they will be added to the in-memory mock user list for the current session.

To integrate with a real backend (e.g., Firebase, REST API):
Modify the login and signUp methods within lib/services/auth_service.dart to make actual API calls or use a chosen authentication SDK.

📂 Project Structure
auth_dashboard_boilerplate/
├── lib/
│   ├── main.dart             # Main entry point of the app
│   ├── models/
│   │   └── user_model.dart   # Data model for user information
│   ├── screens/
│   │   ├── dashboard_screen.dart # Dashboard UI
│   │   ├── login_screen.dart     # Login UI
│   │   └── signup_screen.dart    # Sign-up UI
│   └── services/
│       └── auth_service.dart # Handles authentication logic (mock or real)
├── pubspec.yaml              # Project dependencies and metadata
└── README.md                 # This file
