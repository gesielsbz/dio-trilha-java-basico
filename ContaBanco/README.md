# ContaBanco Project

## Overview
ContaBanco is a simple Java application that simulates basic banking operations such as creating accounts, depositing and withdrawing funds, and transferring money between accounts. This project is designed to demonstrate object-oriented programming principles and basic Java functionalities.

## Project Structure
```
ContaBanco
├── src
│   ├── Main.java
│   ├── models
│   │   └── Conta.java
│   ├── services
│   │   └── ContaService.java
│   └── utils
│       └── Utils.java
├── lib
├── .gitignore
├── README.md
└── pom.xml
```

## Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- Apache Maven

### Installation
1. Clone the repository:
   ```
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```
   cd ContaBanco
   ```
3. Build the project using Maven:
   ```
   mvn clean install
   ```

### Usage
1. Run the application:
   ```
   mvn exec:java -Dexec.mainClass="src.Main"
   ```
2. Follow the on-screen instructions to interact with the banking system.

## Features
- Create a new bank account
- Deposit and withdraw funds
- Transfer money between accounts
- Validate account numbers

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any enhancements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.