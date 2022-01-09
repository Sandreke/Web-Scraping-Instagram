# Web-Scraping-Instagram


This code is used to automatically obtain images by web scraping [Instagram](https://www.instagram.com/) with [Selenium](https://selenium-python.readthedocs.io/) in Python.

The required input will only be a hashtag, in this case, [Clairo](https://es.wikipedia.org/wiki/Clairo) will be used as an example to show the step-by-step process, since we do not know which Instagram pages contain Clairo's images.

In this way, the workflow will be to log into Instagram, avoid alerts, search for the hashtag, obtain the links of the posts that contain the hashtag, obtain the profiles that published these posts (because there are pages that publish especially about a certain person or thing in general), obtain the links of the posts of these profiles, obtain the links of the images within the post and, finally, download and save the images in a certain directory.
