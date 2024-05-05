# Hoax-Detection-System-Using-ML-Algorithms-to-Identify-Fake-News

## Predict whether news is hoax or fact using simple NLP 🤨 🧐

![image](https://github.com/roniantoniius/Hoax-Detection-System-Using-ML-Algorithms-to-Identify-Fake-News/assets/121453378/a1c6a960-7490-43d0-8d9d-9f68eed85c52)
Image Source: www.wittenberg.edu

### Business Understanding 😇 

Today in 2024, we live in an era where information is spread quickly through social media and other online platforms 🤖🤖. But unfortunately, not all information we encounter on the internet can be trusted. There are so many fake news or hoaxes that can negatively affect our views and decisions 💀💀. Therefore, in this project, I want to explore the ability of machines to help us distinguish between real news (facts) and fake news (hoaxes) 😼.

True and accurate information is key to making good decisions, be it in politics, health, business, and more. However, in a world filled with an overwhelming flow of information, it is sometimes difficult to sort out what is true and what is not 🥺. Therefore, the solution we are looking for here is a predictive model that can help us identify whether a news story is a fact or a hoax 🤗.

Using machine learning techniques, we can train the model to recognize certain patterns in the news text that indicate the authenticity or inauthenticity of the news. Through this project, we hope to provide a useful tool for the wider community, especially the younger generation who are often victims of the spread of fake news 😎.



### Data Understanding 😁
This dataset contains information about news that has been categorized whether it is genuine (fact) or hoax in more than 20 thousand data records with a size of 90 mb. This stage is an important part of our efforts to understand trends and patterns in news distribution, where the features contain;
- id: the primary key for each entry in the dataset, which helps in identifying the uniqueness of each news story.
- title: The title of each news item, giving us an overview of the topic or subject of the news item.
- author: The name of the author or news source, providing context about the source of the information.
- text: the actual news text, which will be the main source of information for our model.
- label: a category label that indicates whether the news is a hoax[1] or a fact[0].

### Data Preparation: Feature Engineering 😢
#### Bag of Word Engineering
- EDA and cleaning
- Tokenization
- Stemming
- Feature Extraction with Count Vectorizer

### Modeling 😨 😰
- Naive Bayes: MultiNomial
- Linear_model: PassiveAggressiveClassifier

### Evaluation 🧐 🤓 😎
Natural Language Processing Metrics (optional):
- accuracy
- BLEU Score
- ROUGE
- METEOR
- CIDEr
- Perplexity
- Word Error Rate (WER)
- Character Error Rate (CER)
- F1 Score for NER

Translated with DeepL.com (free version)
