# ghibli_recommendations
This is the coding portion of my final report for the Case Studies in Machine Learning (AI 395T) class.

## Datasets <br/> 
`movies.csv`: Metadata for ~9,000 movies from the [MovieLens Latest Small dataset](https://grouplens.org/datasets/movielens/).<br/>
`ratings.csv`: 100,000 user ratings from the [MovieLens Latest Small dataset](https://grouplens.org/datasets/movielens/).<br/>
`Studio Ghibli.csv`: Metadata for 23 Studio Ghibli movies, sourced from [Kaggle](https://www.kaggle.com/datasets/shruthiiiee/studio-ghibli-dataset).<br/>

## Notebooks <br/>
`prepare_data.ipynb`: Prepares datasets for filtering experiments, generating cleaned files for analysis.<br/>
`content_based_filtering.ipynb`: Implements a content-based filtering model using cosine similarity on genres.<br/>
`collaborative_filtering.ipynb`: Implements an item-based collaborative filtering model using cosine similarity on ratings.<br/>
`compare_results.ipynb`: Analyzes Precision and Recall for content-based filtering and RMSE for collaborative filtering.<br/>

## Output files
`prepared_ghibli.csv`: Contains standardized Studio Ghibli movie titles and IDs from the MovieLens dataset.<br/>
`prepared_genres.csv`: Includes Ghibli movie titles and their one-hot encoded genres.<br/>
`prepared_ratings.csv`: Combines Ghibli movie ratings from MovieLens with corresponding movie titles.<br/>
<br/>
`totoro_content_based.csv`: Recommendations for "My Neighbor Totoro" using content-based filtering.<br/>
`totoro_collaborative.csv`: Recommendations for "My Neighbor Totoro" using collaborative filtering.<br/>
`totoro_combined_comparison.csv`: Combined comparison of recommendations for "My Neighbor Totoro" from both techniques.<br/>
<br/>
`howl_content_based.csv`: Recommendations for "Howl’s Moving Castle" using content-based filtering.<br/>
`howl_collaborative.csv`: Recommendations for "Howl’s Moving Castle" using collaborative filtering.<br/>
`howl_combined_comparison.csv`: Combined comparison of recommendations for "Howl’s Moving Castle" from both techniques.<br/>
<br/>
`kiki_content_based.csv`: Recommendations for "Kiki’s Delivery Service" using content-based filtering.<br/>
`kiki_collaborative.csv`: Recommendations for "Kiki’s Delivery Service" using collaborative filtering.<br/>
`kiki_combined_comparison.csv`: Combined comparison of recommendations for "Kiki’s Delivery Service" from both techniques.<br/>
<br/>
`calculated_precision_recall.csv`: Precision and Recall metrics calculated for content-based filtering.<br/>
`cleaned_ghibli_titles.csv`: Cleaned and standardized Studio Ghibli movie titles for consistency.<br/>
`cosine_similarity_matrix_genres.csv`: Cosine similarity matrix generated for Ghibli movies based on their genres.<br/>
`collaborative_filtering_predictions.csv`: Predicted ratings for Studio Ghibli movies, generated using the Surprise collaborative filtering model.



