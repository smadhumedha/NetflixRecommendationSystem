# Netflix Recommendation System
<h2>About Project</h2>
<p>This project aims to provide movie and TV show recommendations based on user input using a dataset obtained from Kaggle. The dataset contains information about various movies and TV shows available on Netflix as of 2021. By leveraging natural language processing techniques and cosine similarity, the project recommends similar titles based on user queries.</p>

<h2>About Dataset</h2>
<p>The dataset used in this project was obtained from Kaggle and consists of 5968 records and 13 columns. It includes information such as show ID, director, movie title, production country, release date, genre, cast, rating, IMDb score, duration, and date added to Netflix. The dataset was collected from Flixable, a third-party Netflix search engine.</p>

<h2>Concepts Used in the Code</h2>
<ul>
  <li><strong>Data Cleaning:</strong> Removing unnecessary characters, URLs, and punctuation, converting text to lowercase, and stemming.</li>
  <li><strong>Mapping to Dictionary:</strong> Creating a mapping between cleaned titles and original titles to decode recommendations.</li>
  <li><strong>Vectorization:</strong> Converting text data into numerical representations using TF-IDF vectorization.</li>
  <li><strong>Cosine Similarity:</strong> Calculating the similarity between vectors to find similar items.</li>
  <li><strong>Nearest Neighbors Algorithm:</strong> Finding the nearest neighbors to a given item in a high-dimensional space.</li>
  <li><strong>Pandas DataFrame:</strong> Organizing and manipulating tabular data.</li>
</ul>

