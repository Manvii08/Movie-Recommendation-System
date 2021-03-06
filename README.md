# Movie-Recommendation-System
• Content based movie recommendation system that suggests movies based on similarities using score calculated elicited from cosine similarity metrics.
• Metadata (Name, Genre, Name of the director, etc.) fetched using an API by TMDB for years 2018-20 and used Kaggle for movies released before 2017.
• Pandas, NumPy libraries used for preprocessing the data.

*Similarity Score* :
How does it decide which item is most similar to the item user likes? Here we use the similarity scores.

It is a numerical value ranges between zero to one which helps to determine how much two items are similar to each other on a scale of zero to one. This similarity score is obtained measuring the similarity between the text details of both of the items. So, similarity score is the measure of similarity between given text details of two items. This can be done by cosine-similarity.

*How Cosine Similarity works?*

Cosine similarity is a metric used to measure how similar the documents are irrespective of their size. Mathematically, it measures the cosine of the angle between two vectors projected in a multi-dimensional space. The cosine similarity is advantageous because even if the two similar documents are far apart by the Euclidean distance (due to the size of the document), chances are they may still be oriented closer together. The smaller the angle, higher the cosine similarity.

*How to get the API key?*

Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.

Sources of the datasets

IMDB 5000 Movie Dataset

The Movies Dataset

List of movies in 2018

List of movies in 2019

List of movies in 2020

Credits :

• Kishan Lal ( Github username - kishan0725)

• Krish Naik ( YouTube channel - krish naik)

