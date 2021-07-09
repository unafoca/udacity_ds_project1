## Table of content


1. [Installation](https://github.com/unafoca/udacity_ds_project1#Installation)
2. [Project Motivation](https://github.com/unafoca/udacity_ds_project1#Project-Motivation)
3. [File Descriptions](https://github.com/unafoca/udacity_ds_project1#File-Descriptions)
4. [Results](https://github.com/unafoca/udacity_ds_project1#Results)
5. [Licensing, Authors, Acknowledgements](https://github.com/unafoca/udacity_ds_project1#Licensing-Authors-Acknowledgements)

## Installation
In order to run the codes successfully, you'll need to install below packages:<br/>

* pandas (1.1.*)
* numpy (1.18.5)
* matplotlib (3.2.2)
* nltk (3.5)
* seaborn (0.10.1)
* dataframe_image (0.1.1)
* wordcloud (1.8.1)<br/>

After that the code should run with no issues using Python versions 3.*.

## Project Motivation
For this project, I was interestested in using the latest available data (Apr'21) for NYC from Inside Airbnb website to better understand:

1. What's the distribution of listings within NYC? How much more should you expected to pay if you want to sleep in Manhattan and is it worth it?
2. When do people usually visit NYC?
3. What are the most used words by the hosts when describing their properties in NYC?

The analysis is published in Medium [here](https://cq-w.medium.com/travelers-to-the-big-apple-14e3221f3f0b).

## File Descriptions
There is one notebook for the codes used to perform the analysis and 3 csv files downloaded from Inside Airbnb as the data sources. Listings.csv and listings_sum.csv are both snapshots of listed resources as of the time the data was collected where listings.csv contains more information than the other. Reviews_sum.csv is a list of reviews with their objects and date only. There's also a reviews.csv dataset with more comprehensive information but we won't need it for this anlysis. Other pictures are output from the codes and are used in the published analysis for demonstration purposes.

## Results
The main findings of the code can be found at the post available [here](https://cq-w.medium.com/travelers-to-the-big-apple-14e3221f3f0b). Below is the summary of the findings:

1. Most of the Airbnb listings in NYC are in Manhattan. You’ll need to pay for the premium if you want to enjoy the convenience. But be aware, the experience might not be as nice as expected.
2. Most visitors come to the Big Apple in September or October. If there’s some flexibility in your plan, come in January or February, as it should be less crowded and therefore cheaper.
3. People tend to emphasize the spaciousness and location of their properties in NYC. However, manage your expectation as the reference is other NYC apartments :)

## Licensing, Authors, Acknowledgements
Thanks to Inside Airbnb for the data. The analysis won't be possible otherwise. You can find the descriptive information and data for other cities [here](http://insideairbnb.com/about.html).

Other references:

* [Medium post](https://medium.com/@gianpaul.r/tokenization-and-parts-of-speech-pos-tagging-in-pythons-nltk-library-2d30f70af13b) for NLTK
* [Medium post](Time Series Analysis. Trends, Patters, Seasonality and… _ by Athul Anish _ The Startup _ Medium) for analyzing seasonality
* [Github repo](https://github.com/amueller/word_cloud) for wordcloud
* [Wordcloud documentation](https://amueller.github.io/word_cloud/auto_examples/frequency.html)
