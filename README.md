# Chart Builder Testing & CI/CD Pipeline

This project focused on implementing automated testing and a CI/CD pipeline for a web application that allows users to build charts (line, scatter, and bar charts) using the QuickChart API.

The application allows users to:
- Enter chart data
- Configure chart options
- Generate charts
- Save charts to a gallery

The primary goal of the project was to apply software engineering practices including automated testing, continuous integration, and team development workflows.

---

## My Contributions (sorensri)

My work on this project focused on UI integration testing and test environment setup.

Contributions include:

- Implemented integration test for chart generation workflow
- Implemented integration test verifying “clear chart data” behavior
- Implemented integration test verifying alert behavior for insufficient data
- Implemented integration test for adding values in the chart builder UI
- Installed and configured `jest-dom` testing utilities

These tests were written using Jest and DOM Testing Library to simulate user interaction with the application interface.

---

## Testing Stack

- Jest
- DOM Testing Library
- JSDOM
- Cypress (project-wide)
- GitHub Actions (project-wide)

---

## Repository Context

This repository is a fork of a team project completed for a software engineering course focused on:

- Automated testing strategies
- CI/CD pipelines
- Pull-request based workflows
- Code review practices

Original repository:
https://github.com/OSU-CS362-W24/final-project-362finalproj

---

## Running the Project

Install dependencies:
```bash
npm install
```

Start the application:
```bash
npm start
```

Run tests:
```bash
npm test
```
