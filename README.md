# THE-WEB-SCRAPER-PROJECT-
With the GUI Fetches and display Html / IP from URLs using request /socket 


 Web Scraper with IP Resolution

A modern, user-friendly desktop application built with Tkinter that allows users to fetch and view web page data, resolve domain names to IP addresses, and manage a history of scraped data using an SQLite database. The application features a clean, themed interface and supports saving and viewing previous scraping sessions.

 Features

-URL Input & Fetching: Enter a URL to retrieve its HTML content.

-IP Resolution: Automatically resolve the domain to its IP address, hostname, and aliases.

-View HTML Content: Display fetched HTML content within the app.

-Data Saving: Save current scrape data to a local SQLite database.

-View History: Browse previous scraping records with detailed HTML previews.

-Clear Data & History: Reset current fields or clear entire history.

-Modern Theme: Uses `ttkthemes` for a sleek, modern look.

Requirements

- Python 3.x
- `tkinter` (comes pre-installed with Python)
- `requests`
- `ttkthemes`
- `sqlite3` (comes with Python)

Install required third-party libraries via pip:

bash
pip install requests ttkthemes


Getting Started

Cloning or Downloading

Download or clone this repository to your local machine.

Running the Application

Navigate to the directory containing `web_scraper.py` and run:

bash
python web_scraper.py

 Usage

1.Enter URL: Type or paste the website URL into the input box. You can omit `http://` or `https://`; the program will add it automatically.

2.Fetch Data: Click "Fetch Data" to retrieve the HTML content and resolve IP info.

3.View Results:
   - IP info appears in the top text box.
   - HTML content appears in the lower text box.

4.Save Data: Click "Save to DB"to store the current data in the local database.

5.View History: Click "View History"to see all previous records, with the ability to view HTML previews.

6.Clear Data: Clears current inputs and fetched data.

7.Clear History: Deletes all stored records from the database.

Features Details

Database Management

- Stores URL, domain, IP address, hostname, timestamp, and HTML content.

- View previous records with detailed HTML previews.

- Clear entire history if needed.

IP Resolution

- Resolves domain to IP address.
- Retrieves hostname and aliases via reverse DNS lookup.
- Handles errors gracefully if resolution fails.

Notes

- Ensure you have an active internet connection for fetching web pages and resolving IPs.

- Large HTML content may take some time to load.

- The application is designed for Windows, macOS, and Linux environments with Python 3 installed.

---

License

This project is provided for educational purposes. Feel free to modify and enhance it as needed.

---

 Contact

For questions or contributions, please open an issue or contact the author.


Enjoy web scraping with ease and modern aesthetics!