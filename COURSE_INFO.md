# Big Data Analytics with Hadoop and Spark

This course if offered by the BigData@Chalmers initiative under the Swedish e-Science Education (SeSE) and supported by Chalmers e-Science Center.

## Overview

Last few years have seen significant advances in the technologies for data collection, data transmission and storage of data. For the first time in the history, thanks to these technologies, we are at a position where we can instrument a scientific phenomenon, or a business workflow, at a very fine granularity and the collect the required data for the relevant time period. This simple approach can be used for diverse phenomenon – evolving traffic patterns in a city, or how social media plays a part in enhancing/diminishing a brand, or how a protein will fold and impact their function. Think of it as the technology has given us a ringside seat to observe the phenomenon in an unprecedented detail.

## Details

**Dates:** Mon 30th May 2016 to Fri 3rd June 2016

**Location:** Chalmers Conference Building, Campus Johanneberg (room Ascom)

**Schedule:**
  Mon: Course Introduction
  Tue: Introduction to Apache Spark - Architecture, Spark SQL, Graph data processing (Lecture and Applications)
  Wed: Data Exploration and Visualization (Exercises)
  Thu: [Analytics with Spark and MLlib](https://github.com/bdexp/big-data-analytics-2016/blob/master/Day%204%20-%20Analytics/BD2016%20Course.pdf) (Lecture and Exercises)
  Fri: [Data Streaming](http://www.slideshare.net/VincenzoGulisano/data-streaming-in-a-nutshell-and-sparks-window-operations), Recap and Discussion

## Home Assignments

Deadline: 19/6
Submission: By email

### Movie Recommender System: Complete Day 4 - Analytics Exercise 2

1. Train a movie recommender system. Use the MovieLens dataset (ratings.csv) and append some ratings of movies you have seen. You can follow this guide.

2. From the model, extract the user features (model.userFeatures()) and cluster them in 20 clusters. Where did you end up? Can you find something interesting from that cluster (you might need to join with other files, e.g. movies.csv) ?


### Summary of Use Cases

Built on the discussions in the last day, write a short summary (2-5 pages) of how data analytics with Apache Spark can be of use within your domain. You can either implement a proof-of-concept application and describe your process or discuss about the future possibilities that exist when utilizing such a tool in your field of research.

## Additional Info

The public cluster together with the Jupyter notebook will be up and running until 9/6. The public S3 bucket will be available during this time as well, however the access ID and secret key to retrieve the data are removed from the notebooks in the Github repo. Otherwise you can find the dataset [here](http://grouplens.org/datasets/movielens/) as well.

### Study Resources

* [Learning Spark by Holden Karau, Andy Konwinski, Patrick Wendell, Matei Zaharia (2015), O'Reilly.](http://shop.oreilly.com/product/0636920028512.do)
* [Spark Documentation](http://spark.apache.org/docs/latest/)
* [GraphFrames](http://graphframes.github.io/)
* [PySpark API](https://spark.apache.org/docs/latest/api/python/)

## Content

The course will progressively cover the steps involved in a typical data science experiment, starting from data ingestion to data visualization. Each day will cover a specific data science concept with lectures and hands on lab sessions.
 
* Data Science Methodology: You will learn an approach for conducting your data science experiment. This will include the high level steps that you need to follow for conducting and validating your experiment. You will also learn of the common pitfalls and gotchas.
* Tool & Technologies: You will get an exposure to the different tools and technologies that should be used for the different steps of the data science experiment, starting from data collection, all the way to data visualization. There will be assignments around Hadoop and Spark, including different ways of exploring data through graphs and machine learning.
* Labs and Hands-on Experience on Big Data Technologies: You will get hands on experience on working with a subset of the big data technologies in a lab setting and you will leave the course with a working big data environment that you could use for your own data science experiments.
 
Course Pre-requisites
* Basic programming knowledge in one scripting language, e.g. Python.
