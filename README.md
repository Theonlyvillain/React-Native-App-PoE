# React-Native-App-PoE

// App.tsx

Updates and Enhancements
1. State Management and Persistence with SharedPreferences
In the final version of the app, I implemented a mechanism to persist the list of dishes across app restarts using SharedPreferences. The dishes are now stored in memory using a SharedPreferencesManager class. This ensures that any dishes added or edited by the user will be saved, and when the app is reopened, the list of dishes will be automatically loaded and displayed. This was accomplished by using Gson to serialize the list of dishes into a JSON format for storage, and deserializing them back into a list when needed.

2. Enhanced UI Components
The app now includes a fully functional navigation system using NavController and NavHost, which allows users to seamlessly navigate between different screens, such as the home screen, settings, and profile. Additionally, the HomeScreen now has a filter menu that allows users to view dishes by course type (e.g., "All", "Starter", "Main", "Dessert"). This feature is dynamic and updates the list of dishes based on the selected filter.

3. Dish Editing and Deleting Functionality
Users can now edit existing dishes through the app. When a user taps on the "Edit" icon next to a dish, the dish's details are displayed in editable text fields. Once the user saves the changes, the dish list is updated accordingly. In addition, dishes can be deleted by tapping the "Delete" icon next to a dish. These actions immediately reflect on the displayed list of dishes.

4. Improved User Interface and Accessibility
The user interface (UI) has been improved with better layout and style adjustments, including consistent padding, spacing, and alignment for a more polished experience. Accessibility has been enhanced by adding accessibility labels to the input fields, improving usability for users relying on screen readers.

5. Settings and Profile Screens
Two additional screens, "Settings" and "Profile", were added to provide a more complete application experience. While the settings screen includes basic options like changing the password or managing notifications (placeholders for future functionality), the profile screen serves as a placeholder for user-specific details.

6. Keyboard Dismissal
A feature was added to dismiss the on-screen keyboard after a dish is added, improving the user experience by reducing screen clutter.
