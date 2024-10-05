# Face Recognition Script

This repository contains a simple Python script to recognize and compare known faces to an unknown face in images using the `face_recognition` library.

## Prerequisites

Before running the script, make sure to have the following installed:

1. **CMake**: This is required for the `face_recognition` library.
2. **Python 3.x**: Ensure you have Python 3 installed along with `pip3`.

## Installation

Follow these steps to set up the environment:

1. **Install CMake**:
   - If you are using Homebrew on macOS, run the following command:
     ```bash
     brew install cmake
     ```

2. **Install face_recognition library**:
   - Use `pip3` to install the `face_recognition` package:
     ```bash
     pip3 install face_recognition
     ```

## Usage

1. **Upload Images**: 
   - Add the images of the known individuals and the unknown person to the repository. Ensure the images are named appropriately (e.g., `vance1.jpg`, `walz1.jpg`, `harris.jpg`).

2. **Run the Script**:
   - After uploading the images, run the Python script to compare the unknown face with the known faces. The script will output whether the unknown face matches the known faces.

