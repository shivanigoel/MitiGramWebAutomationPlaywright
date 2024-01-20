Mitigram Assignment - Playwright Test Scenarios
Introduction
This repository contains Playwright test scenarios to validate the Login flow of the Mitigram portal, the Careers page, and the Newsletter section.

Supported Operating Systems
Windows
Linux
Mac
Folder Structure
src: Root package of the core components of the framework.
pages: Page Classes following the Page Object Model (POM) design pattern.
steps: Steps classes containing methods encapsulating interactions and validations.
test: Test cases.
utils: Utility classes.
Prerequisites
Ensure the following dependencies are installed before building and running the test suite:

Node.js

Check Node.js Installation
Run the command node -v in a terminal. It should display the installed Node.js version (e.g., v21.5.0).
Configure Test Suite (Before Run)
Open the file config/config.json.

Adjust the following configurations:

PLAYWRIGHT_TIMEOUT: Timeout configurations used in Playwright.
BROWSER: Browser configuration (e.g., 'chromium', 'firefox'). Default is 'chromium'.
Build and Run Locally
Install Dependencies
Run the command npm install in a terminal from the project root directory to install the dependencies.

Execute Testcases
Execute Full Suite
Run the command npm test in a terminal from the project root directory.

Execute Specific Test Cases
Run the command npx playwright test {path to the test file} in a terminal from the project root directory. Update {path to the test file} according to the test case you want to run.

npx playwright test src/test/careersPageTests.ts

View Test Results Report
Open the file testReports/testResults.html in a web browser to view the HTML test results report.

View Test Logs
Open the file logs/mitigram-playwright-test.log to view the outputs logged to the file.
