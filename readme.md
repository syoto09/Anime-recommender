# Anime recommender
### Find the similarities between animes to recommend the best match anime

## Requirements
* [Python](https://www.python.org/downloads/)
* [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)
*  [Numpy](https://numpy.org/install/)
* [SciPy ](https://scipy.org/)

## Methods
 * Download the data
  * Clean data
     * Eliminate anime with 0
     * Change the Null to 0 in type and genre
* Cleaned data(Anime.file)
     * Choose the only [type = TV]
     * Combine the data both anime and rating on the anime ID
     * For computing reason only we calculate the first 10000 users because of calculation time

* Consine Similarity formula 
![cosine](https://miro.medium.com/max/1400/1*LfW66-WsYkFqWc4XYJbEJg.png)