# Clothing Price Analysis Tool

## Project Overview
This tool performs a **comprehensive analysis of clothing prices** across various online retailers, focusing on different clothing categories, brands, and quality considerations. It scrapes data from multiple websites, allowing users to filter, search, and sort products based on criteria like price, brand, and popularity. Additionally, users can receive email notifications about hot deals.

## Features
1. **Web Scraping:** Gathers product information from different retailers, including image URLs, product URLs, prices, and titles.
2. **Product Search & Spell Check:** Allows users to search for products based on title and provides suggestions if no exact match is found.
3. **Sorting:** Sorts products by title, price, or brand in ascending or descending order.
4. **Inverted Indexing:** Filters products based on specified criteria like brand or price range.
5. **Search Frequency:** Tracks the frequency of product searches and provides this information to users.
6. **Word Completion:** Suggests word completions as the user types based on available product titles.
7. **Email Notifications:** Sends hot deals via email based on user input.
8. **Graphical User Interface (GUI):** Provides a user-friendly interface to enhance interaction.

## Technologies Used
- **Java**: Main programming language used.
- **Selenium**: For web scraping.
- **Apache POI**: For Excel file handling.
- **Trie Data Structure**: For word completion.
- **Merge Sort**: For product sorting.
- **B-tree**: For filtering products by price.
- **Regular Expressions (RegEx)**: For email validation.

## How to Run the Project
1. **Prerequisites**: 
   - Java JDK 1.8 or above
   - Apache POI library
   - Selenium WebDriver
   - Email SMTP server for sending notifications (e.g., Gmail)

2. **Setup**:
   - Clone the repository: 
     ```bash
     git clone https://github.com/your-username/Clothing-Price-Analysis.git
     ```
   - Import the project into your preferred Java IDE.
   - Add the required libraries (Selenium, Apache POI) to the classpath.

3. **Execution**:
   - Run the main Java file (`Main.java`).
   - Follow the on-screen prompts to search, filter, and receive notifications for clothing items.

## Contributors
- Jayati Sakervala
- Tirthkumar Patel
- Jinal Barot
- Rajvee Shah
- Somashekar Venkatamadegowda
