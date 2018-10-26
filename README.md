# faroese-corpus

Faroese corpus taken from Wikipedia dumps.

This repository will contain corpus of Faroese language taken from [the content dump](https://dumps.wikimedia.org/fowikisource/latest/) of [Faroese Wikipedia](https://fo.wikipedia.org).

## `pipenv`

This project uses `pipenv`. [How to install `pipenv`](https://pipenv.readthedocs.io/en/latest/install/#pragmatic-installation-of-pipenv).

## Dependencies

In order to read 7zip archives (used by Wikia's XML dumps) you need to install [`libarchive`](http://libarchive.org/):

```
pipenv install
sudo apt install libarchive-dev
```

## Links

* [ FTS - Färöisk textsamling](https://spraakbanken.gu.se/korp/?mode=faroe)
* [Current XML dump](https://dumps.wikimedia.org/fowikisource/latest/fowikisource-latest-pages-meta-current.xml.bz2) (~14 MB)
* [MediaWiki XML dump format](https://www.mediawiki.org/wiki/Help:Export#Export_format)


## Scripts

Run `pipenv shell` before running them.

### `words_from_dump.py`

Shows the longest words taken from the dump:

```
1 llanfairpwllgwyngyllgogerychwyrndrobwllllantysiliogogogoch - 58
2 samvinnufelagiðsamvinnufelagnum - 31
3 krabbameinsgranskingarstovnurin - 31
4 southernplayalisticadillacmuzik - 31
5 barnabókavirðislønavinnararnar - 30
6 norðurlandameistarakappingini - 29
7 sjónvarpsundirhaldssendingini - 29
8 bókmentakritikaraheiðurslønir - 29
9 einstaklingaítróttargreinunum - 29
10 vegsúkklukappingarmeistaranum - 29
```
