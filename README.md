# Introduction to C

## Table of Contents
- [Introduction to C](#introduction-to-c)
  - [What is C?](#what-is-c)
  - [Why Learn C?](#why-learn-c)
  - [Difference Between C and C++](#difference-between-c-and-c)
- [Installing Required Software](#installing-required-software)
  - [Installing C Compiler and CodeLite IDE](#installing-c-compiler-and-codelite-ide)
    - [Windows](#windows)
    - [Mac](#mac)
    - [Linux](#linux)
  - [Setting Up a Development Environment](#setting-up-a-development-environment)
- [Writing Your First Program](#writing-your-first-program)
  - [Hello, World! Example](#hello-world-example)
  - [Compiling and Running the Program](#compiling-and-running-the-program)

## Introduction to C

### What is C?

C is a general-purpose programming language created by Dennis Ritchie at Bell Laboratories in 1972. Despite its age, C remains a highly popular language, primarily due to its foundational role in computer science.

C is strongly associated with UNIX, as it was developed to write the UNIX operating system.

### Why Learn C?

- **Popularity**: C is one of the most popular programming languages in the world.
- **Foundation for Learning Other Languages**: Knowing C makes it easier to learn other popular languages such as Java, Python, C++, C#, etc., due to similar syntax.
- **Speed**: C is very fast compared to other programming languages like Java and Python.
- **Versatility**: C is highly versatile and can be used in various applications and technologies.

### Difference Between C and C++

- **Extension**: C++ was developed as an extension of C, and both languages share almost the same syntax.
- **Object-Oriented Programming**: The main difference is that C++ supports classes and objects, while C does not.

## Installing Required Software

### Installing C Compiler and CodeLite IDE

To begin programming in C, you need to install a C compiler and an integrated development environment (IDE). For this guide, we will use the CodeLite IDE.

#### Windows

1. **Install the GCC Compiler**:
   - Download and install [MinGW](http://www.mingw.org/). Follow the steps in this [installation guide](http://www.mingw.org/wiki/Getting_Started).
   - During installation, select the `gcc` component.

2. **Download and Install CodeLite IDE**:
   - Go to the [CodeLite download page](https://codelite.org/download).
   - Download the Windows installer and run it.
   - Follow the installation instructions.

#### Mac

1. **Install Xcode Command Line Tools**:
   - Open a terminal and run the following command:
     ```sh
     xcode-select --install
     ```

2. **Download and Install CodeLite IDE**:
   - Go to the [CodeLite download page](https://codelite.org/download).
   - Download the macOS installer and run it.
   - Follow the installation instructions.

#### Linux

1. **Install GCC**:
   - Open a terminal and use your package manager to install GCC. For example, on Ubuntu, run:
     ```sh
     sudo apt-get install build-essential
     ```

2. **Download and Install CodeLite IDE**:
   - Go to the [CodeLite download page](https://codelite.org/download).
   - Download the appropriate package for your distribution and follow the installation instructions.

### Setting Up a Development Environment

Once CodeLite and the GCC compiler are installed, set up your development environment:

1. **Open CodeLite**.
2. **Create a new workspace**:
   - Go to `File` > `New` > `New Workspace`.
   - Enter a name and location for your workspace.
3. **Create a new project**:
   - Right-click on the workspace you created in the `Workspace` tab.
   - Select `New` > `New Project`.
   - Choose `Console Project` and click `Next`.
   - Follow the prompts to set up your project.

## Writing Your First Program

### Hello, World! Example

Let's write a simple "Hello, World!" program to get started with C programming:

1. **Create a new file**:
   - In your CodeLite project, right-click on the `Source` folder.
   - Select `New` > `File`.
   - Name the file `main.c`.

2. **Write the following code in `main.c`**:

    ```c
    #include <stdio.h>

    int main() {
        printf("Hello, World!\n");
        return 0;
    }
    ```

### Compiling and Running the Program

To compile and run your first C program:

1. **Build your project**:
   - Click the `Build` button in the toolbar or press `F7`.

2. **Run your program**:
   - Click the `Run` button in the toolbar or press `Ctrl+F5`.

You should see the output:

