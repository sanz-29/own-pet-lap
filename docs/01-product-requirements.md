# Virtual Pet Desktop Companion
## Product Requirements Document (PRD)

**Version:** 1.0  
**Status:** Draft  
**Platform:** Windows 10 / Windows 11

---

## 1. Product Overview

Virtual Pet Desktop Companion is a lightweight Windows desktop
application that provides an interactive 3D virtual pet that lives
on the user's desktop.

The application runs in the background and allows the user to
interact with the pet while also providing simple productivity
features such as notes and reminders.

---

## 2. Problem Statement

Traditional desktop applications require the user to open a
window before interacting with them.

Virtual Pet aims to provide a more natural desktop companion that
is continuously available on the desktop while remaining
lightweight and unobtrusive.

---

## 3. Target Users

- Students
- Developers
- Computer users who enjoy virtual pets
- Users who want a simple desktop companion
- Users who want lightweight reminders and notes

---

## 4. Product Goals

The product should:

1. Provide an interactive 3D desktop pet.
2. Allow users to choose their preferred pet.
3. Allow pets to move around the desktop.
4. Provide direct mouse interaction.
5. Provide simple notes and reminders.
6. Run efficiently in the background.
7. Work without requiring an online account.
8. Store user data locally.
9. Be easy to install and share with other Windows users.

---

## 5. Pets

V1 will support four pet choices:

### 5.1 Dog

- Idle
- Walk
- Feed
- Sleep
- Happy reaction
- Throw reaction

### 5.2 Hamster

- Idle
- Walk
- Feed
- Sleep
- Happy reaction
- Throw reaction

### 5.3 Pikachu / Electric Mouse Character

- Idle
- Walk
- Feed
- Sleep
- Happy reaction
- Throw reaction

> Licensing requirements for third-party character assets must
> be reviewed before public distribution.

### 5.4 Ginger Cat

- Idle
- Walk
- Feed
- Sleep
- Happy reaction
- Throw reaction

---

## 6. Pet Modes

The pet will support the following states:

- Idle
- Walk
- Feed
- Sleep
- Grab
- Drag
- Throw
- Airborne
- Land
- Happy
- Pause

---

## 7. Desktop Movement

The pet should be able to:

- Walk across the desktop.
- Change walking direction.
- Stop at desktop boundaries.
- Turn around at boundaries.
- Move at a configurable speed.
- Enter idle mode.
- Resume movement after idle mode.

---

## 8. Mouse Interaction

The user should be able to interact directly with the pet.

### Grab

The user can click the pet.

### Drag

The user can hold the mouse button and move the pet.

### Throw

When the user releases the mouse button, the pet will be
launched according to the direction and approximate velocity of
the cursor movement.

The system may simulate:

- Velocity
- Gravity
- Friction
- Airborne movement
- Landing
- Collision with desktop boundaries

After landing, the pet should return to an appropriate state.

---

## 9. Feed

The user can feed the pet.

Feeding may:

- Trigger an eating animation.
- Increase hunger/satisfaction.
- Increase happiness.
- Play an optional sound.
- Return the pet to idle mode.

---

## 10. Sleep

The user can put the pet into sleep mode.

During sleep:

- Sleep animation is played.
- Pet movement stops.
- Energy can recover.
- The user can wake the pet.

---

## 11. Notes

Users can:

- Create notes.
- Edit notes.
- Delete notes.
- Search notes.
- View saved notes.

Notes will be stored locally.

---

## 12. Reminders

Users can:

- Create reminders.
- Edit reminders.
- Delete reminders.
- Mark reminders as completed.
- Receive Windows notifications.

The pet may react when a reminder is triggered.

---

## 13. System Tray

The application should run from the Windows system tray.

Example:

Virtual Pet

- Walk
- Feed
- Sleep
- Notes
- Reminders
- Change Pet
- Pause
- Resume
- Settings
- Exit

---

## 14. Windows Startup

The application should support starting automatically when Windows
starts.

This should be configurable through application settings.

---

## 15. Data Storage

V1 will use local SQLite storage.

The application should not require:

- Cloud database
- Online account
- External server
- Internet connection for normal operation

---

## 16. Privacy

User notes, reminders and pet data should remain stored locally.

The application should not collect unnecessary personal data.

---

## 17. Technology Stack

### Desktop Framework

Tauri 2

### Native Backend

Rust

### Frontend

TypeScript

### 3D Engine

Three.js

### 3D Asset Format

GLB / GLTF

### Database

SQLite

### Version Control

Git / GitHub

---

## 18. Platform

Primary platform:

- Windows 10
- Windows 11

Future platforms may be considered after V1.

---

## 19. V1 Scope

V1 includes:

- Four pet choices
- 3D pet
- Idle animation
- Walking
- Feeding
- Sleeping
- Mouse grab
- Mouse drag
- Throw interaction
- Pause/resume
- System tray
- Notes
- Reminders
- Windows notifications
- Local SQLite database
- Windows startup
- Windows installer

---

## 20. Future Features

Possible future features:

- Multiple pets
- Pet customization
- Pet names
- Accessories
- More animations
- Pet moods
- Pet growth
- Achievements
- Sound effects
- Themes
- Cloud synchronization
- Mobile companion
- Multiplayer features

These features are outside the initial V1 scope.

---

## 21. V1 Success Criteria

V1 will be considered complete when:

- The application installs successfully on Windows.
- A user can select one of the available pets.
- The pet appears on the desktop.
- The pet can walk around the desktop.
- The user can grab and throw the pet.
- Feed and sleep modes work.
- Notes can be created and stored.
- Reminders can be created and triggered.
- The application can run from the system tray.
- The application can start with Windows.
- User data persists after restarting the application.
- The application can be packaged for distribution.

---

## 22. Project Status

Current phase:

**Requirements and Planning**

Next phase:

**System Architecture**