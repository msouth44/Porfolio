# Wordcloud #

This sample shows code that was used to create a wordcloud that was done in the *The Hotetst Topics in Machine Learning* project found on DataCamp. The wordcloud represents the words that occur the most within titles of Journal articles written about the topic of machine learning. 

```python
# Import the wordcloud library
import wordcloud

# Join the different processed titles together.
long_string = ' '.join(papers['title_processed'])

# Create a WordCloud object, generate a wordcloud and visualise it
wordcloud = wordcloud.WordCloud()

# Generate a word cloud
wordcloud.generate(long_string)

# Visualize the word cloud
wordcloud.to_image()
```




![png](wordcloud_0_0.png)


