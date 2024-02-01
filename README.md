# CPSC501 Assignment 2


I got the data I used from Kaggle, specifically: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_movies.csv. 

As you can see, there is no specific license listed (it says specified in description), and the description says:
"Data Source Transfer Summary

We (Kaggle) have removed the original version of this dataset per a DMCA takedown request from IMDB. In order to minimize the impact, we're replacing it with a similar set of films and data fields from The Movie Database (TMDb) in accordance with their terms of use. The bad news is that kernels built on the old dataset will most likely no longer work."

and 

"Acknowledgements

This dataset was generated from The Movie Database API. This product uses the TMDb API but is not endorsed or certified by TMDb.
Their API also provides access to data on many additional movies, actors and actresses, crew members, and TV shows. "

This assignment is built to help me better understand how to use Tensorflow and Keras, as well as plotting data with seaborn or MatplotLib. 

Navigating this repository should be easy; 
Main has all of the parts of my main project (main1, main2, main3, and main4 for each of the 4 parts). There is also one report that I appended each new part onto. This also holds my input data, as well as a cleaned version of my data, along with 3 plots I was asked to make.

Part 1 has the completed version of my code that outputs 98%+ test accuracy, as well as my model output in a .h5 and its own part1 report.

Part 2 has MNIST-partial, which is the code that gave me a pretty good accuracy but was not complete (found 3 images that fail). MNIST-complete is the code that has these 3 same images pass. It also has my model output in a .h5. There is also predict_test, which is the file I edited that allows me to see the images and graph my models predictions. It also has its own report, in a pdf.

Part 3 has my completed heart model code (CHDModel.ipynb), as well as my training and testing data each in its own csv. There is also a part3 report pdf. 
