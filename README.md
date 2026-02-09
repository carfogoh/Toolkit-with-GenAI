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
1.	Download Go
        •	Go to the official Go website
        •	Download the Windows installer (.msi) for 64-bit
2.	Run the installer
        •	Double-click the .msi file
        •	Click Next and accept the default settings
        •	Go will install (usually to C:\Program Files\Go)
3.	Verify installation
        •	Open Command Prompt or PowerShell
        •	Run:
        •	go version
        •	If installed correctly, you’ll see the Go version printed
4.    Check environment variables (usually automatic)
        •	GOROOT → Go install location
        •	PATH → includes C:\Program Files\Go\bin

5.    Test with a simple program (optional)
            package main
            import "fmt"
            func main() {
                fmt.Println("Hello, Go!")
            }
            Run:
            go run main.go
            That’s it—Go is ready to use 🚀

6.     Errors encountered and how I solved it
                PS C:\Users\User\desktop\goprograms> go run main.go 
                # command-line-arguments
                .\hello.go:4:32: invalid character U+005C '\'
                .\hello.go:4:33: syntax error: unexpected name n in argument list; possibly missing comma or )
                PS C:\Users\User\desktop\goprograms> go run main.go 
                Hello, Go!
                I made a syntax error but with help of Chatgpt I was able to find that I it was a simple mistake thanks Chatgpt

