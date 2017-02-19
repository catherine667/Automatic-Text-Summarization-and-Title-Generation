# Automatic-Text-Summarization-and-Title-Generation
Txsmart provides service to generate summaries and titles from both English and Chinese articles. We use advanced deep learning, machine learning and natural language processing techniques to extract summaries and titles.

## Text Summarization on Chinese:

We use submodular functions for document summarization tasks. These functions each combine two terms, one which encourages the summary to be representative of the corpus, and the other which positively rewards diversity.

快编宝是一个自动生成文本摘要的编辑工具。用户输入中文原文后，快编宝根据用户设定的摘要长度，自动生成精华摘要，并提供编辑和存储的功能。

Demo: http://kuaibianbao.com/

## Text Summarization on English:

* TextRank and RAKE methods to select sentences with high weights. 
* TextTiling and LDA methods to disperse sentences.
* Dependency tree compression rules to do sentence compression.
* Novel similarith based Word2Vec method to evaluate the summaries.

## DTATG: Title Generation on Dependency Trees

* Extract a small number of central sentences that convey the main meanings of the text and are in a suitable structure for conversion into a title. 
* Construct a dependency tree for each of these sentences and removes certain branches using a Dependency Tree Compression Model we devise.

Demo: http://119.29.118.23/title_generator/index.html






