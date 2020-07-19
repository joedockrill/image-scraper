# image-scraper
Image scraper for DuckDuckGo and Google for creating deep learning datasets

This allows you to run a bunch of searches and download images into folders based on label name. \
You can then run a very simple image cleaner in the notebook to delete anything which doesn't belong. \
Then it zips them up so you can download the dataset or transfers it to google drive.

TODO:
- add: option to create a csv file of labels & filenames (also allowing for multi-label searches)
- add: option to create a csv file of labels & URLS (allows much smaller datasets)
- add: DDG options to constrain searches by layout/type/colour etc, if I can ever find what the allowed params to i.js are...  

Credits: \
DDG code from https://github.com/deepanprabhu/duckduckgo-images-api  
