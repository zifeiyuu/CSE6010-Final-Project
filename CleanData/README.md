
# CleanMovieLens.ipynb Function Description

`CleanMovieLens.ipynb` reads the raw data (`ratings.csv`, `movies.csv`, `tags.csv`,`links.csv`) from the `ml-32m` folder and performing data cleaning. The main workflow includes:

- **Reading all raw data from ml-32m**
- **Filtering movies** that have both tags and ratings
- **Collecting all tags** for each movie, removing duplicates, and storing them as `review_text`
- **Calculating the average rating** for each movie, stored as `average_rating`
- **Assembling the final dataframe** in the format `{movieId, title, genres, review_text, average_rating}`
- **Outputting the result** to the file `cleaned_reviews.csv`

You can run this notebook directly to obtain a cleaned movie dataset for further analysis and modeling.