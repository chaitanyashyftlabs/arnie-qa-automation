# Arnie QA Automation

This repository contains **Playwright automation tests** for the Arnie application.
The framework follows the **Page Object Model (POM)** design pattern.

## Tech Stack

* Playwright
* JavaScript
* Node.js
* GitHub Actions

## Project Structure

```
tests/        → Test cases  
pages/        → Page Object Model classes  
utils/        → Helper functions and utilities  
auth/         → Authentication setup  
```

## Setup

Clone the repository

```
git clone https://github.com/<org-name>/arnie-qa-automation.git
cd arnie-qa-automation
```

Install dependencies

```
npm install
```

Install Playwright browsers

```
npx playwright install
```

## Run Tests

Run all tests

```
npx playwright test
```

Run tests in UI mode

```
npx playwright test --ui
```

## Reports

After test execution, open the Playwright report:

```
npx playwright show-report
```

## Maintainers

QA Automation Team – Arnie Project
