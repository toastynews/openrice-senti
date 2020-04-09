# openrice-senti
Scraped reviews from OpenRice for sentiment analysis. Formatted to use with BERT.

## Description
The files contain random reviews from the OpenRice Hong Kong section. 
These are reviews of restaurants in Hong Kong. The dataset is filtered to contain
only those written in Hong Kong Cantonese (Hongkongese).

The files are tab-separated with sentiment in column one and review text in
column two. The classes are:
* smile
* ok
* cry

In OpenRice, the number of "smile" reviews far outnumber the other two. This dataset
is exactly balanced with 1/3 from each class.
