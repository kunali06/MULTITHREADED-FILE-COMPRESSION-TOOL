# MULTITHREADED-FILE-COMPRESSION-TOOL
MULTITHREADED FILE COMPRESSION TOOL

COMPANY: CODTECH IT SOLUTIONS

NAME: KUNALI BHAVARTHE

INTERN ID: CT2MTXEI

DOMAIN: C++ PROGRAMMING

DURATION: 8 WEEEKS

MENTOR: NEELA SANTHOSH


#DESCRIPTION 
Project Description: File Handling Application in C++
Overview
This project is a console-based C++ application developed using Code::Blocks that demonstrates basic file-handling operations. The application allows users to write, append, and read data from a text file. It has been designed as a simple yet comprehensive example of how to manage files in C++ using the iostream and fstream libraries.

Objectives
Demonstrate File I/O Operations: The project aims to showcase three primary file-handling techniques in C++: writing (overwriting), appending, and reading file data.

User Interaction: Provide an interactive menu-driven interface that enables users to choose the desired file operation easily.

Error Handling: Illustrate basic error checking techniques to ensure that the operations (read, write, append) handle issues (like file not opening) gracefully.

Key Features
Write Operation:

The application creates or overwrites an existing text file.

It allows the user to enter text from the console, which is then written to a file named example.txt.

Append Operation:

Users can append additional data to the existing file without removing the old content.

This ensures that new inputs are added at the end of the file.

Read Operation:

The program reads the content of example.txt and displays it on the console.

This function helps verify that data is written and appended correctly.

Menu-Driven Interface:

An interactive, loop-based menu allows users to select the desired operation (write, append, read, or exit).

Clear instructions are provided, making the user experience straightforward.

Error Management:

The program includes error checking for file operations, ensuring that any issues (such as file access errors) are reported to the user.

Technical Details
Language: C++

Development Environment: Code::Blocks

Libraries Used:

<iostream> for standard I/O operations.

<fstream> for file-handling operations.

<string> for managing text data.

Architecture
Functions:

writeToFile(): Opens the file in write mode to overwrite any existing content.

appendToFile(): Opens the file in append mode to add data at the end without erasing existing contents.

readFromFile(): Opens the file in read mode to display its contents.

Main Function:
The main function drives the application, displaying a menu to the user and invoking the corresponding functions based on user input until the exit option is selected.

Usage Instructions
Setup:

Open Code::Blocks and create a new Console Application project in C++.

Replace the content of the default main.cpp with the provided code.

