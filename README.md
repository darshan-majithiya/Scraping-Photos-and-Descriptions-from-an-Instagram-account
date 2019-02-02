# Scraping-Photos-and-Descriptions-from-an-Instagram-account
It can be used to scrape photos from any Instagram account (Offcourse, only if you follow that account or it's an open account) and write the photo description for each photo to excel sheet.

## Dependencies
You need Python 3.x on your system to run this program.

There are some handful of libraries you need to install beforehand. You can easily install them using python package manager **pip**.

- requests 2.x
- BeautifulSoup 4.x
- lxml 4.x (For parsing the data. Although, you can use any other parser as well.)
- Selenium 3.x

Also, Browser Driver will be required to control it. I’ll be using ChromeDriver for Linux.
You can download ChromeDriver at the following page, select the latest release and then download the package dedicated to your operating system (Linux, Mac, or Windows) into your machine: https://sites.google.com/a/chromium.org/chromedriver/downloads.

If you prefer any other browser or are operating on any other OS, then you can use driver exclusive to that browser and to that OS. You can change the path to the driver in instaScraper.py by changing the value of self.driver.


You can read more about the execution of this program on [Darshan Majithiya - medium](https://medium.com/@darsh2115/scraping-photos-and-descriptions-from-an-instagram-account-using-python-11c5a1ce1e81).

