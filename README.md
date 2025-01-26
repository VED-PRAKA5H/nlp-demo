# nlp-demo
Tutorial on Natural Language Processing
## Step 1: Data-Cleaning
Get and clean the data.
### Libraries
- **pandas**: A powerful data analysis and manipulation library.
- **re**: Provides support for working with regular expressions.
- **pickle**: Used for serializing and deserializing Python objects.
- **beautifulsoup**: A library for parsing HTML and XML documents.
- **requests**: A simple and elegant HTTP library for making web requests.
- **scikit-learn**: A popular machine learning library with efficient tools for data mining and analysis.
## Step 2: EDA
* `Input`: a corpus and a DTM
* `EDA`: summarize the main characteristics of the data set, often using visual methods
    > EDA Steps (eg. how to find Top words?): 
    > 1. Data: Determine the format ot the raw data you will need to start (select the data format that is DTM)
    > 2. Aggregate: Figure out how to aggregate the data (for each row, select the columns with the larget value)
    > 3. Visualize: Find the best way to visualize the data (eg. word clouds)
    > 4. Insight: Extract some key takeaways from the visualization (Does the data make sense? or Can we further clean the data (maybe with additional stop words) or What are some intial findings? How are the comedians different?)
* `Output`: figure out the main trends in the data and if it makes sense.
### Libraries:
* wordcloud: Create word cloud in python
* matplotlib: Data visualization in python
