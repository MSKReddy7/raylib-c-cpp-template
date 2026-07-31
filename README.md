# raylib C/C++ Template

This is a simple and ready-to-use raylib template for Windows. It is designed for students, beginners, and anyone who wants to start a raylib project quickly.

## What is included
- A basic raylib example in main.c
- Raylib headers and libraries in raylib-6.0/
- Raylib documentation in raylib-documentaion/

## How to use this project

### 1. Clone the repository
Open your terminal and run:

```bash
git clone https://github.com/MSKReddy7/raylib-c-cpp-template.git
cd raylib-c-cpp-template
```

### 2. Setup raylib in your compiler
After cloning, go to the folder named raylib-6.0 and copy the files into your compiler paths.

- Copy the contents of raylib-6.0/include into your compiler's include folder
- Copy the contents of raylib-6.0/lib into your compiler's lib folder

Example locations:
- For MinGW: copy to your MinGW include and lib folders
- For MSVC: add the include and lib folders in your compiler settings

If you are using a different compiler, just make sure your compiler can find:
- the raylib header files
- the raylib library files

### 3. Rename your source file
You can keep the file as main.c, or rename it to whatever you want.

- Use .c for C projects
- Use .cpp for C++ projects

### 4. Build and run the project
If you are using Visual Studio Code, open this folder and press:

```text
Ctrl + Shift + B
```

This workspace already has a build task set up, so the project should compile and run successfully.

### 5. Use the raylib documentation
You can learn more from the documentation folder named raylib-documentaion. It contains useful raylib references and examples.

## Notes
- Keep the raylib-6.0 folder with your project so the setup stays organized.
- If you get errors, check whether your compiler can see both the include and lib folders correctly.

Enjoy coding with raylib!
