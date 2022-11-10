# project_03

Project instructions can be found [here](https://github.com/mikeizbicki/cmc-csci040/tree/2022fall/project_03)

## Project Overview
The program created scrapes data from Ebay about items sold taking into account ```name```, ```shipping```, ```status```, ```price```, ```free returns```, and ```items sold```. This is done through parameters ```argparse```, ```requests```, ```BeautifulSoup```, ```json```, and ```csv```.

When trying to use the program, one must add the item they are looking for at the end of the ``` % python3 ebay-dl.py ``` code (if the item has a space in it, use quotation marks instead ex: "gummy worms"). The code defaults to showing 10 webpages, but if someone wants to show more or less, they must add the following code ```--num_pages=5```. Lastly, if you would like to change the format so that it saves to a csv as opposed to a json, this can be done as seen here ```--csv```.

For my project, I used the following 6 commands:
```
$ python3 ebay-dl.py chairs
```
```
$ python3 ebay-dl.py "gummy worms"
```
```
$ python3 ebay-dl.py movies
```

```
$ python3 ebay-dl.py chairs --csv
```
```
$ python3 ebay-dl.py "gummy worms" --csv
```
```
$ python3 ebay-dl.py movies --csv
```



