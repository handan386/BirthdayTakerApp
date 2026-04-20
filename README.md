Birthday Note Taker: This is a simple iOS app built with Swift that saves and manages birthday notes. It ensures that user data is stored on the device even after the app is closed.

Key Features:
Data Persistence - Uses UserDefaults to save and load names and birthdays.
Information Management - Allows users to view saved notes and delete them when needed.
Updates alerts: Instantly displays saved or deleted information on the screen labels.

Logic:
The user enters a name and a birthday. When the Save button is clicked, the app stores the data using key-value pairs. On startup, the app checks for existing data and displays it. If the Delete button is clicked, it removes the data from storage.

Tech Details:
Language - Swift
Framework - UIKit
Architecture: MVC (Model-View-Controller)
