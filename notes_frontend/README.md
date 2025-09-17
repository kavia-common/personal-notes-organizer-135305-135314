# Ocean Notes (notes_frontend)

A modern, minimalist Flutter app to create, edit, and organize personal notes.
Built with the "Ocean Professional" theme featuring blue primary and amber accents,
rounded corners, subtle shadows, and smooth transitions.

## Features
- Create, edit, pin, and delete notes
- Local persistence using SQLite (sqflite)
- Provider-based state management
- Search notes by title/content
- Ocean Professional theme

## Run
- flutter pub get
- flutter run

## Project Structure
- lib/
  - main.dart: App root, routing, and theming
  - src/
    - data/: Database and repository
    - models/: Data models
    - state/: Provider state
    - theme/: Theme configuration
    - ui/pages/: List, detail, and edit pages
    - ui/widgets/: Reusable UI elements
