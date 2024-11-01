# Selenium-Automation-Project-Structure
A Selenium-based automation project template in Java, structured to support scalable and maintainable test scripts. This setup includes the Page Object Model, configurable properties, and basic logging for efficient web testing.


# Selenium Automation Project

This is a template for setting up a Selenium-based automation testing project using Java and Maven. This structure is designed to support scalable and maintainable test automation for web applications, with organized directories for configuration, test scripts, and utilities.

**Key Components**

- src/main/java/pages/: Houses page classes implementing the Page Object Model for easier interaction with web elements.
- src/main/java/utils/: Contains helper classes, e.g., WebDriverManager for driver setup and utilities for logging.
- src/test/java/tests/: Includes test cases, organized into specific test classes.
- BaseTest.java: Sets up common test initialization and teardown functionality.
- config/config.properties: Stores configuration variables (e.g., URLs, credentials, browser options).
- logs/: Stores test run logs for debugging.

**Prerequisites**

- Java 8 or higher installed.
- Maven installed for dependency management.
- Google Chrome or Mozilla Firefox browser installed.
- IntelliJ IDEA (or another Java-compatible IDE) recommended for development.

**Setup Instructions**

- Clone the repository:
git clone https://github.com//tharaka998/Selenium-Automation-Project-Structure.git

cd selenium-automation-project

- Install dependencies: 
Open a terminal in the project directory and run: mvn clean install

- Configuration:

Update config/config.properties with the desired configurations, such as browser type and target URLs.

- Running Tests: You can execute the tests using: mvn test


The TestRunner class is configured to run all test cases in the project.

**Dependencies**
This project uses Maven for dependency management. Key dependencies include:

- Selenium WebDriver for browser automation.
- TestNG or JUnit (as per preference) for test framework support.
- Log4j for logging.
  
Refer to pom.xml for the complete list of dependencies and their versions.

**Folder and File Details**

- config.properties - Centralized configuration file for specifying environment variables, browser settings, and more.
- BaseTest.java - The base class that initializes WebDriver and sets up browser configurations.
- TestRunner.java - Main class for executing all tests within the tests package.

**License**
This project is open-source and available under the MIT License. You are free to use and modify it for your own testing needs.

**Happy testing with Selenium and Java!**
