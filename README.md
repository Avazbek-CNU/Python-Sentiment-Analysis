# Python-Sentiment-Analysis
Sentiment analysis task
1. Clean up the text data to remove non-ASCII characters and any other weird characters.

2. Identify comments related to accounting by using the following keywords: “accounting,” “accountant,” “fasb,” “gaap,” “CPA,” “AICPA”.
a. For the word “CPA,” please make sure it is separate (i.e., “ cpa “) and not attached to other words

Create a variable called “accounting” that takes on a value of one if it’s an accounting-related post and 0 if not.

3. Use the pysentiment package to analyze the sentiment of all comments using both the Harvard LV-4 dictionary and the Loughran & McDonald dictionary.

4. Output dataset with all original data in input spreadsheet + the sentiment score and accounting variable of each row.
