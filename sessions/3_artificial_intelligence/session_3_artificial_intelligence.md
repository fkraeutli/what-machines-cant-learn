[Home](../../README.md) / [Sessions](../README.md) / Session 3: Artificial Intelligence

# Session 3: Artificial Intelligence


* [Lecture](#lecture)
* [Reading](#reading)
* [Hands-On Exercise](#hands-on-exercise)
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

#### ELIZA

A recreation of the original Eliza chatbot by Joseph Weizenbaum in a web-based implentation created by Norbert Landsteiner can be accessed here: https://www.masswerk.at/elizabot/

Even without coding skills it is worth to look at the source code, which can be downloaded on the same page. The code includes mainly two files. `elizabot.js` contains the programmes logic, while `elizadata.js` contains the chatbot's answers along with placeholders where elements of the user's questions are inserted.

Looking at the source code one can see how the chatbot's logic is relatively simple, while a lot of effort and thinking must have gone into the writing of the data. Weizenbaum must have carefuly outlined the possible trajectories a conversation might take and crafted answers that seem to take into account the user's inputs, but remain general enough to not require true understanding of the conversation.

#### Tensorflow Playground

Use the [Tensorflow Playground](
http://playground.tensorflow.org/) to recreate Rosenblatt's Perceptron, a one layer neural network with inputs for the X and Y coordinates. Try to solve one of the patterns that are not linearly separable, observing that a solution cannot be found without adding additional hidden layers.


## Reading

## Hands-On Exercise

### Files
