# About Page Flutter Project

This Flutter project demonstrates creating a simple "About" page with various components, including a profile section, fun facts, a navigation drawer, and a bottom navigation bar. It uses `MaterialApp` as the main widget and leverages `Scaffold`, `Drawer`, and `BottomNavigationBar` for layout organization.

## Features

- **App Bar**: Displays the title "About Page" centered with a blue background.
- **Profile Section**:
  - Includes a profile picture displayed as a circular avatar.
  - Displays personal information such as name, student ID, and class using the `ProfileList` widget.
- **Fun Fact Section**: A list of fun facts shown within a decorated container with a box shadow for a subtle 3D effect.
- **Floating Action Button**: A circular button at the bottom right with a plus icon, which can be used for additional actions.
- **Navigation Drawer**:
  - Contains a header displaying the user’s account information.
  - Includes "Settings" and "Log Out" options with icons.
- **Bottom Navigation Bar**:
  - Provides navigation options for "Home," "Search," and "About" pages.
  - Highlights the "About" icon by default.

## Widgets Used

### `ProfileList`
A custom widget for displaying profile information with an icon, title, and subtitle. Styled with padding, shadow, and rounded corners.

### `BulletList`
A custom widget for displaying bullet points in a list format. Each item is preceded by a bullet symbol and formatted to align text neatly.

## How to Use

1. Add an image file named `profile_pic.JPG` in the `assets/images/` folder to use as the profile picture.
2. Run the project using `flutter run` to view the About Page with all components.

## Project Structure

- **main.dart**: Contains the main app code with `MaterialApp`, `Scaffold`, `AppBar`, and other UI elements.
- **ProfileList**: Custom widget for profile items with icons.
- **BulletList**: Custom widget for displaying lists of items in bullet format.

## Installation

1. Ensure Flutter is installed and set up on your system.
2. Clone this repository.
3. Run `flutter pub get` to install dependencies.
4. Run `flutter run` to start the app.

## Dependencies

- **Flutter SDK**: Required to run the project.
- **Material Design**: For standard UI components.

## Screenshot

Add a screenshot of the app here to showcase the UI.

## Author

- **Name**: Alif Faturrohman
- **Email**: aliffaturrohman11@gmail.com

Feel free to explore and modify this project to suit your needs. Enjoy coding with Flutter!
