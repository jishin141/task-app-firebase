<<<<<<< HEAD
# Task Management Application

A Flutter-based task management application integrated with Firebase. This app includes features like user authentication, CRUD operations for tasks, animations, persistent login, and seamless navigation using GoRouter.

---

## Features

### 1. User Authentication
- Sign-Up and Login functionality using **Firebase Authentication**.



- Task fields:
  - **Task Title**
  - **Task Description**
  - **Task Image** (optional)
  - **Task Status**
  - **Created Timestamp**
- Features:
  - Add new tasks with an option to upload images (via camera or gallery).
  - Store images in Firebase Storage and save their download URL in Firestore.
  - Edit existing tasks, including updating images.
  - Delete tasks.
  - Mark tasks as completed/incomplete.

### . State Management
- **Provider** (or Bloc) for efficient state management.
- Real-time updates for:
  - Task list changes (add, update, delete).
  - User authentication state.

### . Navigation
- **GoRouter** for modern navigation, including:
  - Login Page
  - Sign-Up Page
  - Task List Page
  - Task Details Page (view/edit specific tasks)



### . Real-time Updates
- Task list updates dynamically as tasks are added, edited, or deleted.

###  User-Specific Data
- Tasks are filtered based on the authenticated user (using Firebase Authentication UID).

---

## Optional Features (Bonus)
- **Responsive Design**: Optimized for both mobile and tablet views.
- **Dark Mode Support**: Includes light and dark themes.
- **Push Notifications**: Notifications for new tasks using Firebase Cloud Messaging (FCM).

---

## Technical Stack

- **Flutter**: Framework for building the app.
- **Firebase Authentication**: For user login and signup.
- **Firebase Firestore**: For storing task data.
- **Firebase Storage**: For storing uploaded task images.
- **Provider** (or Bloc): For state management.
- **GoRouter**: For seamless navigation.
- **image_picker**: For selecting images from the camera or gallery.

---

=======
Task Management Application

A Flutter-based Task Management Application leveraging Firebase to help users efficiently organize and manage tasks. This project demonstrates the implementation of user authentication, state management, real-time updates, and modern navigation using GoRouter. The application is designed with scalability, responsiveness, and an enhanced user experience in mind. Features

User Authentication Firebase Authentication ensures secure login and signup using email and password.

Task Management A robust task management system where users can organize and keep track of their tasks effectively: Task Title: Serves as the main identifier for a task and is prominently displayed. Task Description: A concise overview that provides additional details about the task. Task Status: Users can mark tasks as Pending or Completed, indicated visually with labels/icons. Created Timestamp: Automatically generated to provide context on when the task was created.

Comprehensive CRUD Operations: Create: Users can add new tasks by filling out a form with a title, description, and an optional image. Read: The task list screen displays all tasks in an email-style layout, making it easy to scan through. Update: Users can edit tasks, including updating their details and replacing images. Delete: Tasks can be permanently removed from the list.

State Management State management is handled using Provider, a popular package in Flutter that allows for efficient, scalable, and organized state handling. The authentication state is managed so that: The app dynamically reflects login/logout state changes. User sessions are maintained or invalidated seamlessly. Real-time task updates ensure that changes (e.g., adding, editing, or deleting a task) are immediately reflected on the task list screen without requiring manual refresh.

5.Navigation The app uses GoRouter, a modern navigation solution in Flutter, to provide a declarative and easy-to-manage navigation structure. Screens are designed to flow intuitively: Login Screen: For user login. Sign-Up Screen: For creating a new account. Task List Screen: Displays the user’s tasks in an organized manner. Task Details Screen: Allows users to view and edit the details of a selected task. Navigation Features: Proper navigation guards ensure that unauthorized users cannot access protected screens. Smooth screen transitions enhance the user experience.

Real-Time Updates Tasks are updated in real-time using Firebase Firestore's live database capabilities: When tasks are added, edited, or deleted, the changes are instantly reflected in the task list. This feature eliminates the need for manual refresh or reloading of data, providing a seamless experience.

User-Specific Data User data is securely isolated by associating tasks with the unique Firebase Authentication UID of the logged-in user.

Login Screen: Captures the authentication interface. Task List: Displays tasks with their title, description, and status. Task Details: Provides the editing and viewing interface for individual tasks.

Installation Guide Prerequisites Install the Flutter SDK (Installation Guide). Set up a Firebase project in your Google account. Enable Firebase Authentication, Firestore, and Storage in the Firebase console.
>>>>>>> 6a763e0621aaf8f3f4c72f4f15d1cf0e429c4ab6
#   t a s k - a p p - f i r e b a s e  
 