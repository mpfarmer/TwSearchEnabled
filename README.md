# TwSearchEnabled

A Python scripts run you multiple (No. keywords * No. days) browsers
with auto-login and auto-scroll-down features
for crawling historical data (tweets) by keywords

## Getting Started

1. Check out the tweetsearch.py and read the comments for understanding
2. Create username.txt and password.txt for storing credentials
3. Setup the keywords in the code as you like, current keywords are 'Android' and 'iOS'
4. Setup the Start date and End date in the code

### Prerequisites

[Python3](https://www.python.org/downloads/)
[pip](https://pip.pypa.io/en/stable/installing/) (Optional)
[Firefox](https://www.mozilla.org/en-US/firefox/new/?f=116)
[Mozilla geckodriver](https://github.com/mozilla/geckodriver/releases)
[Selenium](https://pypi.python.org/pypi/selenium)

### Installing

Python3 Link -  https://www.python.org/downloads/
pip Link - https://pip.pypa.io/en/stable/installing/
Firefox Link - https://www.mozilla.org/en-US/firefox/new/?f=116
Mozilla geckodriver Link - https://github.com/mozilla/geckodriver/releases
Selenium Link - https://pypi.python.org/pypi/selenium

Some more guidance:
1. For Selenium installation, follow the Selenium Link above 
or get pip installed and type command below
For Windows user, pip install -U selenium
For OS X user, $ pip3 install -U selenium (or use brew)

2. For geckodriver, please put the executable in a System Path (e.g. under the Python3 folder)

## Built With
1. Command Line
python tweesearch.py (Windows)
$ python3 tweetsearch.py (Linux or OS X)
2. Sublime Text3 + Anaconda (My favorite for now)

## Authors

* **Go Code** - *Initial work* - [Co Code](https://github.com/mpfarmer)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

[Marco](https://marcobonzanini.com/2015/03/02/mining-twitter-data-with-python-part-1/)
[Randy Daw-Ran Liou](https://medium.com/@dawran6/twitter-scraper-tutorial-with-python-requests-beautifulsoup-and-selenium-part-2-b38d849b07fe)
[Craig Trim](http://trimc-devops.blogspot.com/2016/03/using-python-and-selenium-to-logon-to.html)

Please feel free to pull request for improvement or questions
