# image-scraper
Image scraper for DuckDuckGo and Google for creating deep learning datasets

This allows you to run a bunch of searches and download images into folders based on label name.
You can then run a simple image cleaner within the notebook to delete anything which doesn't belong.
Then it zips them up so you can download the dataset or transfers it to google drive.

You can also use it to create URL/label CSV files which is useful if you want to have a massive
dataset with many thousands of files but don't want to host it or send it around yourself.
It would then be up to your users to download the files themselves.

Credits:
------------------------------------------------------------------------------------------
- [Deepan Prabhu Babu](https://github.com/deepanprabhu/duckduckgo-images-api) for the base DuckDuckGo code
- Iegor Timukhin for pointing out that the search constraints param was sitting under my nose the whole time

```
History:
------------------------------------------------------------------------------------------
11/08/20  chg: rewrite of image cleaner. includes pagination and is 10x faster than before.
03/08/20  fix: exception handling for failed downloads (403, 404 etc)
03/08/20  add: DDG search params for image size, image type, image layout and image color.
14/07/20  rel: version 1
```
