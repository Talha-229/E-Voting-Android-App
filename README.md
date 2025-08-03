# E-Voting-Android-App
A comprehensive Electronic Voting System built for Android that enables secure, transparent, and accessible voting for political elections. This project implements a complete voting ecosystem with both user and admin interfaces, featuring real-time vote counting, OTP verification, and Firebase backend integration.
**For Voters:**
User Registration & Authentication: Secure signup with CNIC validation and user login system
Vote Casting Interface: Intuitive UI displaying political parties with symbols and areas
OTP Verification: Phone number verification using Firebase Authentication for enhanced security
Profile Management: Update personal information and view voting history
Real-time Notifications: Stay informed about voting status and announcements
**For Administrators:**
Admin Dashboard: Centralized control panel for election management
Party Management: Add and manage political parties with symbols and areas
Real-time Vote Counting: Live tracking of votes for each political party
Announcements System: Broadcast important updates to all voters
Vote Analytics: Comprehensive statistics and vote distribution analysis
🛠 Technical Stack
Platform: Android (Java)
Backend: Firebase Realtime Database
Authentication: Firebase Authentication with Phone OTP
UI Framework: Android XML Layouts with Material Design
Database: Firebase Realtime Database for real-time data synchronization
Notifications: Android Notification System

**🚀 Getting Started**
Clone the repository
Apply
Run
Setup Firebase
Create a Firebase project
Add your google-services.json file
Enable Authentication and Realtime Database
Build and Run
Open project in Android Studio
Sync Gradle dependencies
Run on Android device or emulator


** Project Structure**
SemesterProject/
├── app/
│   ├── src/main/
│   │   ├── java/com/example/semesterproject/
│   │   │   ├── UserSignUpForm.java
│   │   │   ├── CastVote.java
│   │   │   ├── AdminDashboard.java
│   │   │   ├── OTPVerfication.java
│   │   │   └── CheckVotes.java
│   │   └── res/
│   │       ├── layout/
│   │       └── values/
└── google-services.json

