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
- HDP Sandbox 3.0.1

- VirtualBox 6.1.26

-  MapReduce

-  Hive

-  Python

-  Git/GitHub

## Getting Started

- Enable Enable Virtualization in the Computer from bios
- Install virtual box
- Install HDP inside VirtualBox
- Open the Ambari dashboard
- copy file from local computer to HDP scp -p 2222 <FILE> <user>@<ip>:~/

## Usage
To run hive command hive -f <FILE.sql>

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

## License
