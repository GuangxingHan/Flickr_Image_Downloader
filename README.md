# Flickr_Image_Downloader
A tool to download Flickr images

The tool supports downloading image urls of all galleries from a flickr user, and provides a simple BoW based text-matching method for matching flickr image titles/desscriptions to a pre-defined database.

The code is used to build an artwork dataset for instance-level recognition. For more details, please visit https://ilr-workshop.github.io/ECCVW2020/


## Special Thanks

[Python Flickr API](https://github.com/alexis-mignon/python-flickr-api) is used to build our Flickr downloader.

NLTK and [fuzzywuzzy](https://github.com/seatgeek/fuzzywuzzy) are used for text preprocessing.
