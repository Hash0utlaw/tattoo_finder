

This project is an iOS app developed in Python, using the Kivy framework, that helps users find tattoo artists or tattoo shops based on their preferred criteria such as location, art style, and pricing.

## Features

The main features of the Tattoo Shop Finder App are:

- User-friendly GUI: The app provides text input fields where users can enter their preferred location, art style, and pricing for a tattoo shop.
- Shop Finder: Based on the user's input, the app searches a predefined list of tattoo shops and displays those that match the user's criteria.
- Compatibility: The app is designed for iOS, following all the requirements for Kivy app development and deployment on an iOS environment.

## How it works

The user enters their criteria in the input fields and presses the 'Find shops' button. The app then calls the `find_tattoo_shops` function from the `project.py` script, which filters the predefined list of tattoo shops based on the user's criteria.

## Installation

The app can be installed on an iOS device by building the project using the Kivy-ios toolchain and deploying it to the device via Xcode.

Please refer to the [Kivy iOS packaging guide](https://kivy.org/doc/stable/guide/packaging-ios.html) for detailed instructions on how to do this.

## Testing

The app includes a set of Pytest unit tests for the `find_tattoo_shops` function. These can be run with the command `pytest test_project.py` in the project directory.

## Requirements

This project requires Python 3.7 or above, Kivy 2.0.0+, and pytest for testing. All dependencies are listed in the `requirements.txt` file.

