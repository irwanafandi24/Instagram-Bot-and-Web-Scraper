# Instagram Bot and Web Scraper
This repository contains [web scraper](https://github.com/irwanafandi24/Instagram-Bot-and-Web-Scraper/tree/master/Amazon%20Webscraper) sample code (scrape the data from a website then save it into csv format) and my [instagram bot](https://github.com/irwanafandi24/Instagram-Bot-and-Web-Scraper/tree/master/Instagram%20Bot) (follow, like 3 post, comment in the first post, unfollow, direct message - automatically) using instaloader, selenium, and webdiriver.

<b>Note:</b> I use <i>python 3</i> and <i>Jupyter Notebook</i> for this project.

# Getting Started

### Let's Install
<b><i>Install Instaloader</i></b>
```sh
pip3 install instaloader
```
Upgrade Instaloader to its current version.
```sh
pip3 install --upgrade instaloader
```
You can use this library to scrape many data from Instagram like post, insta story, comment, etc. So you can explore it by yourself on [Istaloader website](https://instaloader.github.io/index.html).<br><br>
<b><i>Install Selenium</i></b>
```sh
pip3 install selenium
```
Check the selenium version (focus on its location, we will put WebDriver in that <b>location</b>).
```sh
pip3 show selenium
```
Download WebDriver:<br> 
- Firefox for windows [geckodriver](https://github.com/mozilla/geckodriver/releases)<br>
- Chrome for windows [chromedriver](https://chromedriver.storage.googleapis.com/index.html?path=87.0.4280.20/)
<br>Extract the folder, then put it into your python installation folder (copy your selenium location).
```sh
C:\Users\moham\AppData\Local\Programs\Python\Python38-32
```
Just visit this [Selenium website](https://selenium-python.readthedocs.io/installation.html) for the details.

### Other Support Library
- pandas (dataframe)
- random
- re (regular expression)
- decimal (str to decimal)
- time 
- tqdm (progress bar)

🎉 Congrats, you ready to create your own Bot or Scraper now :)
