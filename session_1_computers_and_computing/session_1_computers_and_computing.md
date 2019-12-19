# Session 1: Computers and Computing

[[_TOC_]]

## Lecture
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

Articles and papers that have been picked by students:

- Some AI just shouldn’t exist
	- article: https://www.vox.com/future-perfect/2019/4/19/18412674/ai-bias-facial-recognition-black-gay-transgender
	- paper: https://psyarxiv.com/hv28a/
- Salesforce deploys Einstein Vision to spot great white sharks
	- article: https://www.zdnet.com/article/salesforce-deploys-einstein-vision-to-spot-great-white-sharks/
	- paper: https://developer.salesforce.com/blogs/developer-relations/2017/05/using-einstein-vision-within-golang.html
- Inceptionism: Going Deeper into Neural Networks
	- article: https://ai.googleblog.com/2015/06/inceptionism-going-deeper-into-neural.html
	- paper: https://www.nature.com/news/can-we-open-the-black-box-of-ai-1.20731
- Google besiegt erstmals einen Go-Profi
	- article: https://www.zeit.de/digital/internet/2016-01/kuenstliche-intelligenz-google-deepmind-go-alphago
-  China scientists can tell how well you sleep by watching your step
	- article: https://www.asiaone.com/digital/china-scientists-can-tell-how-well-you-sleep-watching-your-step
- Digital dystopia: how algorithms punish the poor
	- article: https://www.theguardian.com/technology/2019/oct/14/automating-poverty-algorithms-punish-poor
- How Etsy taught style to an algorithm
	- article: https://www.fastcompany.com/90374429/how-etsy-taught-style-to-an-algorithm
- How Spotify’s Algorithm Knows Exactly What You Want to Listen To
	- article: https://onezero.medium.com/how-spotifys-algorithm-knows-exactly-what-you-want-to-listen-to-4b6991462c5c
- Google erkennt das Herzinfarktrisiko in den Augen
	- article: https://www.welt.de/wirtschaft/webwelt/article173811314/Google-Algorithmus-erkennt-das-Herzinfarktrisiko-in-den-Augen.html
	- paper: https://arxiv.org/abs/1708.09843
- Facebook Changes Algorithm, Promises More Personalized News Feed
	- article: https://www.geek.com/tech/facebook-changes-algorithm-promises-more-personalized-news-feed-1787639/
	- paper: https://arxiv.org/abs/1904.01049
## Hands-On
As a hands-on exercise, I gave a brief introduction to [Jupyter Notebooks](https://jupyter.org/) as some of the later exercises will make use of this. I suggested students to use [Google Colaboratory](https://colab.research.google.com/) as it comes already preloaded with many popular machine learning libraries and provides access to GPU and TPU powered cores.

Personally I found the [Python for Data Science and Machine Learning Bootcamp](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/)to contain a good introduction of Jupyter Notebooks. It is however a paid course.

Students with some programming experience may then try to implement the number guessing algorithm they formulated earlier in Python. Two implementations, one where the machine guesses a user's number and one where the machine competes against itself are offered in a Jupyter Notebook.

## Files
- [Number\_Guessing\_Algorithm.ipynb](./hands_on/Number_Guessing_Algorithm.ipynb)