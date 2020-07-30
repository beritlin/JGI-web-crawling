<h1 align="center">Welcome to JGI-web-crawling </h1>
<p align="center">
  <a>
    <img alt="date" src="https://img.shields.io/github/last-commit/:user/:repo" target="_blank" />
  </a>
  <a>
    <img alt="status" src="https://img.shields.io/badge/status-done-lightgrey.svg" target="_blank" />
  </a>
</p>


# JGI-web-crawling

The downloaded fungal genome data from [JGI](http://jgi.doe.gov/) contain only abbreviational species names.
</br> 
To get the full names of fungi, a pipeline for crawlering the species names from the website was built.

##  Demo

<p align="center">
  <img width="700" align="center" src="https://github.com/beritlin/JGI-web-crawling/blob/master/demo.gif" alt="demo"/>
</p>

##  Information

This method requies [ChromeDriver - WebDriver for Chrome](https://chromedriver.chromium.org/) for crawling websites. Please download the version that matchs your google chrome browser.
</br> 
The imported list of fungal sepcies names is in the file: [funnm.txt](https://github.com/beritlin/JGI-web-crawling/blob/master/funnm.txt).
</br>
The following python packages were used:
```python
 pip install selenium 
 pip install bs4 
 pip install pandas 
```

## Author

🥀  **Pei-Yu Lin**
- Github: [@beritlin](https://github.com/beritlin)
