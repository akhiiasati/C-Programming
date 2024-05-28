# Introduction to C

## Table of Contents
- [Introduction to C](#introduction-to-c)
  - [What is C?](#what-is-c)
  - [Why Learn C?](#why-learn-c)
  - [Difference Between C and C++](#difference-between-c-and-c)
- [Installing Required Software](#installing-required-software)
  - [Installing C Compiler and CodeLite IDE](#installing-c-compiler-and-codelite-ide)
  - [Setting Up a Development Environment](#setting-up-a-development-environment)
  - [Compiling and Running C Programs](#compiling-and-running-c-programs)

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

#### Step-by-Step Installation

1. **Install the GCC Compiler**:
   - **Windows**: Download and install [MinGW](http://www.mingw.org/). Make sure to select the `gcc` component during installation.
   - **Mac**: Install Xcode Command Line Tools by running `xcode-select --install` in the terminal.
   - **Linux**: Install GCC using your package manager. For example, on Ubuntu, run `sudo apt-get install build-essential`.

2. **Download and Install CodeLite IDE**:
   - Go to the [CodeLite download page](https://codelite.org/download).
   - Download the appropriate version for your operating system.
   - Follow the installation instructions for your platform.

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

### Compiling and Running C Programs

With your development environment set up, you can now compile and run C programs:

1. **Write your C code** in the editor. For example, create a `main.c` file.
2. **Build your project**:
   - Click the `Build` button in the toolbar or press `F7`.
3. **Run your program**:
   - Click the `Run` button in the toolbar or press `Ctrl+F5`.

Here's a simple example to get you started:

```c
#include <stdio.h>

int main() {
    printf("Hello, World!\n");
    return 0;
}
