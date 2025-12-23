# Task App

A Flutter application that demonstrates fetching and displaying user data from a PHP API.

## Features

- Fetch users from a remote PHP API
- Display users in a clean list view with Material Design
- Asynchronous data loading with error handling

## Prerequisites

- Flutter SDK (^3.8.1)
- Dart SDK
- A running PHP API server (e.g., at `http://10.0.2.2:8000/api/users.php`)

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd task_app
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

## API Details

The app connects to a PHP API endpoint:
- **URL**: `http://10.0.2.2:8000/api/users.php`
- **Method**: GET
- **Response Format**: JSON with a `data` array containing user objects

Each user object includes:
- `id`: Integer
- `name`: String
- `email`: String

## Dependencies

- `flutter`: SDK for building the UI
- `http`: For making HTTP requests to the API

## Project Structure

- `lib/main.dart`: Main application entry point and user screen
- `lib/models/user.dart`: User data model
- `lib/services/api_service.dart`: Service for API interactions

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
