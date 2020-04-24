# ML in Architecture

Hello! I'm Gizem and This is my Journal which is about Machine Learning in Architecture 


## 25 Open Datasets for Deep Learning

[Link](https://www.analyticsvidhya.com/blog/2018/03/comprehensive-collection-deep-learning-datasets/) 

1. MNIST - handwritten digits - 30 MB
2. COCO - object detection - 25 GB
3. ImageNet - dataset of images - 150GB
4. Open Images - image URL dataset - 500 GB
etc...

## How to collect your deep learning dataset

- How to collect your deep learning dataset [Link](https://towardsdatascience.com/how-to-collect-your-deep-learning-dataset-2e0eefc0ba24)
- Collecting Movie Data [Link](https://towardsdatascience.com/collecting-movie-data-445ca1ead8e5)
- Movie Posters as a Deep Learning Dataset [Link](https://towardsdatascience.com/movie-posters-81af5707e69a)
- Movie genre classifier using a dataset created using Google Images [Link](https://towardsdatascience.com/building-a-movie-genre-classifier-using-a-dataset-created-using-google-images-4752f75a1d79)
- Wandora Imdb Exractor [Link](http://www.wandora.org/wandora/wiki/index.php?title=IMDB_extractor) 
![Image](/Images/Imdb_10.png)


## Movie Datasets

### Imdb datasets 
Documentation for these data files can be found on [Link](http://www.imdb.com/interfaces/)

[Link](name.basics.tsv.gz) **title.basics.tsv.gz** - Contains the following information for titles:
- tconst (string) - alphanumeric unique identifier of the title
- titleType (string) – the type/format of the title (e.g. movie, short, tvseries, tvepisode, video, etc)
- primaryTitle (string) – the more popular title / the title used by the filmmakers on promotional materials at the point of release
- originalTitle (string) - original title, in the original language
- isAdult (boolean) - 0: non-adult title; 1: adult title
- startYear (YYYY) – represents the release year of a title. In the case of TV Series, it is the series start year
- endYear (YYYY) – TV Series end year. ‘\N’ for all other title types
- runtimeMinutes – primary runtime of the title, in minutes
- genres (string array) – includes up to three genres associated with the title

[Link](title.akas.tsv.gz) **title.akas.tsv.gz** - Contains the following information for titles:
- titleId (string) - a tconst, an alphanumeric unique identifier of the title
- ordering (integer) – a number to uniquely identify rows for a given titleId
- title (string) – the localized title
- region (string) - the region for this version of the title
- language (string) - the language of the title
- types (array) - Enumerated set of attributes for this alternative title. One or more of the following: "alternative", "dvd", "festival",      "tv", "video", "working", "original", "imdbDisplay". New values may be added in the future without warning
- attributes (array) - Additional terms to describe this alternative title, not enumerated
- isOriginalTitle (boolean) – 0: not original title; 1: original title

[Link](title.basics.tsv.gz) **name.basics.tsv.gz** – Contains the following information for names:
- nconst (string) - alphanumeric unique identifier of the name/person
- primaryName (string)– name by which the person is most often credited
- birthYear – in YYYY format
- deathYear – in YYYY format if applicable, else '\N'
- primaryProfession (array of strings)– the top-3 professions of the person
- knownForTitles (array of tconsts) – titles the person is known for

[Link](title.principals.tsv.gz) **title.principals.tsv.gz** – Contains the principal cast/crew for titles
- tconst (string) - alphanumeric unique identifier of the title
- ordering (integer) – a number to uniquely identify rows for a given titleId
- nconst (string) - alphanumeric unique identifier of the name/person
- category (string) - the category of job that person was in
- job (string) - the specific job title if applicable, else '\N'
- characters (string) - the name of the character played if applicable, else '\N'


## Kaggle Datasets

**Movie Genre from its Poster** [Link](https://www.kaggle.com/neha1703/movie-genre-from-its-poster)

The movie posters are obtained from IMDB website. The collected dataset contains *IMDB Id, IMDB Link, Title, IMDB Score, Genre and link* to download movie posters. Each Movie poster can belong to at least one genre and can have at most 3 genre labels assigned to it. As the dataset also includes the IMDB score, it would be really interesting to see if movie poster is related to rating.

**IMDB data from 2006 to 2016** [Link](https://www.kaggle.com/PromptCloudHQ/imdb-data)

Here's a data set of 1,000 most popular movies on IMDB in the last 10 years. The data points included are:
- *Title, Genre, Description, Director, Actors, Year, Runtime, Rating, Votes, Revenue, Metascrore
