# Business Card Application

A simple Android application built using Kotlin and Jetpack Compose that
displays a digital business card.\
The app presents personal and contact information in a clean, structured
layout.

------------------------------------------------------------------------

## Overview

The Business Card Application demonstrates the fundamentals of building
user interfaces using Jetpack Compose.\
It focuses on layout design, composable functions, alignment, styling,
and proper resource management.

This project is ideal for beginners learning modern Android UI
development.

------------------------------------------------------------------------

## Features

-   Displays name and professional title\
-   Shows contact information (phone, email, social media)\
-   Clean and structured UI layout\
-   Built entirely using Jetpack Compose\
-   Uses string and drawable resources properly\
-   Accessible UI with content descriptions

------------------------------------------------------------------------

## Tech Stack

-   Language: Kotlin\
-   UI Toolkit: Jetpack Compose\
-   IDE: Android Studio\
-   Architecture: Single Activity (Compose-based)

------------------------------------------------------------------------

## UI Components Used

-   @Composable functions\
-   Column and Row layouts\
-   Text composable\
-   Image composable\
-   Modifier (padding, alignment, background, size)\
-   Resource management (strings.xml, drawable)

------------------------------------------------------------------------

## Project Structure

    BusinessCardApp/
    │
    ├── MainActivity.kt
    ├── BusinessCard.kt
    └── res/
        ├── drawable/ (profile image / logo)
        └── values/
            └── strings.xml

------------------------------------------------------------------------

## How It Works

1.  The app uses a Column layout to vertically arrange UI components.
2.  Profile information (name and title) is displayed at the top.
3.  Contact information is displayed in structured rows at the bottom.
4.  Modifiers are used to control spacing, alignment, and styling.

------------------------------------------------------------------------

## Learning Outcomes

-   Understanding composable functions\
-   Creating structured layouts using Column and Row\
-   Applying Modifiers for UI styling\
-   Managing Android resources properly\
-   Building a static UI using Compose

------------------------------------------------------------------------

## Future Improvements

-   Add clickable contact actions (call, email, open LinkedIn)\
-   Improve UI design with Material 3 theming\
-   Add dark mode support\
-   Add animations\
-   Make content dynamic using state

------------------------------------------------------------------------
