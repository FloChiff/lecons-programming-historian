## Introduction

In this lesson, you will learn how to organize a set of texts for research; that is, you will learn the basic steps of creating a 'corpus'. You will also learn the main metrics of quantitative text analysis. For this purpose, you will use [Voyant Tools](http://voyant-tools.org/),[^1] a web-based platform that does not require installation and works in any browser with an internet connection.

This lesson is designed as a beginner-friendly introduction to corpus analysis and is part of a growing ecosystem of tools and methods in digital humanities. For a more advanced tool, see the _Programming Historian_ [lesson on corpus analysis with AntConc](/en/lessons/corpus-analysis-with-antconc). You may also be interested in other *Programming Historian* lessons on [text mining](/en/topics/text-mining), [natural language processing](/en/lessons/introduction-to-nlp-with-python), and [topic modeling](/en/lessons/topic-modeling-and-mallet).

### Prerequisites and Further Reading

No prior experience with text analysis is required. However, for those who want to go deeper, we recommend the following resources:

- [Voyant Tools Help Documentation](https://perma.cc/6CRX-9B9D)
- [Hermeneuti.ca](https://perma.cc/93VW-WC8V), the companion site to the book *Hermeneutica: Computer-Assisted Interpretation in the Humanities* by Sinclair and Rockwell[^2]

### Corpus Analysis

Corpus analysis is a type of [content analysis](https://perma.cc/Y8B2-RL89) that allows large-scale comparisons of a set of texts or a corpus.

Since the advent of computing, both computational linguists and [information retrieval](https://perma.cc/3F3M-3JV3) specialists have created and used software to notice patterns that are not evident to the naked eye, or to corroborate hypotheses they intuited when reading certain texts but required laborious, costly, and mechanical work. For example, to obtain patterns of increase and decline in usage of certain terms over a given period, it was necessary to hire people to manually review a text and note how many times the sought term appeared. Early on, observing the counting capabilities of computers, these specialists promptly wrote programs to facilitate the task of creating [frequency lists](https://perma.cc/F472-XM7K) or [concordance tables](https://perma.cc/AYP4-PVKR). The program you will learn to use in this lesson fits into this historical context.

### What You Will Learn in This Lesson

Voyant Tools is a web-based tool that does not require the installation of any specialized software as it works on any computer with an internet connection.

As stated in [Corpus Analysis with Antconc](/en/lessons/corpus-analysis-with-antconc), this tool is a good entry point to more complex methods.

By the end of this lesson, you will be able to:

- assemble a plain text corpus
- load your corpus into Voyant Tools
- understand and apply different corpus segmentation techniques
- identify basic characteristics of your text set:
  - length of the uploaded documents
  - lexical density (called 'vocabulary density' on the platform)
  - average words per sentence
- read and understand different statistics about words: absolute frequency, normalized frequency, statistical skewness, and distinctive words
- search for keywords in context and export data and visualizations in different formats (CSV, PNG, HTML)
