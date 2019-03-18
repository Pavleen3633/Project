#Project
Ranking Artists/Bands through analysis of yearly Top 100 Songs using Wikipedia web scrapping from years 1970 to 2018
Participant- Pavleen Kaur
Project Notebook is uploaded as data_science_final.ipynb
Access to Notebook through Binder
Click below
[![Binder](https://mybinder.org/badge_logo.svg)](https://hub.mybinder.org/user/pavleen3633-project-yrowjqhd/notebooks/data_science_final.ipynb
or
https://hub.mybinder.org/user/pavleen3633-project-yrowjqhd/notebooks/data_science_final.ipynb

#Ranking-Artists/Bands-through-analysis-of-yearly-Top-100-Songs-using-Wikipedia-web-scrapping-from-years-1970-to-2018)



Table of Contents of the project 
Motivation
Task Definition
Input
Output
Data set
Collection
Metadata
Scrapping Wikipedia
Data Parsing and Clean-up
Complexity of Data
Case of Missing Values
Data Statistics and Interpretation
Visualisation
Plot
Observations from Visualisation
Handling Outliers
Feature engineering for alternate visualisation
Conclusion
Literature Review
Motivation
Wikipedia is a big source of information on a wide range of topics including chronological details of events such as historical. Wikipedia is one of my go to source for any query on topics of interest. Finding the information particularly wikitables, a good source of data for analysis, I have chosen to utilize following concepts on the wikipedia top 100 songs list for years 1970 to 2018:

Web scrapping
Data Parsing and Data Clean-up
Dataframe and handling complexity of data
Data Visualisation
Feature Engineering
The initial challenge in the project has been to extrapolate the data wrangling from one wikipage in a manner consistent with ability to generalise the scrapping procedure and data handling from all pages. Secondly, the size and variety of information (e.g. links to more pages and information) presented an initial challenge to decide what data to include in data wrangling and features to be engineered.

Task definition
I intend to determine rank of artist(s)/bands based on their number of songs featured in the top 100 singles song list over the years of analysis (1970 to 2018) e.g. artists whose songs have been featured more than 20 times in the list.

I also intend to perform Feature engineering to determine ranks of artist(s)/bands through alternate analysis.

Input
[Song Ranking, Song name, Artist(s)/band, URLS of Singer/Band,url of song] through web scrapping 38 pages to extract wikitables for Top 100 songs/year from 1970 to 2018

Output
Bar plot indicating ranks of artists based on number of their songs in the list
Bar plot indicating scores of artists based on feature engineering
Dataset
How data was collected?

I have performed web scrapping of wikipedia websites of Top 100 singles songs to extract wikitables.

Why data was collected?

Data was collected to obtain a comprehensive information source containing relevant information which can be utitilzed to answer the question. Also, information structure and access to more information through wikipedia links made it a choice to add more features.

Metadata
Source: Wikipedia e.g. https://en.wikipedia.org/wiki/List_of_Billboard_Hot_100_number-one_singles_of_1970
Years of data scrapped: 1970 to 2018 (>=100 singles/year)
ranking: rank of every song in the list e.g. 1,2,3,........upto 100
band_singer: name of artist(s)/band e.g. 'Apollo 100'
song: name of song(s) featured in the list e.g. 'Joy'
songurl: url of the song e.g. '/wiki/Foolish_Games', None
url: url of the artist(s)/band e.g. '/wiki/Apollo_100'
https://hub.mybinder.org/user/pavleen3633-project-8z9qv26i/notebooks/project_data_science.ipynb
https://nbviewer.jupyter.org/github/Pavleen3633/Project/blob/master/data_wrangling_join_combine_reshape.ipynb
[![Binder](https://mybinder.org/badge_logo.svg)](https://hub.mybinder.org/user/pavleen3633-project-8z9qv26i/notebooks/project_data_science.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Pavleen3633/Project/master?filepath=cs109a_hw1_solutions%20%283%29-Copy1.ipynb)

https://mybinder.org/v2/gh/Pavleen3633/master?filepath=Project%2Fproject_data_science.ipynb

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Pavleen3633/master?filepath=Project%2Fproject_data_science.ipynb)





