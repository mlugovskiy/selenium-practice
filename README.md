# selenium-practice
This is an example of testing framework containing a number of tests for the test site http://automationpractice.com/
Tests run for two browsers: Chrome and Firefox.
## Pre-requisites
1. Chrome and Firefox browsers should be installed
2. Browser drivers chromedriver.exe and geckodriver.exe should be placed locally.
In order for Selenium Webdriver to be able to find chromedriver.exe and geckodriver.exe, the path to the executables should be added to the PATH environment variables.
## Based on
1. Java
2. Selenium
3. TestNG
4. Page Object Model
5. Allure Framework for reports
## Usage
To execute tests run
```mvn clean test```
