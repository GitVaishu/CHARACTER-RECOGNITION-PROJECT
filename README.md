# Character Recognition Project

## Problem Statement
The goal of this project is to recognize hand-drawn Devanagari characters from an image and display the corresponding text output on the screen.

### Example:
Given the following input image:

**Input Image:**
(Insert sample image of a handwritten character here)

**Expected Output:**
```
Character: क
```

## Installation and Dependencies
This project requires OpenCV for image processing and C++ for implementation.

### Prerequisites:
- OpenCV4 installed
- g++ compiler
- A dataset of reference images for Devanagari characters

## Running the Project
To compile and run the code, follow these steps:

### Step 1: Compile the Code
```bash
$ g++ -o recognizer main.cpp recognizer.cpp `pkg-config --cflags --libs opencv4`
```

### Step 2: Execute the Program
```bash
$ ./recognizer <dataset_path> <test_image_path>
```
Where:
- `<dataset_path>` is the directory containing reference images of Devanagari characters.
- `<test_image_path>` is the file path of the test image.

### Example Command:
```bash
./recognizer /home/Devanagari-Dataset/Reference-Images/ /home/Devanagari-Dataset/Testcases/char1.png
```

### Expected Output:
If the test image contains the character `क`, the program will print:
```
Character: क
```

## Project Structure
```
|-- character_recognition
    |-- recognizer.h       # Header file (Class declarations)
    |-- recognizer.cpp     # Implementation file
    |-- main.cpp           # Driver code
    |-- README.md          # Project documentation
    |-- Reference-Images/  # Folder containing reference images
    |-- Testcases/         # Folder containing test images
```

## Supporting Files Provided
- **Reference Image Files**
- **Test Image Files** for verifying output
- **ReadME Doc** for OpenCV constructs: `imread()`, `Mat` class
- **Driver Code**

## Files to be Submitted
Ensure you submit the following files:
- `recognizer.h`: Contains class declarations, data members, and methods.
- `recognizer.cpp`: Implements the `recognize()` method and other required functions.

## Author
-Vaishnavi Pandule
-Anushka Shivade 
-Sanika Joshi


