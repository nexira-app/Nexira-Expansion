Nexira - Flutter Mobile Quiz Game MVP

A Nexira is a neon cyberpunk-themed mobile quiz game built with Flutter.

Features

MVP Phase

Splash Screen with neon design

Firebase Authentication (Login/Register)

Home Page with stats display

Quiz System (10 questions, 15-second timer per question)

Result Page with score and XP display

Local Leaderboard (Top 10 scores)

User Profile with stats

Neon cyberpunk Ul with dark theme

Project Structure

lib/

main.dart

# App entry po

firebase_options.dart

# Firebase con

config/

theme.dart

# App theme & c

models/

question.dart

# Question mode

leaderboard_entry.dart

user_model.dart

providers/

# Authenticatio

quiz_provider.dart

# Quiz state ma

auth_provider.dart

leaderboard_provider.dart

pages/

splash_screen.dart

login_page.dart

register_page.dart

home_page.dart

quiz_page.dart

result_page.dart

leaderboard_page.dart

profile_page.dart

assets/

data/

questions.json

# Quiz question

images/

# App images

animations/

# Lottie animat

Tech Stack

Flutter 3.x

Firebase Authentication

Provider (State Management)

SharedPreferences (Local Storage)

Material 3 Design

Color Palette

Primary: #00E5FF (Cyan Neon)

Secondary: #7B2FFF (Purple Neon)

Background: #0A0A0A (Dark Black)

Surface: #1A1A2E (Dark Blue)

Getting Started

Prerequisites

Flutter 3.x installed

Firebase project created

Android/iOS development environment set up

Installation

1. Clone the repository

git clone <repo-url>

cd nexira

2. Install dependencies

flutter pub get

3. Configure Firebase

Replace Firebase credentials in firebase_options.dart

Download google-services.json (Android) and GoogleService-Info.plist (iOS)

4. Run the app

flutter run

Firebase Setup

1. Create a new Firebase project

2. Enable Firebase Authentication (Email/Password)

3. Add your Android and iOS apps

4. Download configuration files and place them in appropriate directories

5. Update firebase_options.dart with your credentials

Future Enhancements

Character customization

Online leaderboard

In-game shop & cosmetics

Daily challenges

Multiplayer mode

Animations & special effects

License

MIT License - See LICENSE file for details

@ Contributing

Contributions are welcome! Please follow the code style and create a pull request.

Developed with by Nexira Team# Nexira-Expansion
