# Concentrix API Services Team Onboarding (Golang)

Welcome to the Concentrix API Services Team! This guide will help you set up your development environment tailored for Golang development within our enterprise.

## Table of Contents

1. [Setting Up Your Go Runtime](#setting-up-your-go-runtime)
2. [Choosing and Setting Up an IDE](#choosing-and-setting-up-an-ide)
3. [Project Repository and Initial Setup](#project-repository-and-initial-setup)
4. [Concentrix Enterprise Guidelines](#concentrix-enterprise-guidelines)

## Setting Up Your Go Runtime

1. **Install Go**: Download and install the latest stable version of Go approved by Concentrix IT from our internal software portal.
2. **Verify Installation**: Open a terminal and run `go version` to ensure Go was installed correctly.
3. **Setup GOPATH**: Set up your `GOPATH` as per Concentrix's enterprise guidelines. [Here's our internal guide](link-to-internal-gopath-guide).

## Choosing and Setting Up an IDE

1. **Visual Studio Code**: 
   - Download and install VS Code from our internal software portal.
   - Install the [Go extension](https://marketplace.visualstudio.com/items?itemName=golang.Go) approved by Concentrix IT.
2. **GoLand**: 
   - We have an enterprise license for [GoLand by JetBrains](https://www.jetbrains.com/go/). Request access from IT.
   - Follow our internal documentation for setup and configuration.

## Project Repository and Initial Setup

1. **Clone the Repository**: Once you have access, clone the main API services repository from ConcentrixGit to your local machine.
2. **Install Dependencies**: Navigate to the project directory and run `go get -v ./...` to fetch all the necessary dependencies.
3. **Run the Project**: Follow the README in the project repository for instructions on how to run the project locally.

## Concentrix Enterprise Guidelines

1. **Code Reviews**: All code must be reviewed by at least two senior developers before merging.
2. **Testing**: Ensure all your code has appropriate unit and integration tests.
3. **Documentation**: All functions and modules should be documented as per our internal documentation standards.

---

For any additional help or questions, please reach out to your team lead or mentor.

