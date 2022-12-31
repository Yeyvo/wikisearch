# TP WOOGLE

## II/ Crawling the data

1. the wikipedia category that will be crawled is : Biology
2. a file named "wiki.lst" and the number of pages crawled by depth
3. wiki.lst contains all titles of the crawled pages

## III/ Downloading the data

1. batch are of size 3000
2. the API of wikipedia used is "https://en.wikipedia.org/wiki/Special:Export"
3. 
4. By going to the API page in the browser, and reading the documentation paragraph, we can see that the pages will be encoded in a special XML format, which is the "wiki" language, which also can be then imported into another wiki running MediaWiki (le moteur de wiki qui alimente Wikipédia).

## IV/ Parsing the data

1. The two matrices are encoded using dictionaries. (what is the name of this encoding)?
2. The links are encoded using an href attribute in an "a" tag in the wiki language.
3. See the parsexml.py file (the cleanExtLinks regular expression)