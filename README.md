
# River Animation with Jetpack Compose

This project demonstrates how to implement a pull-to-refresh animation using Jetpack Compose and Rive animations in an Android application.

##Demo

https://github.com/user-attachments/assets/cfb40430-0090-4b7c-b8f4-b7834cad74f2


## Features

- **Pull to Refresh**: A custom pull-to-refresh animation using `RiveAnimationView` from the [Rive](https://rive.app/) library.
- **Jetpack Compose**: Fully composed UI with a smooth spring-based animation for the pull-to-refresh gesture.
- **LazyColumn**: Displays a list of items that can be refreshed by pulling down the list.
- **System UI Customization**: Changes the status bar color dynamically based on the theme.
- **Composable-based Rive Animation**: Integrates Rive animations in a fully Jetpack Compose-based UI.

## Project Structure

- `MainActivity.kt`: The main activity of the project where the UI is set and the pull-to-refresh animation logic is implemented.
- `ComposableRiveAnimationView`: A reusable Composable function to display and control the Rive animation.
- `CustomPullRefreshSample`: The core function that manages pull refresh states and triggers the Rive animation based on the user's interactions.
- `ListItemUI`: A simple UI for displaying individual list items in the LazyColumn.

## Getting Started

### Prerequisites

- Android Studio **Bumblebee** or newer
- Jetpack Compose setup
- Rive library integration for Android

### Dependencies

Add the following dependencies in your `build.gradle` file:
