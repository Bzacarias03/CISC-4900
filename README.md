# CISC 4900 Project - drawmeet

## Overview

drawmeet is a Flutter-based dating app. Due to confidentiality agreements, specific project details are kept minimal.

## Features

- User Authentication (Sign up, Login, Logout)
- Profile Creation & Editing
- Swiping & Matching System
- Real-time Chat using Supabase
- Interactive User Engagement Features
- Secure & Scalable Backend with Supabase
- Cloud Storage for User Profile Pictures
- Push Notifications for Matches and Messages

## Tech Stack

- **Frontend:** Flutter (Dart)
- **Backend:** Supabase (PostgreSQL, Auth, Realtime Database, Storage)
- **State Management:** Getx Package ([https://pub.dev/packages/get](https://pub.dev/packages/get))
- **Push Notifications:** Firebase Cloud Messaging (WORK IN PROGRESS)
- **Version Control:** Git & GitHub

## Folder Structure

```
lib/
│── main.dart        # Entry point
│── models/          # Data models
│── screens/         # UI Screens
│── core/            # API and backend interaction
```

## Database Schema (Supabase)

### Tables:

- **profiles**: Stores user profile information (id, name, age, bio, etc.)
- profile\_images: Stores user-uploaded images (main\_url, avatar\_url, created\_at)
- **matches**: Stores matched users' relationships (user\_id\_1, user\_id\_2, status)
- **messages**: Handles user conversations (sender\_id, receiver\_id, message, timestamp)
- **drawings**: Stores interactive engagement data (user\_id, drawing\_data, timestamp)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

