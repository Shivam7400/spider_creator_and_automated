# Automated Web Scraper and Spider File Creator

This repository provides tools to automate the creation and management of web scraper configurations and spider files. The scripts are designed to streamline the process of setting up web scraping projects by integrating environment variables, XPath mappings, and dynamic file generation.

## Key Features

### 1. Spider File Creator
- **Automated Spider Creation:** Dynamically generates Python files for new spiders based on the provided spider name.
- **Git Integration:** Automatically stages and commits new spider files to your Git repository.
- **Error Handling:** Built-in logging for tracking file creation status and handling errors.

### 2. Web Scraper Configuration
- **Environment Variable Management:** Uses a `.env` file to manage sensitive configurations such as base paths, credentials, and URLs.
- **Predefined XPaths:** Provides structured dictionaries for interacting with various web elements, including domain fields and article-related configurations.
- **Login Automation:** Automates the login process for secured web pages using stored credentials.
- **User Agent Customization:** Allows setting a custom user agent string for more effective web scraping.

### 3. Integration and Flexibility
- **Path Management:** The scripts adapt to the project structure using `Pathlib` and ensure compatibility with different directory setups.
- **Dynamic Execution:** The spider file creator checks for existing files to avoid duplication and writes appropriate git commands for version control.
- **Versatile Web Scraping Setup:** The scraper configuration script handles multiple pages and sources, saving data from a specific web-based dashboard.