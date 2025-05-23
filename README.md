# Cross-Browser Selenium Automation for SauceDemo

This project contains automated UI tests for [saucedemo.com](https://www.saucedemo.com), implemented using Python and Selenium WebDriver. The tests verify core e-commerce interactions such as login, cart updates, and product navigation.

## Features

- Automated testing of five user flows:
  - Login with valid credentials
  - Add product to cart
  - Verify cart icon update
  - View product detail page
  - Logout
- Executed using both BrowserStack and Sauce Labs
- Parallel test execution supported on BrowserStack
- Test environment matrix generation using Python

## Files

- `demo cart selenium.ipynb`: Main notebook containing test logic and configuration
- `.gitignore`: Configured to track only the primary notebook

## Requirements

- Python 3.x
- Selenium
- Valid BrowserStack or Sauce Labs credentials

## Usage

1. Install dependencies:
2. Add your credentials in the notebook where specified.
3. Run the notebook in JupyterLab or VS Code.

## Notes

- BrowserStack allowed full parallel execution under the free tier.
- Sauce Labs was limited to one parallel session with a 60-minute trial cap.
- Execution artifacts (logs, screenshots, videos) are viewable in respective dashboards.
