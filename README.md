# Recommender-Systems
Article/News Recommender System using Content Based Filtering method.

1. Problem Statement
With the rapid growth of online content, finding relevant news articles has become increasingly difficult due to the overwhelming volume of information. Recommendation systems, especially for dynamic environments like online news, aim to address this issue by suggesting articles based on content similarity. The recommendation process is challenging due to continuous changes in news streams, user preferences, and frequent updates. Using attributes like article headline, category, author, and publishing date, a content-based recommendation system can help users discover similar articles to those they have already read, streamlining the browsing process and improving user satisfaction.

2. Dataset Description
The dataset contains approximately 200,000 news headlines from 2012 to 2018, obtained from HuffPost. It includes attributes such as article headline, category, author, short description, publication date, and news links, spanning categories like Politics, Entertainment, Wellness, Sports, and more. These features aid in segregating articles and enhancing recommendations. The dataset supports applications such as tagging untracked news articles and analyzing the language used across different categories, providing a robust foundation for news recommendation systems.

3. Results and Conclusion
Content-based filtering was used for article recommendations, leveraging methods such as TF-IDF, Word2Vec, and weighted similarity. Compared to the Bag-of-Words (BoW) approach, the TF-IDF method effectively identifies articles with less frequently occurring but relevant keywords. For example, words like "employer," "fire," and "flip" in headlines are highlighted in the top recommendations. Word2Vec further improves recommendations by capturing semantic relationships between words, enhancing the system’s ability to suggest articles based on deeper content understanding.
