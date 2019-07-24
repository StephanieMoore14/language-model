# Intro to Language Modeling

This project builds a statistical language using public domain books found on [Project Gutenberg](https://www.gutenberg.org/). Language models attempt to capture the likelihood that a given sequence of words occur in a given "language". Here, "language" is a broad term that, in addition to the normal usage, may mean the language of a particular author or style. Applications of language models are found in areas such as language generation, authorship attribution, auto-complete / word-suggestion, and machine translation.

This project focuses on a simple but effective type of language model (LM) called N-gram models. Given a sentence, s, we can construct a list of n-grams from s by finding pairs of words that occur next to each other. From this, we can count the number of occurrences of each n-gram. This count determines the frequency with which an n-gram occurs throughout our document.

Below are the outline steps to achieve this:
 * Write code to download the text of a book from a url, returning the corpus as a string.
 * Tokenize the corpus into sequences of words and paragraphs.
 * Create two "baseline" langunage models; create text with them using sampling.
 * Compute an N-gram language model
 * Write code to sample from the N-gram language model; create text with them.
 * Evaluate performance (computational) of your language model for different N.
 * Evaluate performance (statistical) of your language model for different N.
 * Create an auto-completion suggestion model.
