# React Native Application End-to-End Testing with Maestro

This repository contains comprehensive Maestro end-to-end tests for a React Native application built using the Ignite boilerplate. The tests cover various aspects of the application, ensuring the robustness and reliability of key functionalities.

## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running Maestro Tests](#running-maestro-tests)
- [Test Scenarios](#test-scenarios)
  - [Authentication (`auth.test.js`)](#authentication-authtestjs)
  - [Navigation (`navigation.test.js`)](#navigation-navigationtestjs)
  - [API Integration (`api.test.js`)](#api-integration-apitestjs)
  - [Forms (`forms.test.js`)](#forms-formstestjs)
  - [Redux State Management (`redux.test.js`)](#redux-state-management-reduxtestjs)
  - [Permissions and Security (`permissions.test.js`)](#permissions-and-security-permissionstestjs)
- [Documentation](#documentation)
  - [Environment Setup](#environment-setup)
  - [Maestro Tests](#maestro-tests)
- [Code Report](#code-report)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

### Prerequisites

Make sure you have the following tools and dependencies installed:

- Node.js and npm
- React Native development environment
- Ignite CLI
- Maestro testing tool

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Nikhil-707/End-to-End-Tests-using-Maestro
   ```

2. **Install dependencies:**

   ```bash
   cd End-to-End-Tests-using-Maestro
   npm install
   ```

## Running Maestro Tests

Execute the following command to run Maestro tests:

```bash
npm test
```

## Test Scenarios

### Authentication (`auth.test.js`)

- Verify user login functionality.
- Test new user registration process.

### Navigation (`navigation.test.js`)

- Ensure proper navigation to the settings screen.
- Validate navigation back from the settings screen.

### API Integration (`api.test.js`)

- Test data fetching from the API.
- Verify correct display of API data in the UI.

### Forms (`forms.test.js`)

- Validate various forms within the application.

### Redux State Management (`redux.test.js`)

- Test Redux state management and actions.

### Permissions and Security (`permissions.test.js`)

- Verify correct handling of camera permission.

## Documentation

### Environment Setup

1. Follow the Ignite boilerplate installation instructions.
2. Set up the React Native development environment.
3. Install Maestro and other necessary testing dependencies.

### Maestro Tests

- Explore the `__tests__` folder for individual test files.
- Each test file covers specific scenarios and features.
- Refer to the documentation within each test file for details.

## Code Report

- View the code report for detailed test results.

## Contributing

Feel free to contribute by submitting issues or pull requests.

