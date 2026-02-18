# Toolkit-with-GenAI

Go Hello word – Capstone Project Toolkit

This is a Go Hello World Toolkit, created as part of the Moringa AI Capstone Project.

Welcome to the Go Hello World Toolkit, created as part of the Moringa AI Capstone Project. This guide helps beginners learn Go programming language with the support of Generative AI tools.

## Project overview 

This is a simple, beginner-friendly “Hello World” application built with Go. The goal is to learn a new programming language by leveraging AI to:

a. Understand syntax and structure

b. Set up a working Go environment

c. Compile and run basis Go code
                  
d. Document the entire process for other to follow

  ## Why Go Language?

Go shines because it’s fast, simple, and great at handling concurrency. It produces efficient single binaries, has clean and readable syntax, and includes strong built-in tooling, making it ideal for scalable cloud services, APIs, and infrastructure.

Quick summary of GO (GoLang) language
Go (Golang) is a fast, simple programming language created by Google, designed for building efficient and scalable software.

## What it’s used for:

• Backend web services and APIs  

• Cloud and microservices systems

• Command-line tools

• Networking and concurrent systems

## Real-world examples:

• Docker – container technology

• Kubernetes – container orchestration

• Terraform – infrastructure as code

• Prometheus – monitoring systems

## System requirements

Operating System: Windows, MacOS, Linux

Processor: 64-bit

Tool/Editor required VS code

## Installation instructions (windows example)
    Here’s a clear, step-by-step guide to install Go on Windows 

                Download Go
                • Go to the official Go website
                • Download the Windows installer (.msi) for 64-bit
                Run the installer
                • Double-click the .msi file
                • Click Next and accept the default settings
                • Go will install (usually to C:\Program Files\Go)
  ## Verify installation
   
                • Open Command Prompt or PowerShell
                • Run:
                • go version
                • If installed correctly, you’ll see the Go version printed

        Check environment variables (usually automatic)

                • GOROOT → Go install location
                • PATH → includes C:\Program Files\Go\bin

  ##   Test with a simple program (optional)
           
                package main
                import "fmt"
                func main() {
                        fmt.Println("Hello, Go!")
                }
                Run:
                go run main.go
                                     
                That’s it—Go is ready to use 🚀

  ## A working code example with comments

                      // Declare the package name. "main" is required for an executable program
                      package main
                      // Import the "fmt" package for formatted I/O (input/output)
                      import "fmt"
                      // Entry point of the program
                      func main() {
                      // Print text to the console with a newline in between
                      fmt.Println("Hello, Go! ")
                      }

## To run the program use this command
     Go run main.go
## Output 
Hello Go!

## Here’s what happens step by step what the code basically does :
1. Go starts executing at the main() function.
2. It calls fmt.Println("Hello, Go!").
3. The program sends the text "Hello, Go!" to the terminal and adds a newline at the end.
4. The program finishes and exits.
## AI Prompt Journal
-Link to the curriculum for the prompt:https://ai.moringaschool.com/ai-software/ai-use-cases/usecases-documentation/

**Prompt 1**

**Prompt:**
“Explain what go language is and how to write a simple program.”

**Response Summary:**
AI explained go language and gave a simple program.

**Evaluation:**
Helped me understand the structure of a Dart program quickly.

**Prompt 2**

**Prompt:**
“Give me a go example that Print Hello world”

**Response Summary:**
AI generated a program in go language.

**Evaluation:**
Saved time and provided a correct syntax example.

**Prompt 3**

**Prompt:**
“Explain this go code line by line.”

**Response Summary:**
AI explained the code line by line and gave comments.

**valuation:**
Improved my understanding and confidence.

## Errors encountered 

|   | **Issue**	           | **Cause**                                 | **Fix**                        |
|:--|:---------------------|:------------------------------------------|:-------------------------------|
|   | go not found         | Go not installed or not added to PATH     | ensure Go/bin is added to system PATH |
|   | undefined: fmt       | Forgot to import package                  | Add import "fmt"                      |
|   | File not recognized	 | File not saved as .go                     | Save file with .go extension          |
|   | Syntax errors      	 | Missing {}, (), "                         | Check syntax carefully                |

## References
- [Go Standard Library Documentation](https://pkg.go.dev/fmt) - reference for packages like fmt used in printing and formatting
- [Programming Language Specification](https://golang.org/ref/spec)-the authoritative source for Go syntax and behavior
- [Go by Example](https://gobyexample.com/)
- [Effective Go](https://golang.org/doc/effective_go.htmls) – practical guide on idiomatic Go coding practices, including functions, packages, and formatting

### Reflection on GenAI Use
Using AI significantly reduced learning time.
It helped with:
* Syntax
* Debugging
* Explaining concepts
* Generating examples

## MIT License
https://github.com/carfogoh/Toolkit-with-GenAI/blob/main/LICENSE

## Author
Built by **Dennis Kabogo Kamau** for the “Toolkit With GenAi” mini-project using GenAI for setup, debugging, and documentation.
                        
