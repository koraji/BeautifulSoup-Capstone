# Web-Scrapping using beautiful soup 

This is developed as one of Algoritma Academy Data Analytics Specialization using capstone Projects. The deliverables of this project is a Simple flask dashboard that can visualize the data we get from web scrapping. For step by step guide, you can check out my git. [Click here](https://github.com/t3981-h/Webscrapping-with-BeautifulSoup "Webscrapping with Beautiful Soup").

## Dependencies

- beautifulSoup4
- pandas
- matplotlibs
- flask
- altair

## Rubics

* Doing a request
* Finding the right key to scrap the data
* Extracting the right information
* Data wrangling
* Creating data.Frame
* Implement it on flask dashboard

## What you need to do

* You can clone this repo.
* File in this repo is a skeleton that you can use for making a simple flask dashboard.
* You can fill the blank part at the skeleton.
* You can try to scrap the information from this sites : (link)
* fill function `scrap` with scrapping process. You need fill this part with the key to get the infromation from the webpage.

```python
table = soup.find(...)
tr = table.find_all(...)
```

* Then you can extract the infromation per row with looping.
* Save here to save your scrapping data as csv.

```python
df = pd.DataFrame(name of your tupple, columns = (name of the columns))
```

* Lastly you can use your scrap function at function for making table and chart. Fill the parameter with the link.

```python
df = scrap(...) #insert url here
```

* You also can play with the ui at `index.html` which you can follow the comment to know which part you can change.
