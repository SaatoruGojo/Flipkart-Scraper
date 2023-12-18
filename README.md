# Web Scraping and Flask App for Flipkart Reviews

## Description
This project is a web scraping application built with Selenium and Flask to extract product reviews from Flipkart. The application takes a user-inputted product name, performs a search on Flipkart, and retrieves reviews for the top 10 search results. The scraped data is then displayed on a result page.

## Technology Used
- **Selenium:** Web scraping is achieved using Selenium, a powerful tool for automating web browser interactions.
- **Flask:** The backend of the application is built using Flask, a lightweight web framework for Python.
- **ChromeDriverManager:** Used for managing the Chrome WebDriver, eliminating the need for manual driver downloads.
- **WebDriver:** Selenium WebDriver is employed for automating browser actions and interactions.
- **XPath:** XPath expressions are used to locate and extract elements from the HTML structure of the web pages.
- **Web Template (HTML):** The user interface is designed using HTML templates, allowing users to input a product name and view the scraped reviews.

## Project Overview
The application provides a simple web interface where users can input the name of a product they want to search for on Flipkart. After submitting the form, the application scrapes reviews for the top 10 search results on Flipkart and displays them on a result page.

### Home Page
The home page (`index.html`) includes a form where users can enter the product name they want to search for on Flipkart.

### Result Page
The result page (`result.html`) displays the scraped reviews for the specified product. Each review includes the reviewer's name, rating, comment header, and comment text.

## Screenshots
- [Home Page](screenshots/home.png)
- [Result Page](screenshots/result.png)

**Note:** Screenshots are included in the `screenshots` directory for reference.

## How to Run the Application
1. Install the required Python libraries:
    ```bash
    pip install selenium webdriver-manager Flask
    ```

2. Run the Flask application:
    ```bash
    python app.py
    ```
   The application will be accessible at `http://localhost:5000` in your web browser.

Feel free to explore and modify the code to suit your needs!
