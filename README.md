# Sentiment_analysis_BERT
Sentiment Analysis using finetuned BERT

Sentiment Analysis using BERT
This Jupyter Notebook (Sentiment_analysis_using_BERT.ipynb) performs sentiment analysis on text data using a pre-trained BERT model from the Hugging Face Transformers library. It analyzes the sentiment of the provided text and presents the results in a DataFrame.

Usage
1.	Install Dependencies: Ensure you have the required Python libraries installed. You can install them using pip:

2.	Open the Notebook: Open the Jupyter Notebook in your preferred environment.

3.	Execute the Cells: Run each cell in the notebook to perform sentiment analysis on the provided text data.


Description

•	The notebook imports necessary libraries such as torch, requests, BeautifulSoup, pandas, numpy, and transformers for handling data retrieval, sentiment analysis, and data manipulation.

•	It then instantiates a BERT-based sentiment analysis model using the AutoTokenizer and AutoModelForSequenceClassification classes from the Hugging Face Transformers library.

•	After encoding the input text, the notebook calculates sentiment scores using the BERT model and stores the results in a DataFrame.

•	The sentiment scores range from 1 (very negative) to 5 (very positive), indicating the sentiment polarity of each input text.

•	Finally, the notebook outputs the DataFrame containing the input text and their corresponding sentiment scores.

Notes
•	This notebook requires an internet connection to access the pre-trained BERT model from the Hugging Face model hub.

File Structure
•	Sentiment_analysis_using_BERT.ipynb: The main Jupyter Notebook for performing sentiment analysis on text data and outputting the results.

Acknowledgments
•	The sentiment analysis model used in this notebook is provided by the Hugging Face Transformers library.
