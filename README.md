
The purpose of the following project was to process textual data from a given HTML page, calculating the positive and negative score based on predefined set of strings and extracting the articles to an output
Excel file.

# Libraries: 
Natural Language processing libraries like NTLK and Textblob used to extract the data from the article
RE library- used to check whether a given string matches the given pattern
Syllables- Used to estimate the number of vowels to understand the number of syllables in a string
Urllib.request- urllib provides a basic API for making HTTP requests in Python without relying on third party libraries
BeautifulSoup- Helps in extracting data from an HTML page

# Data Collection
- The project ingests data from webpages, demonstrating web scraping skills to extract unstructured data.
- Pandas is used to load and manipulate the input dataset of URLs.
# Data Cleaning
- The text data is cleaned by:
- Removing HTML tags with BeautifulSoup
- Lowercasing and tokenizing words
- Filtering out stopwords with NLTK
- Lemmatizing words to their base form
- This data munging process prepares the text for analysis.
# Exploratory Data Analysis
- Both numerical and natural language processing techniques are used to analyze the data, including:
- Calculating sentiment scores
- Statistical metrics like word counts
- Text readability metrics like fog index
- Syntactic analysis like sentence lengths
- This mixes traditional stats with modern NLP.
# Statistical Analysis
The output includes several descriptive statistics quantifying attributes of the text.
These stats could be further analyzed to find patterns, correlations, etc.
# Model Development
- The analysis functions could serve as feature extraction for training machine learning models.
- For example, predicting article quality on the extracted metrics.
# Reporting
- Results are exported to a structured format (Excel) for further analysis.
  Visualizations could also be generated to present insights.
So in summary, the project follows a standard data science pipeline - collecting data, cleaning it, doing EDA, applying ML-powered techniques, performing statistical analysis, and exporting the final results.
