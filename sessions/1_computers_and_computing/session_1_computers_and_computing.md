[Home](../../README.md) / [Sessions](../README.md) / Session 1: Computers and Computing

# Session 1: Computers and Computing

## Lecture

> **Slides**: [Computers and Computing](lecture/slides_computers_and_computing.md)

A brief history of computers provides the background to introduce Turing's concept of a universal computing machine, the Turing Machine. The argument is made that the Turing Machine was brought forward to demonstrate the limits of computing and, by extension, artificial intelligence. Turing's own arguments against strong AI are presented as well.
Algorithms are introduced as a set of steps that (are guaranteed to) accomplish a certain tasks.
The lecture contains an **in-class exercise**. Students are invited to guess a number between 1 and 100 and receive feedback on whether the number they suggest is higher or lower than the number that the presenter has in mind. They then may answer the questions:
- What strategy have you used to guess the number?
- Can you formulate an algorithm from your strategy?
- What other strategies are possible? Can you formulate an algorithm?
- Which strategies are algorithms, i.e. are guaranteed to succeed?
	- e.g. shouting out random numbers may result in eventually finding the correct number, but is not guaranteed to succeed. Adding a memory that only produces random numbers that have not yet been suggested would succeed however.

## Reading

As this is the first session, there will be no student-prepared presentation of the reading material. Instead students are invited to:
- Find a (current) newspaper article about an algorithm
	- What does the algorithm claim to do?
	- What does the article say about its performance?
- Try to locate the original academic paper other background material on the algorithm _(optional)_ 
	- Read and try to understand
	- Does the newspaper article accurately reflect the paper?

Each student then gives a brief summary of the article they read, which is followed by a discussion.

:point_right: See [articles and papers](reading/articles.md) that have been picked by students

Works cited:

Dreyfus, H. (1972). What Computers Can’t Do. Retrieved from https://archive.org/details/whatcomputerscan017504mbp

Hicks, M. (2017). Programmed Inequality: How Britain Discarded Women Technologists and Lost Its Edge in Computing. Cambridge, MA: MIT Press.

Turing, A. M. (1937). On Computable Numbers, with an Application to the Entscheidungsproblem. Proceedings of the London Mathematical Society, s2-42(1), 230–265. https://doi.org/10.1112/plms/s2-42.1.230

Turing, A. M. (1950). Computing Machinery and Intelligence. Mind, LIX(236), 433–460. https://doi.org/10.1093/mind/LIX.236.433

:point_right: Bibliography on [Zotero](https://www.zotero.org/groups/2422637/what_machines_cant_learn/items/tag/Computers%20and%20Computing)

## Hands-On
As a hands-on exercise, I gave a brief introduction to [Jupyter Notebooks](https://jupyter.org/) as some of the later exercises will make use of this. I suggested students to use [Google Colaboratory](https://colab.research.google.com/) as it comes already preloaded with many popular machine learning libraries and provides access to GPU and TPU powered cores.

Personally I found the [Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/)to contain a good introduction of Jupyter Notebooks. It is however a paid course.

Students with some programming experience may then try to implement the number guessing algorithm they formulated earlier in Python. Two implementations, one where the machine guesses a user's number and one where the machine competes against itself are offered in a Jupyter Notebook.

### Files
- [Number\_Guessing\_Algorithm.ipynb](./hands_on/Number_Guessing_Algorithm.ipynb)