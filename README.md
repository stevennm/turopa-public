</br>
<a href="https://turopa.com.ar/">
    <img src="https://turopa.com.ar/static/main/img/marca.f68316391423.png" alt="Turopa logo" title="Turopa" height="40px" />
</a>
</br>

#### :star: <a href="https://turopa.com.ar/">TuRopa.com.ar</a> is a web application that helps you find and compare clothes from multiple brands* in a single place. :star:

### Technologies used

The project is developed mainly using the <a href="https://www.djangoproject.com/">Django framework</a> and multiple Python scripts. The data for the products is scraped from multiple websites like Zara, Levis, Kevingston, Dexter, John Cook, Quick Silver, Rip Curl, among many others using Beautiful Soup and Selenium. After the data is gathered and processed we load it to a PostgreSQL database hosted by Heroku. (The website is hosted at Heroku)

#### Backend
- Django framework
- PostgreSQL
- Beautiful Soup
- Selenium
#### Frontend
- Bootstrap
- HTML, JavaScript, CSS

### How to use

The website itself is fairly intuitive but in case you don't speak spanish there are multiple ways to find your next outfit:
- The main way of searching for products is using the search box, which is built using the Postgres full-text search engine. (Trigram similarity) 
- You may click on "Productos" on the top right if you want to see all the products in the database sorted randomly.
- You can also click any of the buttons in the main page if you want to prefilter the products page.
- Then you just click on any porduct that catches your attention.

### What's next
This is still a beta release so naturally there are bugs. The priority right now is to find them and fix them. The main objectives in the short term are:
- To improve the search engine.
- To add more brands.
- To improve the filtering section.
- Any tip is welcome.

*brands that are sold in Argentina only
