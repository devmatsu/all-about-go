# All About Go

This repository contains my learning journey with the Go programming language.

It's a personal space to explore Go concepts, build small projects and practice the fundamentals.

## What you'll find here
- Basic syntax and language features
- Go exercises and practice code
- Notes and explanations for future reference
- Small experiments and project prototypes

## Why this repo?
I'm currently learning Go to expand my backend skills and explore a new ecosystem. This repo helps me stay organized and track my progress.

## How to install Go
**Option 1: via official website**
- Go to [https://go.dev/dl/](https://go.dev/dl/)
- Download and install the version for your OS

**Option 2: via Homebrew (macOS)**
```bash
brew install go
```

After installation, verify it with: `go version`

## How to Run Go Code
### Running Go Code with `go run`
Compiles and runs a `.go` file in one step using a temporary binary that's deleted after execution, ideal for quick testing and development.
```bash
go run main.go
```

### Compiling Go Code with `go build`
Use it to generate a standalone executable from your source code.
```bash
go build main.go
```

It generates a binary (e.g. `main` or `main.exe`) that you can run with:
```bash
./main
```
