# Entrata Test Automation

This project contains automated tests for the login functionality of the Entrata website using Selenium WebDriver and TestNG.

## Prerequisites
- Java Development Kit (JDK) installed
- Maven installed
- Chrome web browser installed
- ChromeDriver executable for Selenium WebDriver

## Getting Started
1. Clone this repository to your local machine.
2. Set up the ChromeDriver executable path in the 'setUp()' method of 'Entara_TestNG' class.
3. Open a terminal or command prompt and navigate to the project directory.

## Project Structure
- 'Entara_TestNG.java': TestNG test class containing automated login tests for the Entrata website.
- 'chromedriver.exe': ChromeDriver executable for Selenium WebDriver.
- 'pom.xml': Maven project configuration file.

## Test Execution
- The 'setUp()' method initializes the WebDriver, navigates to the Entrata website, and maximizes the browser window.
- The 'testLogin()' method automates the login process by accepting cookies, opening the sign-in page, entering credentials, and switching between browser tabs.
- Test execution results are logged in the console and TestNG-generated reports.
