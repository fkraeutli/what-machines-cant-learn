[Home](../../README.md) / [Sessions](../README.md) / Session 3: Artificial Intelligence

# Session 3: Artificial Intelligence

- [Lecture](#lecture)
  * [Theories of Mind](#theories-of-mind)
  * [History of Artificial Intelligence](#history-of-artificial-intelligence)
  * [In-class exercises](#in-class-exercises)
    + [Exercise 1: ELIZA](#exercise-1--eliza)
    + [Exercise 2: Tensorflow Playground](#exercise-2--tensorflow-playground)
- [Reading](#reading)
  * [Is Metabolism Necessary?](#is-metabolism-necessary-)
  * [Minds, Brains, and Programs](#minds--brains--and-programs)
  * [What Computers Can't Do](#what-computers-can-t-do)
- [Hands-On Exercise](#hands-on-exercise)
  * [ELIZA](#eliza)
  * [Building a Simple Chatbot from Scratch in Python (using NLTK)](#building-a-simple-chatbot-from-scratch-in-python--using-nltk-)
  * [Files](#files)

## Lecture

This session introduces the topic of Artificial Intelligence through a philosophical and historical lens. The dominant theories of mind at the time the first artificial intelligence systems were implemented on modern computers are presented. It argues that the understanding of computing informed the understanding of the mind, and not the other way around. Researchers wanted to see the human mind as something that can, in principle, be implemented on a machine and theories of mind that would allow this were favoured.

The historical lecture introduces some of the first AI applications. Two competing approaches emerged: Symbolic AI, which is operates on an internal representation of the world based on pre-defined rules, and Connectionist AI, which derives the rules it operates on based on real-world examples. Symbolic AI emerges as the winner in this first competition. The lecture outlines the reasons for its success and subsequent demise.

### Theories of Mind

> Slides: [Theories of Mind](lecture/slides_theories_of_mind.md)

In order for a machine to exhibit intelligence, we first should get a sense of what we consider intelligence. At the time the first AI systems were developed, but still today, theories of mind, intelligence and cognition rest on the assumption of Dualism: that the mind can be a separate entity of the body and the world. If that were not the case, intelligence could not be implemented in a computer, separate from body and world.

AI-compatible theories of mind were therefore representational theories of mind. In this view the mind builds up an internal representation of the external world on which it operates. The body sends signals to the mind, allowing the mind to build up this representation and compute actions on it, sending signals back to the body which in turn operates on the world.

Alternatives to a representational theory of mind would be, for instance, [Direct Realism](https://en.wikipedia.org/wiki/Na%C3%AFve_realism), which argues against internal representation in favour of direct experience of the material world, and [embodied theories of mind](https://en.wikipedia.org/wiki/Embodied_cognition), which argue that cognition arises from the direct (bodily) interaction with the world. (Personally I am a defendent of these views)

Dualism enables, in principle, to instantiate a mind independently of the physical world. Another requirement for the possibility of implementing a mind on a computer is to make the mind able to exist independently from brain substance. This requirement can be fulfilled through the theory of Functionalism, which argues that functional properties (of the mind) supervene on physical properties (of brain substance) and are therefore not dependent on them.

### History of Artificial Intelligence

> Slides: [History of Artificial Intelligence](lecture/slides_history_of_artificial_intelligence.md)

This brief history of Artificial Intelligence begins with the coinage of the term through the 1956 Dartmouth College Summer Research Project. The lecture introduces two competing strands of Artificial Intelligence: Symbolic AI and Connectionist AI (the latter being synonymous with current Machine Learning techniques based on Neural Networks).

Symbolic AI emerged as the winner during these first golden years of AI. Connectionist AI suffered from limited computing power, unavailability of training data and, not the least, lobbying and bullying against Frank Rosenblatt and his Perceptron, an early implementation of a neural network.

The limits of symbolic AI however became all to eminent when it failed to live up to its promises. Connectionist AI did not perform well either, however. Although it was shown that multi-layer neural networks could in principle overcome some of the issues that critics of connectionist approaches outlined, a usable algorithm to train multi-layer networks was not developed until 1986.

However, symbolic AI failed not because it did not offer suitable and, for specific problems, very potent methods, but because their creators claimed that it could do much more than they were able to deliver. We see similar levels of over-promising and under-delivering in current machine learning hypes, too, which apply connectionist approaches.

### In-class exercises

The following exercises appear in the lecture slides and can be done with the entire class. 

#### Exercise 1: ELIZA

A recreation of the original Eliza chatbot by Joseph Weizenbaum in a web-based implentation created by Norbert Landsteiner can be accessed here: https://www.masswerk.at/elizabot/

Even without coding skills it is worth to look at the source code, which can be downloaded on the same page. The code includes mainly two files. `elizabot.js` contains the programmes logic, while `elizadata.js` contains the chatbot's answers along with placeholders where elements of the user's questions are inserted.

Looking at the source code one can see how the chatbot's logic is relatively simple, while a lot of effort and thinking must have gone into the writing of the data. Weizenbaum must have carefuly outlined the possible trajectories a conversation might take and crafted answers that seem to take into account the user's inputs, but remain general enough to not require true understanding of the conversation.

#### Exercise 2: Tensorflow Playground

Use the [Tensorflow Playground](
http://playground.tensorflow.org/) to recreate Rosenblatt's Perceptron, a one layer neural network with inputs for the X and Y coordinates. Try to solve one of the patterns that are not linearly separable, observing that a solution cannot be found without adding additional hidden layers.


## Reading

### Is Metabolism Necessary? 

_Margaret A. Boden_

Boden, Margaret A. (1999). Is Metabolism Necessary? British Journal for the Philosophy of Science, 50, 231–248.

In this article Boden discusses the conditions for (strong) Artificial Life and its necessity for a physical body.

> Metabolism is a criterion of life. Three senses are distinguished. The weakest allows strong A-Life: virtual creatures having physical existence in computer electronics, but not bodies, are classed as ‘alive.’ The second excludes strong A-Life but allows that some non-biochemical A-Life robots could be classed as alive. The third, which stresses the body’s self-production by energy budgeting and self-equilibrating energy exchanges of some (necessary) complexity, excludes both strong A-Life and living non-biochemical robots.

_Boden, 1999, p. 1_

### Minds, Brains, and Programs

_John Searle_

Searle, John R. (1980). Minds, brains, and programs. The Behavioural And Brain Sciences, 3, 417–457.

This article presents John Searle's widely discussed Chinese Room argument. Searle presents a thought experiment in which a human sitting in a room answers questions in Chinese passed to him in writing by following a rule book without himself understanding Chinese. Searle argues therefore that even if a machine can converse in a way that appears intelligent, the machine itself does not understand the conversation.

Searles article is a reaction to some of the chatbots that have been developed in this time, with some of their creators arguing that they made machines that truly understand the conversations.

> I will consider the work of Roger Schank and his colleagues at Yale (Schank & Abelson 1977), because I am more familiar with it than I am with any other similar claims, and because it provides a very clear example of the sort of work I wish to examine. But nothing that follows depends upon the details of Schank's programs. The same arguments would apply to Winograd's SHRDLU (Winograd 1973), Weizenbaum's ELIZA (Weizenbaum 1965), and indeed any Turing machine simulation of human mental phenomena.

Searle, 1980, p. 417

### What Computers Can't Do

_Hubert Dreyfus_

Dreyfus, H. (1972). What Computers Can’t Do. MIT Press. https://archive.org/details/whatcomputerscan017504mbp

Part II: Assumptions Underlying Persistent Optimism (pp. 155-186)

This chapter of Dreyfus' book outlines four assumptions that underly (strong) artificial intelligence: 

> 1. A biological assumption that on some level of operation – usually supposed to be that of the neurons – the brain processes information in discrete operations by way of some biological equivalent of on/off switches.
>2. A psychological assumption that the mind can be viewed as a device operating on bits of information according to formal rules. Thus, in psychology, the computer serves as a model of the mind as conceived of by empiricists such as Hume (with the bits as atomic impressions) and idealists such as Kant (with the program providing the rules). Both empiricists and idealists have prepared the ground for this model of thinking as data processing – a third-person process in which the involvement of the "processor" plays no essential role. 
> 3. An epistemological assumption that all knowledge can be formalized, that is, that whatever can be understood can be expressed in terms of logical relations, more exactly in terms of Boolean functions, the logical calculus which governs the way the bits are related according to rules.
> 4. Finally, since all information fed into digital computers must be in hits, the computer model of the mind presupposes that all relevant information about the world, everything essential to the production of intelligent behavior, must in principle be analyzable as a set of situation-free determinate elements. This is the ontological assumption that what there is, is a set of facts each logically independent 

_Dreyfus, 1972, p. 156_

## Hands-On Exercise

### ELIZA

Download the [ELIZA source code](https://www.masswerk.at/elizabot/elizabot.zip) from Norbert Landsteiner's [website](https://www.masswerk.at/elizabot/).
Try to understand the structure of ELIZA's data in `elizadata.js`. Add some new answers and try to reach them through the chatbot's interface. Try to change ELIZA's personality.

### Building a Simple Chatbot from Scratch in Python (using NLTK)

A Jupyter Notebook implementation of [Parul Pandey's Chatbot example](https://medium.com/analytics-vidhya/building-a-simple-chatbot-in-python-using-nltk-7c8c8215ac6e).

### Files

- [ChatBot.ipynb](./hands_on/ChatBot.ipynb)