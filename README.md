# raylib C/C++ Template

This is a simple Windows-ready raylib template for beginners and students. The goal is to get you started quickly with a working C/C++ setup.

## Windows setup

### 1. Install the compiler first
Download and install MSYS2 from:

https://github.com/msys2/msys2-installer/releases/download/2026-06-11/msys2-x86_64-20260611.exe

After installing MSYS2, open the MSYS2 terminal and install GCC:

```bash
pacman -S mingw-w64-ucrt-x86_64-gcc
```

### 2. Add the compiler to your PATH
After installation, add the compiler bin folder to your system PATH.

Typical locations are:

- `C:\msys64\ucrt64\bin`
- or `C:\msys64\mingw64\bin`

If you are not sure which one applies, use the folder that contains `g++.exe` and `gcc.exe`.

### 3. Copy or move the raylib files
Go to your project folder and find the raylib files in the `raylib-6.0` folder.

Copy or move the contents of:

- `raylib-6.0/include` to your compiler include folder
- `raylib-6.0/lib` to your compiler lib folder

For example, you can place them in:

- `C:\msys64\mingw64\include`
- `C:\msys64\mingw64\lib`

If you installed the UCRT toolchain, use the `ucrt64` folders instead.

### 4. Open the project in VS Code
Open the project folder in Visual Studio Code.

You can then build and run the project from the built-in terminal or by using the provided build task.

## What is included
- A basic raylib example in `main.cpp`
- Raylib headers and libraries in `raylib-6.0/`
- Raylib documentation in `raylib-documentaion/`

## Notes
- Keep the `raylib-6.0` folder with your project so the setup stays organized.
- If you get errors, make sure your compiler can find both the include and lib folders.

Enjoy coding with raylib!
