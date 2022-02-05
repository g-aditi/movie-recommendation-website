# What Should I Watch Today?
## A movie recommendation website

Watch it run [here](https://what-should-i-watch.azurewebsites.net/)!

## About
This Content Based Filtering Movie Recommender is built on FLASK using Python for backend. The frontend consists of HTML, CSS, and JavaScript. IT has been hosted on Microsoft Azure using the WebApps service. Two snippets of code were created using the concept of CB. The first one is in Python programming language using the package “scikit-learn” and the second snippet of code is 
in JavaScript programming language which uses no packages and operates based on logic. Here, feature extraction methods and distance metrics are utilised to generate recommendations. 
The TMBD5000 dataset was used in the ML model.

## Content-based Filtering Methods
TfIdfVectorizer was used for feature extraction and conversion into the Vector Space Model. With CB filtering, a multi-dimension vector represents the preference of a user and the items available,in which each item is stored as a vector of its features. The angles between these vectors will be useful 
later on in calculating the similarity between each item.

The distance metric used in this recommender is Cosine Similarity. Cosine Similarity computes the similarity of items by measuring the cosine of the angle between two vectors projected in a multidimensional vector space. With Cosine Similarity, non-binary vector values are taken into consideration during calculation as the values directly influence the position of the vector.

## What The Screens Look Like
The first screen looks so:
![home-screen](https://github.com/g-aditi/movie-recommendation-website/blob/main/assets/home-screen.png)

When the entered movie was found, suggestions are listed on this screen like so:
!(/assets/found-screen.png)

If a movie is not found, this page is visible:
!(/assets/not-found-screen.png)

