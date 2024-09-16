# C++ Gaussian Elimination with JSON Input

This repository contains a C++ program that uses Gaussian Elimination to solve a system of linear equations with input data provided in a JSON file. The program also includes a custom base conversion function and demonstrates how to handle JSON data using the `nlohmann/json` library.

## Prerequisites

1. **C++ Compiler**: Ensure you have a C++ compiler installed. You can use GCC, Clang, or Visual Studio.
2. **JSON Library**: This project uses the `nlohmann/json` library. You need to have this library available to compile the code.

## Setup Instructions

### 1. Install C++ Compiler

   - **On Linux or macOS**: You can usually install GCC or Clang via your package manager.
   - **On Windows**: You can use MinGW or Visual Studio.

### 2. Create the Input JSON File

   - Create a file named `input.json` in the same directory as the source code. The JSON file should follow the format expected by the program.

### 3. Ensure Dependencies

   - Download the `nlohmann/json` header file from [nlohmann/json GitHub](https://github.com/nlohmann/json) and place it in your project directory or install it using a package manager.

### 4. Run the Program

   - Open the project directory in Visual Studio Code or your preferred IDE.

   - Ensure the json.hpp file is in the same directory as your source code.

   - Open the main source file (e.g., shamir.cpp) and ensure it includes the JSON library:
     ```sh
     #include "json.hpp"
     ```
   - Use your IDE's build and run functionality to compile and execute the program. For most IDEs, you can press a "Run" or "Build and Run" button to compile and execute the code.
     
### 5. Verify Output

   - Check the console output to ensure it matches your expectations
