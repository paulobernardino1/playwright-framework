Automated Web Testing Framework with Playwright and JavaScript

This project implements end-to-end automated testing for web applications using Playwright, JavaScript, and the Page Object Model (POM) design pattern. It covers functional testing, API validation, and visual regression checks to ensure UI consistency and backend reliability.

Technologies Used:

Playwright

JavaScript

GitHub Actions

Key Features:

Visual Regression Testing:

Captures and compares screenshots of web pages to detect unintended changes in the user interface. This ensures that UI updates do not introduce unexpected visual issues.

API Testing:

Validates the behavior of backend services by checking API responses and ensuring they meet expected criteria.

Functional Testing with POM Structure:

Ensures the application behaves as defined in the project requirements. Tests are organized using the Page Object Model to promote reusability and maintainability.

Data-Driven Test Execution:

Allows tests to be run with multiple sets of input data by referencing external test data files, enabling broader coverage with minimal code duplication.

Automation via GitHub Actions:

Integrates the test suite into a CI/CD pipeline using GitHub Actions, ensuring that every code change is automatically verified and does not break existing functionality.

How to Run the Tests:

Clone this repository.

Install dependencies with npm install.

Run the test suite using npm run test.