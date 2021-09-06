# Wikipedia Data Analysis 

This analysis consists of using big data tools to answer questions about datasets from Wikipedia. There are a series of analysis questions, answered using Hive and MapReduce. The tools used are determined based on the context for each question. The output of the analysis includes MapReduce jarfiles and .hql files so that the analysis is a repeatable process that works on a larger dataset.

## Features
- Process the downloaded data analyze the datasets.
- Find, organize, and format pageviews on any given day.
- Follow clickstreams to find relative frequencies of different pages.
- Find the different way to analyze the most internal search link fraction of hotel california.

## TECHNOLOGY USED  
- Hadoop

-  HDFS

-  Yarn

-  MapReduce

-  Hive

-  Python

-  Git/GitHub

## Data Definations :
-  For Problem Statement 1, 4 & 5 we need to Download jan 20, 2021 DataSet.

-  eg: fr.b 1-Naphthol 1 737

## Data Explanation :
-  domain_code: fr.b

-  page_title: Naphthol

-  count_views: 1

-  total_response_size: 733

## Types Of Data :
-  wikibooks: ".b"

-  wiktionary: ".d"

-  foundationwiki: ".f"

-  mobile sites: ".m"

-  wikinews: ".n"

-  wikiquote: ".q"

-  wikisource: ".s"

-  wikiversity: ".v"

-  wikivoyage: ".voy"

-  mediawikiwiki: ".w"

-  wikidatawiki: ".wd"

## For Problem Statement 2 & 3 we need to download Jan 2021 month DataSet 
-  eg: other-search Camp_Tawonga external 183

## Data Explanation 
-  prev: the result of mapping the referrer URL to the fixed set of values described above

-  curr: the title of the article the client requested

-  type: describes (prev, curr)

-  n: the number of occurrences of the (referrer, resource) pair

## Problem Statement 
1.Which English wikipedia article got the most traffic on January 20,2021?

2.What English wikipedia article has the largest fraction of its readers follow an internal link to another wikipedia article?

3.What series of wikipedia articles, starting with Hotel California, keeps the largest fraction of its readers clicking on internal links?

4.Find an example of an English wikipedia article that is relatively more popular in the Americas than Germany.

5.Find which device generate the most traffic on the English Wikipedia Article.


## Reference
-  Pageviews Filtered to Human Traffic

https://wikitech.wikimedia.org/wiki/Analytics/Data_Lake/Traffic/Pageviews

-  Monthly Clickstream

https://meta.wikimedia.org/wiki/Research:Wikipedia_clickstream
