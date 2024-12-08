# Password Generator

This is a simple Java application that generates secure alphanumeric passwords, saves them to a JSON file, and allows users to specify a username for each generated password. This project uses secure random password generation and logs the process for monitoring.

## Features
- **Generate Secure Passwords**: Generates random, secure passwords using a mix of characters.
- **Save Passwords to JSON**: All generated passwords are saved to a JSON file (`generated_passwords.json`).
- **Logging**: The process is logged using a dedicated logger, providing information about password generation and errors.
- **User Input**: The user is prompted to enter a username or email to associate with each generated password.

## Prerequisites

Before running the application, ensure you have the following:

- Java Development Kit (JDK) installed (version 8 or higher).
- Maven (for dependency management and building the project).

## Getting Started

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/shlok-nahar/passwordgenerator.git
cd passwordgenerator
```

### 2. Build the Project

```bash
mvn clean compile
```

### 3. Running the Application

```bash
java -cp target/classes com.password.generator.Main
```