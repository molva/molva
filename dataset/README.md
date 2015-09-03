## Twitter IDs

Twitter IDs are stored in files ```tweets_<date>_ids.txt.gz``` and contain Twitter IDs per given day.

## Sample of Tweets

Sample of Tweets fetched during on 2015/08/01 is stored in two files: 

* ```tweets_20150801_raw_50k.tsv.gz``` 
* ```tweets_20150801_stemmed_50k.tsv.gz```

```tweets_20150801_raw_50k.tsv.gz``` has following columns: ```TwitterID``` and ```Tweet Text```. 
Multiline Tweet is broken down in several lines, each starting with Tweet ID. It contains 50k Tweets.

```tweets_20150801_stemmed_50k.tsv.gz``` contains stemmed Tweets. There is no Tweet ID in this file. 
