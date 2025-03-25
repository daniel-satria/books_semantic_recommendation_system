# Semantic Book Recommender

## Building Process
[1. Data Exploration](notebooks/1_data-exploration.ipynb)
* Exploring the data and perform data cleaning.

[2. Vector Search](notebooks/2_vector-search.ipynb)
* Building a vector database. This allows users to find the most similar books to a natural language query (e.g., "a book about a person seeking revenge").

[3. Text Classification](notebooks/3_text-classification.ipynb)
* Doing text classification using zero-shot classification in LLMs. This allows us to classify the books as "fiction" or "non-fiction", creating a facet that users can filter the books on. 

[4. Sentiment Analysis](notebooks/4_sentiment-analysis.ipynb)
* Performing sentiment analysis using LLMs and extracting the emotions from text. This will allow users to sort books by their tone, such as how suspenseful, joyful or sad the books are.

## Deployment
* Creating a web application using Gradio for users to get book recommendations (code in the file `gradio-dashboard.py`). The gradio dashboard could be initiate with command `python3 gradio-dashboard.py`.

