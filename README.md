# Flutter Navigation with Data Passing

This Flutter application demonstrates how to navigate between screens and pass data between them.

## Features

1. **First Screen**:
   - Contains two text fields for collecting the user's name and email.
   - Includes a "Submit" button that navigates to the Second Screen, passing the entered name and email as arguments.

2. **Second Screen**:
   - Displays the name and email received from the First Screen.
   - Provides a "Go Back" button to navigate back to the First Screen.

## Usage

1. Run the app to see the First Screen.
2. Enter a name and email in the text fields.
3. Tap the "Submit" button to navigate to the Second Screen, which displays the entered name and email.
4. Tap the "Go Back" button to return to the First Screen.

## Code Overview

The application consists of three main files:

1. `main.dart`: The entry point of the application, which sets the `FirstScreen` as the home screen.
2. `first_screen.dart`: Defines the `FirstScreen` widget, which collects the user's name and email and navigates to the `SecondScreen`.
3. `second_screen.dart`: Defines the `SecondScreen` widget, which displays the received name and email and provides a "Go Back" button to navigate back to the First Screen.

The key points to note are:

- `TextEditingController`s are used to manage the text fields and retrieve the entered values.
- The `Navigator.push()` method is used to navigate to the `SecondScreen`, passing the name and email as arguments.
- The `SecondScreen` widget receives the name and email as constructor parameters and displays them.
- The `Navigator.pop()` method is used to navigate back to the previous screen.

## Running the App

1. Make sure you have Flutter installed and configured on your machine.
2. Clone or download the project files.
3. Open the project in your preferred IDE (e.g., Android Studio, Visual Studio Code).
4. Run the app on an emulator or physical device.

## Customization

You can customize the app by modifying the following:

- **Styling**: Update the UI elements, such as colors, fonts, and layouts, to match your design requirements.
- **Additional Functionality**: Expand the app by adding more screens, implementing complex navigation, or integrating additional features.

## Conclusion

This project demonstrates the basic principles of screen navigation and data passing in a Flutter application. It can serve as a starting point for building more complex Flutter apps that require navigation and data sharing between screens.