[Home](../../README.md) / [Sessions](../README.md) / Session 2: Data

# Session 2: Data

- [Lecture](#lecture)
    + [Exercise 1: What data is produced when visiting a website](#exercise-1--what-data-is-produced-when-visiting-a-website)
    + [Exercise 2: Explore data and traffic in Web Inspector](#exercise-2--explore-data-and-traffic-in-web-inspector)
    + [Exercise 3: Manipulate data using Web Inspector](#exercise-3--manipulate-data-using-web-inspector)
    + [Exercise 4: Download and inspect Facebook data](#exercise-4--download-and-inspect-facebook-data)
    + [Exercise 5: Create a personality profile from Facebook data](#exercise-5--create-a-personality-profile-from-facebook-data)
    + [Exercise 6: Find out what Facebook knows](#exercise-6--find-out-what-facebook-knows)
  * [References](#references)
- [Reading](#reading)
  * [Performing a Vanilla Self: Respectability Politics, Social Class, and the Digital World](#performing-a-vanilla-self--respectability-politics--social-class--and-the-digital-world)
  * [Psychological targeting as an effective approach to digital mass persuasion](#psychological-targeting-as-an-effective-approach-to-digital-mass-persuasion)
  * [Weapons of Math Destruction](#weapons-of-math-destruction)
- [Hands-On Exercise](#hands-on-exercise)
  * [Files](#files)

## Lecture

> Slides: [Data](lecture/slides_data.md)

The lecture begins with a working definition of data, emphasising that data is not neutral and given, but something that has been collected. [Johanna Drucker's](http://www.digitalhumanities.org/dhq/vol/5/1/000091/000091.html) concept of 'capta' is used to illustrate this. Recent work by [Catherine D'Ignazio and Lauren Klein](https://bookbook.pubpub.org/pub/zrlj0jqb), and [Mimi Onuoha](https://github.com/MimiOnuoha/missing-datasets) underline how  data that is being captured and – crucially – data that is not being recorded reflects structural racism and mysoginy. A brief history of data covers cuneiform tablets and punch cards. Early innovations in big data processing, relying on the idea of data records as well as women's labour, are discussed through research by [Christine von Oertzen](https://www.mpiwg-berlin.mpg.de/users/coertzen).

The lecture then continues to look at data on the web: how data is being transmitted, where it is captured and stored. This second part contains six hands-on exercises that are outline below.

### In-class exercises

The following exercises appear in the lecture slides and can be done with the entire class. Some of them require a Facebook account. When doing these exercises, be sure to prepare a dummy Facebook acount for your students to use for if they do not have or do not want a Facebook account.

#### Exercise 1: What data is produced when visiting a website

In addition to the data that is being disclosed and transmitted as part of HTTP, websites can gather additional data through client side APIs and JavaScript. 

[Artificial Senses](https://artificial-senses.kimalbrecht.com) is an experiment by [Kim Albrecht](http://www.kimalbrecht.com) that visualises some of the data browsers are able to gather.

Students are invited to explore the experiments on different devices.

Data that websites have access to includes location data, mouse movements, touch, accelerometer and orientation sensors, webcam and microphone data etc. Only some of those (e.g. location, webcam and microphone) require a user's consent. Mouse movements and orientation data, for instance, can be captured without users being made aware.

#### Exercise 2: Explore data and traffic in Web Inspector

Most desktop browsers come with developer tools that let users inspect the code of websites, the data they store and network traffic they create. In Chrome and Safari on MacOS it is available by pressing Command+Alt+I, or by pressing F12 in Internet Explorer and Microsoft Edge.

Students are invited to navigate to a website (e.g. their university website, a social nework) and look at the data the websites store (under Application->Local Storage). Facebook for instance stores a variety of data, such as drafts of status updates and comments.

The Network tab provides insights into data that is being transmitted. Facebook in particular transmits data even when the user does not navigate the page. Combine this with the knowledge from the previous exercise about which data can be gathered.

#### Exercise 3: Manipulate data using Web Inspector

Another useful feature of the Web Inspector is that it allows you to manipulate the code of a website. By right clicking on an element and selecting Inspect this lets you edit the content of a website.

Ask students to create a fake Tweet.

![A fake tweet](lecture/assets/fake_tweet.jpg)


#### Exercise 4: Download and inspect Facebook data

Request and download your Facebook data, or data from any other social media site. Look at the files and inspect their content. Consider what kind of data might be stored in addition to what Facebook is willing to give you.

#### Exercise 5: Create a personality profile from Facebook data

The website [applymagicsauce.com](http://applymagicsauce.com) allows you to upload your Facebook data along with data from other social networks in order to create a personality profile that can be used for advertising.

Before completing this exercise, make sure that students understand the implications of uploading their data to a third-party website.

#### Exercise 6: Find out what Facebook knows

As we have seen when inspecting the personal data Facebook provided, a lot of data might be missing. To gain an insight into what kind of data Facebook stores and how it seeks to derive knowledge from it you can use their ad builder.

The [Faceook Business](facebook.com/business) platform allows you to define an audience for an ad. The criteria that can be defined are very specific, such as political interests, association with other people, hobbies, beliefs etc. Facebook provides a feedback of the targeted audience size.

1. Use the Audience Builder to find out how many students at your university are interested in cats vs dogs.

2. Use the Audience Builder to construct the audience for a political ad of a party of your choice.

### References

D’Ignazio, C., & Klein, L. (2019). Bring Back the Bodies. In Data Feminism. Retrieved from https://bookbook.pubpub.org/pub/zrlj0jqb

Drucker, J. (2011). Humanities Approaches to Graphical Display. Digital Humanities Quarterly, 5(1). Retrieved from http://www.digitalhumanities.org/dhq/vol/5/1/000091/000091.html

Evans, J. (2019). HTTP: Learn your browser’s language. Retrieved from https://gumroad.com/l/http-zine

Latour, B. (1986). Visualisation and Cognition: Drawing Things Together. Knowledge and Society Studies in the Sociology of Culture Past and Present, 6, 1–40.

Onuoha, M. (2019, December 12). MimiOnuoha/missing-datasets. Retrieved 20 December 2019, from https://github.com/MimiOnuoha/missing-datasets (Original work published 3 February 2016)

von Oertzen, C. (2017). Machineries of Data Power: Manual versus Mechanical Census Compilation in Nineteenth-Century Europe. Osiris, 32, 129–159.

## Reading

:point_right: Session bibliography on [Zotero](https://www.zotero.org/groups/2422637/what_machines_cant_learn/tags/Data/library)

### Performing a Vanilla Self: Respectability Politics, Social Class, and the Digital World

_Mikaela Pitcan, Alice E. Marwick, Danah Boyd_

Pitcan, M., Marwick, A. E., & Boyd, D. (2018). Performing a Vanilla Self: Respectability Politics, Social Class, and the Digital World. Journal of Computer-Mediated Commuication, 23, 163–179. https://doi.org/10.1093/jcmc/zmy008

This paper gathers the experiences of young people of low socio-economic status in New York who describe the strategies they (have to) use when presenting themseves on social media platforms.

Rather than expressing their personality, they edit themselves to appear respectable towards a white middle and upper class audience. This includes "using standard English rather than African-American vernacular English" and not uploading photographs that could be used to make them appear less respectable:

> available “unrespectable” images may be a danger for victims of color, as they are often used to justify negative media portrayals and the less respectable images yield less empathy among viewers and harsher public opinions

The interviewed young people both self-police their online presence as well as the presence of their peers. Women of colour in particular face the need to promote morality and de-emphasize sexuality online in order to not be subjected to criticism and violence.

### Psychological targeting as an effective approach to digital mass persuasion

_S.C. Matz, M. Kosinski, G. Nave, D.J. Stillwell_

Matz, S. C., Kosinski, M., Nave, G., & Stillwell, D. J. (2017). Psychological targeting as an effective approach to digital mass persuasion. Proceedings of the National Academy of Sciences, 114(48), 12714–12719. https://doi.org/10.1073/pnas.1710966114

The paper outlines how online advertisement can be more individually targeted when it is geared towards the recipients personality profile. Ads are matched for psychological trait such as introversion vs extraversion and level of openness to new experience.

The personality traits are derived from social media data. Data from the [myPersonality.org](http://www.mypersonality.org) database is used for the study. This data has been removed in the aftermath of the [Cambridge Analytica scandal](https://en.wikipedia.org/wiki/Facebook%E2%80%93Cambridge_Analytica_data_scandal).

What is striking in this study is that not a lot of data is needed to improve the performance of targeted advertising. A single like is enough to create a personality traits profile for a Facebook user.

### Weapons of Math Destruction

_Cathy O'Neill_

O’Neill, C. (2016). Chapter 4: Propaganda Machine. In _Weapons of Math Destruction_. New York: Crown.

In her book O'Neill discusses the harmful effects of algorithms, specifically those that she characterises as Weapons of Math Destruction (WMDs): algorithms that are opaque, unregulated and applied at large scale.

The fourth chapter, Propaganda Machine, describes how for-profit universities use online advertisement to target vulnerable people and people of low socio-economic background. Government rules allow students to cover up to 90% of their tuition fees through loans, which means that poor students are exploited twice: they are sold both poor education and unfavorable student loans.

The chapter presents how diploma mills and payday loan lenders develop and employ WMDs with damaging effects for people's lives.


## Hands-On Exercise

Students are invited to analyse their Facebook comments through basic Natural Language Processing methods implemented in a Python notebook using [NLTK](https://www.nltk.org/).
The input JSON file is read and prepared for analysis by removing stop words. A statistical look at the vocabulary used provides initial insights. The pre-processed text can then be analysed in, for instance, using [Voyant](https://voyant-tools.org/).

### Files

- [Facebook\_Analysis.ipynb](./hands_on/Facebook_Analysis.ipynb)