# To-Do Mobile Application

## Overview
This is a mobile application built with Android Studio and Firebase. It allows users to manage their tasks effectively by creating to-do lists with reminders and expiration dates. Additionally, users can form groups to collaborate on tasks, assign them to group members, and track their completion.

## Features
- **User Authentication**: Secure login system using Firebase Authentication.
- **To-Do Lists**: Create, edit, and delete to-do lists.
- **Reminders and Expiration Dates**: Set reminders and expiration dates for tasks.
- **Group Functionality**: Create groups to collaborate on tasks.
- **Task Assignment**: Assign tasks to group members.
- **Task Completion Tracking**: Track the completion status of assigned tasks.

## Technologies Used
- **Android Studio**: The primary development environment for building the application.
- **Firebase**:
  - **Authentication**: For user login and registration.
  - **Firestore**: To store and retrieve to-do lists, tasks, and group data.

## Installation and Setup
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
Open in Android Studio:

### Open Android Studio.
Select File > Open and navigate to the cloned repository.
Wait for Gradle to build the project.

###Configure Firebase:
Go to the Firebase Console.
Create a new project or use an existing one.
Add an Android app to your Firebase project with your app's package name.
Download the google-services.json file and place it in the app directory.
Enable Firebase Authentication, Firestore, and Cloud Messaging in the Firebase Console.

### Run the Application:

Connect an Android device or start an emulator.
Click on Run > Run 'app' in Android Studio.

### Usage
Login: Users can log in using their email and password.
Create To-Do List: Users can create to-do lists with tasks, set reminders, and expiration dates.
Manage Groups: Users can create groups, invite others, and assign tasks within the group.
Task Tracking: Users can track the status of tasks, and group members can mark tasks as completed.
License
This project is licensed under the MIT License - see the LICENSE file for details
