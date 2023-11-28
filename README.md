# Cypress-Cucumber Framework

This project utilizes Cypress and Cucumber for testing purposes. Below are the steps to set up and run the tests locally.

## Setup

1. **Clone Repository:**
git clone <repository_url>
cd <project_directory>

markdown
Copy code

2. **Install Dependencies:**
npm install

bash
Copy code

## Running Tests

To execute the tests, use the following command:
npm test

vbnet
Copy code

## Structure

### Step Definitions

The step definitions are organized into two files:
- `common-steps.js`: Contains steps related to common functionalities.
- `dynamicTable-steps.js`: Contains steps specific to interacting with dynamic tables.

### Feature Files

The feature files define various scenarios to test the application's functionality:
- `dynamic_tables.feature`: Includes scenarios testing the dynamic table functionality.

### Pages

The `TGTables` class in `pages.js` holds methods to interact with different elements on the page, making the tests more readable and maintainable.

## Usage

Modify and extend step definitions and feature files to cover additional test scenarios. Use the `TGTables` methods to interact with the application elements.

---

Ensure your environment meets the necessary requirements and follow these steps to set up and run the tests effectively.
