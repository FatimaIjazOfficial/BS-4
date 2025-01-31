# BeautifulSoup Web Scraping Project

This project demonstrates the use of BeautifulSoup for web scraping in Python. It includes various techniques to extract information from HTML files.

## Prerequisites

Make sure you have the following libraries installed:

- `requests`
- `beautifulsoup4`
- `lxml`

You can install them using pip:

```sh
pip install requests beautifulsoup4 lxml
```

## Main BeautifulSoup Script

### Description

This script demonstrates basic web scraping techniques using BeautifulSoup. It includes reading an HTML file, parsing it, and extracting various elements from it.

### Usage

1. **Read HTML File:**
   - The script reads an HTML file named `website.html` from the local directory.

2. **Parse HTML:**
   - The HTML content is parsed using BeautifulSoup, allowing you to navigate and search the HTML tree structure.

3. **Extract Data:**
   - The script demonstrates different ways to extract data from the HTML, such as:
     - Finding the first occurrence of a tag (e.g., `<title>`, `<a>`, `<p>`).
     - Finding all occurrences of a tag (e.g., all `<a>` tags).
     - Extracting text and attributes from tags.
     - Using CSS selectors to find elements by ID, class, or tag.

### Example Scenarios

- **Extracting the title of the webpage.**
- **Finding and printing all anchor (`<a>`) tags.**
- **Extracting and printing the text and href attributes of all anchor tags.**
- **Using CSS selectors to find elements by class or ID.**

---

## Movie Data Script

### Description

This script scrapes a webpage to get a list of movie titles and saves them to a text file.

### Usage

1. **Fetch Webpage:**
   - The script makes an HTTP request to a specified URL containing the list of movies.
   - It fetches the HTML content of the webpage.

2. **Parse HTML:**
   - The HTML content is parsed using BeautifulSoup to locate and extract the relevant movie titles.

3. **Extract Movie Titles:**
   - The script finds all movie titles by searching for specific HTML tags and classes.
   - The extracted movie titles are stored in a list.

4. **Save to File:**
   - The script reverses the order of the movie titles and saves them to a text file named `movies.txt`.

### Example Scenarios

- **Fetching and parsing a list of the best movies from a webpage.**
- **Extracting and reversing the order of movie titles.**
- **Saving the movie titles to a text file for further use or analysis.**

---

## Hacker News Script

### Description

This script scrapes the Hacker News website to find the most upvoted article.

### Usage

1. **Fetch Webpage:**
   - The script makes an HTTP request to the Hacker News website.
   - It fetches the HTML content of the webpage.

2. **Parse HTML:**
   - The HTML content is parsed using BeautifulSoup to locate and extract relevant information about articles.

3. **Extract Article Titles and Links:**
   - The script finds all article titles and their corresponding links.
   - The extracted titles and links are stored in lists.

4. **Extract Upvotes:**
   - The script finds the number of upvotes for each article.
   - It determines the article with the highest number of upvotes.

5. **Print the Most Upvoted Article:**
   - The script prints the title, upvotes, and link of the most upvoted article.

### Example Scenarios

- **Fetching and parsing the latest articles from Hacker News.**
- **Extracting titles, links, and upvote counts for each article.**
- **Identifying and printing the most popular article based on upvotes.**

---

These sections provide an overview and usage instructions for each script, explaining what each part of the code does and how it works, without including the actual code snippets.
