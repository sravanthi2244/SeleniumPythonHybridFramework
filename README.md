# Selenium Python Hybrid Framework

A robust automation framework for testing online store aplications.
-Automated test cases for login, registration, and product search.
- Follows Page Object Model (POM) to separate UI logic from test logic
- Pytest-based test runner with setup and teardown using `conftest.py`
- Allure report generation support.



## Features

- **Selenium with Python** for web automation
- **Pytest** as the test execution framework
- **Page Object Model (POM)** design for maintainable code
- **Allure Reports** for visually appealing test results
- Easily extensible for different online store categories

## Technologies Used

- Python
- Selenium WebDriver
- Pytest
- Page Object Model
- Allure Reporting

## Project Structure

```
├── tests/              # Pytest test cases
├── pages/              # Page object classes
├── utils/              # Utility scripts
├── Reports/            # Allure report output
├── requirements.txt    # Python dependencies
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.x installed
- Google Chrome & ChromeDriver (or another browser/driver)
- [Allure commandline](https://docs.qameta.io/allure/#_installing_a_commandline) installed

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/sravanthi2244/seleniumpythonhybridframework.git
    cd seleniumpythonhybridframework
    ```

2. Install dependencies:
   selenium
   pytest
   allure-pytest
   openpyxl

### Running Tests

To run all tests and generate Allure results:
```bash
pytest tests/ --alluredir=./Reports
```

To view Allure reports:
```bash
allure serve ./Reports
```

## Usage Example

- The framework includes tests for common online store actions (search, add to cart, checkout, etc.)
- Page Object Model makes it easy to add new pages/categories

## License

This project is licensed under the MIT License.

## Notes

This framework is intended for demo/testing practice purposes only.

Target website: https://tutorialsninja.com/demo


---

Happy Testing!
