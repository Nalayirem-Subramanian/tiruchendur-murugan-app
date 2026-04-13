# Tiruchendur Murugan Mobile App

## 📱 Overview

The **Tiruchendur Murugan Mobile App** is a Flutter-based mobile application designed to provide a seamless devotional experience for users visiting or exploring the Tiruchendur Murugan Temple. The app integrates user authentication, personalized greetings, and temple-related features.

This project demonstrates industry-level best practices including REST API integration, authentication, clean architecture, and scalable design.

---

## 🚀 Features

### 🔐 Authentication

* User Signup
* User Login (API-based authentication)
* Secure password handling

### 🏠 Home Screen

* Personalized welcome message (e.g., *Welcome Selvi*)
* Clean and simple UI for users

### 📡 Backend Integration

* REST API communication using HTTP
* JSON request/response handling

### 💾 Local Storage (Optional Enhancement)

* Session persistence using SharedPreferences

---

## 🏗️ Tech Stack

### Frontend (Mobile App)

* Flutter (Dart)
* Material UI Components

### Backend

* Java
* Spring Boot
* REST APIs
* MongoDB

### Tools & Libraries

* HTTP package (Flutter)
* Postman (API testing)
* Git (Version control)

---

## 📂 Project Structure

```
lib/
 ├── screens/
 │    ├── signin_screen.dart
 │    ├── signup_screen.dart
 │    ├── home_screen.dart
 │
 ├── services/
 │    ├── api_service.dart
 │
 ├── models/
 │    ├── user_model.dart
 │
 └── main.dart
```

---

## 🔄 Application Flow

1. User opens the app
2. User signs up or logs in
3. API validates user credentials
4. On success:

   * User navigates to Home Screen
   * Displays personalized welcome message

---

## 🔗 API Endpoints

### Signup

```
POST /api/signup
```

### Login

```
POST /api/login
```

### Sample Request (Login)

```json
{
  "email": "user@example.com",
  "password": "password123"
}
```

### Sample Response

```json
{
  "message": "Login successful",
  "username": "Selvi"
}
```

---

## ⚙️ Setup Instructions

### Prerequisites

* Flutter SDK installed
* Android Studio / VS Code
* Java 17+
* MongoDB running locally or remotely

### Steps to Run

#### 1. Clone Repository

```
git clone <your-repo-url>
cd tiruchendur-murugan-app
```

#### 2. Install Dependencies

```
flutter pub get
```

#### 3. Run Backend (Spring Boot)

* Start your Spring Boot application
* Ensure APIs are running on correct port (e.g., 8080)

#### 4. Run Flutter App

```
flutter run
```

---

## 🔐 Security Considerations

* Avoid storing plain text passwords
* Use encryption (BCrypt recommended)
* Implement JWT for production-level authentication

---

## 📈 Future Enhancements

* Temple information & history section
* Live darshan updates
* Festival notifications
* Online booking for darshan
* Multi-language support (Tamil & English)

---

## 🧪 Testing

* Unit testing for backend services
* API testing using Postman
* Manual UI testing in Flutter

---

## 📦 Deployment

### Backend

* Deploy using Docker or cloud platforms (AWS, Azure)

### Mobile App

* Generate APK:

```
flutter build apk
```

---

## 👩‍💻 Author

**Nalayirem Subramanian**

* Java & Spring Boot Developer
* Flutter Enthusiast

---

## 📄 License

This project is for educational and demonstration purposes.

---

## 🙏 Acknowledgement

Inspired by devotion to Lord Murugan and aimed at helping devotees connect digitally.
