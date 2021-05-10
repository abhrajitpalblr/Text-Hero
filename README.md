# Text-Hero
Text hero 1 release was 20 April 2020
Text Hero
https://pypi.org/project/texthero/

Texthero is a python toolkit to work with text-based dataset quickly and effortlessly. Texthero is very simple to learn and designed to be used on top of Pandas. Texthero has the same expressiveness and power of Pandas and is extensively documented. Texthero is modern and conceived for programmers of the 2020 decade with little knowledge if any in linguistic.

You can think of Texthero as a tool to help you understand and work with text-based dataset. Given a tabular dataset, it's easy to grasp the main concept. Instead, given a text dataset, it's harder to have quick insights into the underline data. With Texthero, preprocessing text data, map it into vectors and visualize the obtained vector space takes just a couple of lines.

Texthero include tools for:

Preprocess text data: it offers both out-of-the-box solutions but it's also flexible for custom-solutions.
Natural Language Processing: keyphrases and keywords extraction, and named entity recognition.
Text representation: TF-IDF, term frequency, and custom word-embeddings (wip)
Vector space analysis: clustering (K-means, Meanshift, DBSAN and Hierarchical), topic modelling (wip) and interpretation.
Text visualization: vector space visualization, place localization on maps (wip).

pip install texthero
Under the hoods, Texthero makes use of multiple NLP and machine learning toolkits such as Gensim, NLTK, SpaCy and scikit-learn. You don't need to install them all separately, pip will take care of that.

For fast performance, make sure you have installed Spacy version >= 2.2. Also, make sure you have a recent version of python, the higher, the best.
