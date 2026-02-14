# Toolkit-with-GenAI
This is a Go Hello World Toolkit, created as part of the Moringa AI Capstone Project.

Go Hello word – Capstone Project Toolkit

Welcome to the Go Hello World Toolkit, created as part of the Moringa AI Capstone Project. This guide helps beginners learn Go programming language with the support of Generative AI tools.

Project overview 

This is a simple, beginner-friendly “Hello World” application built with Go. The goal is to learn a new programming language by leveraging AI to:
a	Understand syntax and  structure
b	Set up a working Go environment
c	Compile and run basis Go code
d	Document the entire process for other to follow

Why Go Language?

Go shines because it’s fast, simple, and great at handling concurrency. It produces efficient single binaries, has clean and readable syntax, and includes strong built-in tooling, making it ideal for scalable cloud services, APIs, and infrastructure.
Quick summary of GO (GoLang) language

Go (Golang) is a fast, simple programming language created by Google, designed for building efficient and scalable software.

What it’s used for:
•	Backend web services and APIs
•	Cloud and microservices systems
•	Command-line tools
•	Networking and concurrent systems
Real-world examples:
•	Docker – container technology
•	Kubernetes – container orchestration
•	Terraform – infrastructure as code
•	Prometheus – monitoring systems

System requirements

Operating System: Windows, MacOS, Linux
Processor: 64-bit
Tool/Editor required VS code

Installation instructions (windows example)

Here’s a clear, step-by-step guide to install Go on Windows 
	Download Go
        •	Go to the official Go website
        •	Download the Windows installer (.msi) for 64-bit
	Run the installer
        •	Double-click the .msi file
        •	Click Next and accept the default settings
        •	Go will install (usually to C:\Program Files\Go)
	Verify installation
        •	Open Command Prompt or PowerShell
        •	Run:
        •	go version
        •	If installed correctly, you’ll see the Go version printed
       Check environment variables (usually automatic)
        •	GOROOT → Go install location
        •	PATH → includes C:\Program Files\Go\bin

      Test with a simple program (optional)
            package main
            import "fmt"
            func main() {
                fmt.Println("Hello, Go!")
            }
            Run:
            go run main.go
            That’s it—Go is ready to use 🚀

        A working code example with comments

// Declare the package name. "main" is required for an executable program

package main

// Import the "fmt" package for formatted I/O (input/output)

import "fmt"

// Entry point of the program
func main() {
    // Print text to the console with a newline in between
    fmt.Println("Hello, Go! ")
}


To run the program use this command
Go run main.go
Output 
Hello Go!
Here’s what happens step by step what the code basically does :
1.	Go starts executing at the main() function.
2.	It calls fmt.Println("Hello, Go!").
3.	The program sends the text "Hello, Go!" to the terminal and adds a newline at the end.
4.	The program finishes and exits.
Errors encountered and how I solved it
PS C:\Users\User\desktop\goprograms> go run main.go 
# command-line-arguments
.\hello.go:4:32: invalid character U+005C '\'
.\hello.go:4:33: syntax error: unexpected name n in argument list; possibly missing comma or )
PS C:\Users\User\desktop\goprograms> go run main.go 
Hello, Go!
I made a syntax error but with help of Chatgpt I was able to find that I it was a simple mistake
References
1.	Go Programming Language Specification – the authoritative source for Go syntax and behavior
https://golang.org/ref/spec
2.	Go Standard Library Documentation (fmt, time, etc.) – reference for packages like fmt used in printing and formatting
https://pkg.go.dev/fmt
https://pkg.go.dev/time
3.	Effective Go – practical guide on idiomatic Go coding practices, including functions, packages, and formatting
https://golang.org/doc/effective_go.htmls
4.	A Tour of Go – interactive tutorial for beginners to learn Go syntax and concepts
https://tour.golang.org
5.	Go by Example – hands-on examples of Go features like fmt.Println, structs, and loops
https://gobyexample.com


