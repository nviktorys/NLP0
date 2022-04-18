# NLP0 (master)
First NLP project.

### Motivation
This is a learning project. Some of the things we aim to learn are in the following not exhaustive list:

1. To collaborate in a version control environment.
2. To write `.md` documents.
3. To get familiar with simple NLP methods.
4. To improve our coding habbits, specially with Python. 

### Useful (?) links

This very small and concise [GUIDE](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) is helping me this very moment to write this `.md` document.

About doing NLP with Python, I found a simple to follow [GUIDE](https://realpython.com/nltk-nlp-python/). I haven't reproduced any of their code, but I liked the explanation so far.

### Topics in NLP.

At the moment, EM is using NLTK for most of the work in Python. After reviewing some guides, I noticed that there is a bunch of pre-processing to do before actually doing any statistical analysis. Here are some of the topics that I have been trying:

1. Tokenising. Done by words or by sentences. This reads strings and creates a list of either words or sentences.
2. Filtering for stop words. We don't want words like "an", "a", "in" etc. They carry some info, but maybe it is not that useful. However, we need to be careful on not removing words like "not", which are short but meaningful.
3. Stemming. This algorithm looks for the root of words. Example: "helping", "helped", "help", should all relate to "help".
4. Lemmatising. Similar to Stemming, brings words to their core meaning.
5. Tagging (or POSTagging). This labels part of the string into parts of regular speech. In english, there are 8: "noun", "pronoun", "adjective", "verb", "adverb", "preposition", "conjunction" and "interjection".
6. Chunking. This is tokenising, but with phrases. After tagging words of a string, you create a pattern of tags to identify phrases. Example: The pattern Adjective + Noun would recorgnise "a large computer" as a phrase. 
7. Chinking. In chunking, you include patterns. In chinking, you exclude.
8. Named Entity Recognition (NER). Named Entities are noun phrases that refer to locations, people, organisations, etc.
