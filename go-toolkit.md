# Getting Started with Go (Golang) – A Beginner’s Toolkit

## 1. Title & Objective

### Objective
The goal of this toolkit is to help beginners learn the basics of the Go programming language by setting it up from scratch and running a simple Hello World application.

### Why Go?
I chose Go because it is a modern, simple, and efficient programming language developed by Google. It is widely used in backend development, cloud computing, and DevOps tools.

### End Goal
By the end of this guide, users will be able to install Go, write a basic Go program, and run it successfully on their machine.

---

## 2. Quick Summary of the Technology

Go, also known as Golang, is an open-source programming language designed for simplicity and high performance.

It is commonly used to build backend services, APIs, cloud platforms, and command-line tools.

A real-world example of Go usage is Docker and Kubernetes, which are written in Go.

---

## 3. System Requirements

- Operating System: Windows / Linux / macOS  
- Code Editor: Visual Studio Code  
- Tools Required: Go SDK  
- Internet connection for installation  

---

## 4. Installation & Setup Instructions

### Step 1: Install Go
Download Go from the official website:

https://go.dev/dl/

Run the installer and follow the default installation steps.

---

### Step 2: Verify Installation
Open a terminal and run:

```bash
go version
Expected Output(example)
go version go1.21.0 windows/amd64



Step 3: Create Project Folder

# Create the main project folder
mkdir go-beginner-toolkit
cd go-beginner-toolkit
# Create a subfolder for your Hello World example
mkdir go-hello-world
cd go-hello-world

5. Minimal Working Example
Description

This example prints "Hello, World!" to the terminal using Go.

Code Example

Create a file named main.go and add the following code:
package main           // Defines the package name; 'main' is special as the entry point

import "fmt"           // Imports the 'fmt' package for printing to the terminal

func main() {          // main function where the program starts execution
    fmt.Println("Hello, World!")  // Prints "Hello, World!" to the terminal

Run the Program
# Initialize Go module
go mod init hello
# Run the program
go run main.go

Expected Output
Hello, World!

6. AI Prompt Journal
Prompt 1

Prompt Used:
"Explain Go programming language in simple terms for a beginner"

Purpose:
To understand what Go is and whether it is suitable for a beginner project.

Reflection:
The AI provided a simple explanation of Go and its real-world uses, which helped me confidently choose it for this capstone.

Prompt 2

Prompt Used:
"Give me step-by-step instructions to create and run a Hello World program in Go on Windows"

Purpose:
To learn how to create a Go project and run it correctly using the terminal.

Reflection:
The AI helped me understand how to navigate folders, initialize a Go module, and run a Go file using go run.

7. Common Issues & Fixes
Issue 1: go command not recognized

Cause: Go is not added to the system PATH or the terminal was not restarted.
Fix: Restart VS Code or add Go to the system environment variables.

Issue 2: Program does not run

Cause: Attempting to run the .go file directly instead of using the Go command.
Fix: Always run the program using:

go run main.go

8. References

Official Go Documentation: https://go.dev/doc/

Go Installation Guide: https://go.dev/doc/install

VS Code Go Setup: https://code.visualstudio.com/docs/languages/go