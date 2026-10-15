# RoadSafeAI

## Summary

RoadSafeAI is a web-based road safety system that helps communities report, monitor, and reduce road hazards. Potholes, damaged signage, poor lighting, and accident-prone spots often go unreported or are slow to reach the right authorities. RoadSafeAI gives residents a simple place to submit reports and gives local officials a clearer view of where the problems are, so they can respond faster.

Planned first features:

- User login and account access
- Road hazard and incident reporting
- Home dashboard showing reported road issues
- AI-assisted analysis of reports (e.g., categorizing hazards and highlighting high-risk areas)

> Activity 8 scope: this checkpoint only contains the initialized Flutter Web project, the organized `lib/` structure, and the starter Home and Login screens. The REST API, database, and AI features are planned but not yet implemented.

## Current stack

| Layer | Status |
|-------|--------|
| Flutter Web / Dart | Implemented (starter UI) |
| REST API (e.g., FastAPI) | Planned |
| PostgreSQL | Planned |
| Git + GitHub | Implemented |

## Project structure

```
lib/
├── main.dart          # App entry point
├── app.dart           # MaterialApp setup, theme, routes
├── screens/           # home_screen.dart, login_screen.dart
├── widgets/           # app_button.dart, app_text_field.dart
├── services/          # Future API clients
├── models/            # Future data models
├── routes/            # Routing definitions
└── constants/         # App-wide constants
```

## Run locally

Requirements: Flutter SDK and Google Chrome.

```bash
git clone https://github.com/ricorespecia-oss/semester_project.git
cd semester_project
flutter pub get
flutter run -d chrome
```

Run the commands from the project root (the folder containing `pubspec.yaml`).

## First checkpoint

Date: October 15, 2026 | Commit: 153e0f6