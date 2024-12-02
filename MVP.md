# MVP Implementation Plan

## Day 1-2 (Core Framework)
- Phaser setup for game framework
- Implement `AppManager`:
  - `currentUser`: Managing logged-in user
  - `activeRoom`: Room navigation functionality
  - `initializeApp`: Setting up default settings
  - `navigateToRoom`: Room-switching feature
  - `addRoom`: Add new room functionality
- Implement `Room`:
  - `roomID`: Room identification
  - `loadRoom`: Load room layout and elements

## Day 3-4 (Essential Features)
- Continue work on `AppManager`
- Implement `User`:
  - `userID`: User identity management
  - `username`: User profile setup
  - `updateProfile`: Update user details
- Implement more `Room` functionality:
  - `rooms`: Room list for navigation

## Day 5 (Enhancement & Testing)
- Implement `friendList`: Display user’s friends (P1)
- Implement `sendNotification`: Notification system (P1)
- Implement `Room`:
  - `roomType`: Add room types for different experiences (P1)
  - `accessLevel`: Room access control (P1)
- Final testing and refinement
