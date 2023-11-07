# Web Scraping Challenge
Columbia University Bootcamp Week 11 Challenge <br/>


![web_scraping_illustration](https://scrape-it.cloud/assets/blog_img/web-scraping-with-python.png)




## About 
In this project, we explore the power of Python by Web Scraping Websites and gathering data using splinter's browser and bs4's BeautifulSoup. <br/>
Using HTML components, data was gathered, further analyzed and visualized, to get a better grasp of the information.<br/>
To carry the aforementioned tasks, pandas and matplotlib were also utilized. <br/>
This project uses two websites to gather data: <br/>

![mars_news_site](Readme Resources/Screenshot 2023-11-07 at 12.49.37 AM.png) <br/>
[Mars News Website](https://static.bc-edx.com/data/web/mars_news/index.html)<br/> <br/>
![mars_data_table](Readme Resources/Screenshot 2023-11-07 at 12.48.25 AM.png)
[Mars Temperature Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html)<br/>
### Mars News Articles
In the Mars News Website, the article titles and preview text were extracted from every article. <br/>
The information that was scraped from every article was exported into a JSON file (This file can be found in the Files folder).<br/>

### Mars Temperature Data
In the Mars Temperature Website, the components from an HTML table were extracted using a python loop. <br/>
The data was then converted into a Data Frame using pandas. <br/>
The information was further analyzed using pandas aggregate functions. <br/>
Finally, the results were visualized. <br/>

## Table of Contents
[Installation](#installation)  
[Visualization](#visualization)   
[Acknowledgements](#acknowledgements)  



## Installation 
    1. Clone repository on your local machine
    2. Open Jupyter Notebook 
    3. Open .ipynb file
    4. Run all cells
  


## Visualization

![avg_min_temp](Files/avg_min_temp.png) <br/>
![avg_temp_sorte](Files/avg_temp_sorted.png)<br/>
![avg_pressure](Files/avg_pressure.png)<br/>
![temp_over_days](Files/temp_over_days.png) <br/>


## Acknowledgements

* How to export a JSON file: [Stack overflow](https://stackoverflow.com/questions/12309269/how-do-i-write-json-data-to-a-file) <br/>
* Looping through an HTML table: [Data Science Central](https://www.datasciencecentral.com/how-to-use-python-to-loop-through-html-tables-and-scrape-tabular-data/) <br/>

