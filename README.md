# Web-Scraping with selenium

HTML websites can be scraped using standard Python packages such as Requests and BeautifulSoup. However, these methods often fail on websites that were programmed in JavaScript, a language used to create dynamic web applications.

This project shows what to do when HTML-based web scraping methods fail. Specifically, it uses a special Python module called Selenium which allows the user to initiate a web "driver" that can navigate dynamic web applications. Using this driver, a website programmed in JavaScript can be scraped for content.

Documentation for Selenium can be found here: http://selenium-python.readthedocs.io/

You will also need to install a browser-specific driver.

Chrome: https://sites.google.com/a/chromium.org/chromedriver/

Firefox: https://developer.mozilla.org/en-US/docs/Mozilla/QA/Marionette/WebDriver
