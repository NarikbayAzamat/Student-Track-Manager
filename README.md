# Student Task Manager

## Description
Student Task Manager is a simple Android app that helps students organize
their homework, assignments, and study tasks in one place, so they don't
lose track of deadlines.

## Functionality
- User can create a new task with a title and description.
- User can set an optional due date and subject/category for a task.
- User can view a list of all saved tasks on the main screen.
- User can tap a task to view its full details.
- User can edit an existing task's title, description, or due date.
- User can delete a task from the list.
- User can mark a task as completed or incomplete.
- Completed tasks are visually distinguished from incomplete tasks.
- The app displays an empty state message when there are no saved tasks.
- All tasks persist locally between app sessions.

## Current Folder Structure
StudentTaskManager/
|
+-- app/
|   +-- src/
|   |   +-- main/
|   |   |   +-- java/
|   |   |   |   +-- com/example/studenttaskmanager/
|   |   |   |       +-- MainActivity.kt
|   |   |   |
|   |   |   +-- res/
|   |   |   |   +-- drawable/
|   |   |   |   +-- mipmap/
|   |   |   |   +-- values/
|   |   |   |   +-- xml/
|   |   |   |
|   |   |   +-- AndroidManifest.xml
|   |   |
|   |   +-- test/
|   |   +-- androidTest/
|   |
|   +-- build.gradle.kts
|   +-- proguard-rules.pro
|
+-- gradle/
+-- .gitignore
+-- build.gradle.kts
+-- settings.gradle.kts
+-- README.md

## Build and Run Instructions
1. Clone or download the repository.
2. Open the project in Android Studio.
3. Allow Gradle to sync.
4. Connect an Android device or start an emulator.
5. Click Run.
