# Plan:

## Links to refer:
  - https://monkeylearn.com/sentiment-analysis/ 
  - https://www.geeksforgeeks.org/sentiment-classification-using-bert/
  - https://huggingface.co/docs/transformers/en/model_doc/bert#transformers.BertForPreTraining
  - https://www.youtube.com/watch?v=szczpgOEdXs
  - https://github.com/google-research/bert
  - https://github.com/Wilsven/yelp-reviews-sentiment-analysis/blob/main/yelp-NLP-1-data-wrangling.ipynb 

## Task 1: Comparing Different Platforms for Importing Textual Data 
**Timeline:** May 17 - May 24

1. **Identify Potential Platforms:**
   - Research and list platforms that can be used to import textual data relevant to tourism (e.g., social media platforms, review sites, forums).
   - Consider platforms like Twitter, TripAdvisor, Yelp, Reddit, etc.
   - yelp --> https://github.com/lanl/yelpapi?tab=readme-ov-file, https://github.com/Yelp/yelp-fusion?tab=readme-ov-file#code-samples, https://docs.developer.yelp.com/docs/fusion-intro
   - twitter --> https://developer.x.com/en/docs/twitter-api/getting-started/about-twitter-api, https://www.youtube.com/watch?v=GDbnarInwBQ, 
   - reddit --> https://www.geeksforgeeks.org/python-praw-python-reddit-api-wrapper/, https://www.reddit.com/r/restaurantowners/comments/18rfdlu/locally_sourced_goods/
   - opentable --> https://dev.opentable.com/partner-portal

2. **Criteria for Comparison:**
   - **Data Accessibility:** How easy it is to access and import data from the platform.
   - **Data Volume:** The amount of textual data available.
   - **Data Relevance:** Relevance of the data to tourism and risk preferences.
   - **APIs and Tools:** Availability of APIs or tools for data extraction.
   - **Cost:** Any costs associated with data access.

3. **Data Collection:**
   - Use APIs or web scraping tools to extract sample data from each platform.
   - Document the process and any challenges encountered.

4. **Analysis and Comparison:**
   - Compare platforms based on the criteria above.
   - Summarize the pros and cons of each platform.
   - Make a recommendation on the best platform(s) to use.

## Task 2: Performing Sentiment Analysis on Textual Data

**Timeline:** May 25 - June 15

1. **Prepare the Data:**
   - Clean and preprocess the textual data (removal of stop words, normalization, tokenization).
   - Annotate data if necessary.

2. **Sentiment Analysis:**
   - Choose a sentiment analysis tool or library (e.g., NLTK, TextBlob, VADER, BERT).
   - Implement sentiment analysis to classify emotions into 8 categories (e.g., joy, trust, fear, surprise, sadness, disgust, anger, anticipation).
   - Validate the results and fine-tune the model as needed.

3. **Distributional Semantics:**
   - Analyze the distribution of emotions across the data.
   - Use visualization tools (e.g., Matplotlib, Seaborn) to display the distribution of emotions.
   - Identify patterns and insights related to risk preferences in tourism.

## Optional Task: Text Classification or Topic Modeling

**Timeline:** June 16 - June 22

1. **Text Classification:**
   - If using a platform with numerical ratings, classify the text based on rating scores.
   - Use supervised learning techniques (e.g., Naive Bayes, SVM, Random Forest) for classification.

2. **Topic Modeling:**
   - Use unsupervised learning techniques (e.g., LDA, NMF) to identify key topics in the textual data.
   - Analyze how different topics correlate with risk preferences.

3. **Integration:**
   - Combine results from text classification/topic modeling with sentiment analysis.
   - Interpret how these methods complement each other in understanding risk preferences.

## Documentation and Reporting

**Timeline:** June 23 - June 30

1. **Compile Results:**
   - Gather all findings from the previous tasks.
   - Ensure all data, code, and results are well-documented.

2. **Report Writing:**
   - Write a comprehensive report detailing the methodology, analysis, results, and conclusions.
   - Include visualizations and summaries for clarity.

3. **Review and Feedback:**
   - Share the report with your advisor or team for feedback.
   - Make any necessary revisions based on feedback received.

## Milestones

1. **By May 24:** Complete comparison of platforms and select the best one(s).
2. **By June 15:** Complete sentiment analysis and distributional semantics.
3. **By June 22:** Optionally complete text classification or topic modeling.
4. **By June 30:** Finalize documentation and report.

## Tools and Resources

1. **Data Extraction:** APIs, BeautifulSoup, Scrapy.
2. **Sentiment Analysis:** NLTK, TextBlob, VADER, BERT.
3. **Visualization:** Matplotlib, Seaborn, Plotly.
4. **Machine Learning:** Scikit-learn, TensorFlow, Keras.
