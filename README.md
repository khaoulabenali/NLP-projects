# NLP-projects

### What Is Natural Language Processing?

- Natural Language Processing, or NLP for short, is broadly defined as the automatic manipulation of natural language, like speech and text, by software.

- The study of natural language processing has been around for more than 50 years and grew out of the field of linguistics with the rise of computers.

- Given the importance of this type of data, we must have methods to understand and reason about natural language, just like we do for other types of data.

<img src="/assets/google-smith.jpeg" width="500" align="center"/>


### How Does Natural Language Processing Work?
- In natural language processing, human language is separated into fragments so that the grammatical structure of sentences and the meaning of words can be analyzed and understood in context. This helps computers read and understand spoken or written text in the same way as humans.

- Here are a few fundamental NLP pre-processing tasks data scientists need to perform before NLP tools can make sense of human language:

    * Tokenization: breaks down text into smaller semantic units or single clauses
    * Part-of-speech-tagging: marking up words as nouns, verbs, adjectives, adverbs, pronouns, etc
    * Stemming and lemmatization: standardizing words by reducing them to their root forms
    * Stop word removal: filtering out common words that add little or no unique information, for example, prepositions and articles (at, to, a, the).

Only then can NLP tools transform text into something a machine can understand. 
<img src="/assets/Natural-Language-Processing-steps.png" width="500" height="500" align="center"/>

### Natural Language Processing Algorithms :

- Once your data has been pre-processed, it’s time to move onto the next step: building an NLP algorithm, and training it so it can interpret natural language and perform specific tasks.

- There are two main algorithms you can use to solve NLP problems:

    * A rule-based approach. Rule-based systems rely on hand-crafted grammatical rules that need to be created by experts in linguistics, or knowledge engineers. This was the earliest approach to crafting NLP algorithms, and it’s still used today.

    * Machine learning algorithms. Machine learning models, on the other hand, are based on statistical methods and learn to perform tasks after being fed examples (training data). 

- The biggest advantage of machine learning algorithms is their ability to learn on their own. You don’t need to define manual rules – instead machines learn from previous data to make predictions on their own, allowing for more flexibility.

- Machine learning algorithms are fed training data and expected outputs (tags) to train machines to make associations between a particular input and its corresponding output. Machines then use statistical analysis methods to build their own “knowledge bank” and discern which features best represent the texts, before making predictions for unseen data (new texts):
<img src="/assets/Capture.PNG" width="500" height="500" align="center"/>

### Natural Language Processing Examples :

###### Text Classification :

- Text classification is one of the most basic NLP tasks and consists of assigning categories (tags) to a text, based on its content. Classification models can serve different purposes, for example:


* Sentiment analysis is the process of analyzing emotions within a text and classifying them as positive, negative, or neutral. By running sentiment analysis on social media posts, product reviews, NPS surveys, and customer feedback, businesses can gain valuable insights about how customers perceive their brand.

* Topic classification consists of identifying the main themes or topics within a text and assigning predefined tags. For training your topic classifier, you’ll need to be familiar with the data you’re analyzing, so you can define relevant categories. For example, you might work for a software company, and receive a lot of customer support tickets that mention technical issues, usability, and feature requests.In this case, you might define your tags as Bugs, Feature Requests, and UX/IX.


* Intent detection consists of identifying the purpose, goal, or intention behind a text. It’s an excellent way of sorting outbound sales email responses by Interested, Need Information, Unsubscribe, Bounce, etc. The tag Interested could help you spot a potential sale opportunity as soon as an email enters your inbox!

###### Text Extraction :

- Another example of NLP is text extraction, which consists of pulling out specific pieces of data that are already present in a text. It’s a perfect way to automatically summarize text or find key information. The most common examples of extraction models are:


* Keyword extraction automatically extracts the most important words and expressions within a text. This can provide you with a sort of preview of the content and its main topics, without needing to read each piece.

###### Machine Translation :

- This was one of the first problems addressed by NLP researchers. Online translation tools (like Google Translate) use different natural language processing techniques to achieve human-levels of accuracy in translating speech and text to different languages. Custom translators models can be trained for a specific domain to maximize the accuracy of the results.

###### Topic Modeling :

- Topic modeling is similar to topic classification. This example of natural language processing finds relevant topics in a text by grouping texts with similar words and expressions.

- Since you don’t need to create a list of predefined tags or tag any data, it’s a good option for exploratory analysis, when you are not yet familiar with your data.

###### Natural Language Generation (NLG) :

- Natural language generation, NLG for short, is a natural language processing task that consists of analyzing unstructured data and using it as an input to automatically create content. 

### Top NLP Tools to Help You Get Started :
    
* MonkeyLearn
* Google Cloud NLP
* IBM Watson
* Aylien
* Amazon Comprehend
* MeaningCloud


