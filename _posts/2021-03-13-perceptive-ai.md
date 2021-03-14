---
toc: true
layout: post
description: My thoughts on how we define "AI"
categories: [thoughts]
title: What is AI __really__?
---
# What is AI __really__?

### Intro

So I was doing computer vision tutorial on kaggle and it had been really interesting to learn imaage processing AFTER NLP and not vice versa. It's remarkable hwo similar the development of those fields are, and I had some interesting thoughts on it. Enjoy!

### AI vs DL vs ML vs Data Science

From my experience/knowledge/uderstanding, AI is a very specific term which is used somewhat interchangeable with ML and DL by many people. It is interesting how when learning more stuff about ML/DL/AI this distinction became more clear and intuitive for me. Data science is the field of data analysis in general, so pretty much anything you do involving data is data science. The term is so broad it is somewhat useless in my opinion. Then we have ML. ML is about statistics and "learning" data representations. I do not remember where I heard it, but someone said ML is statictics plus, and that is kind of how I like to think about it. It is a very math-heavy field, and, imo, pretty boring one. Saying that, I also did not really do much ML, so that is a pretty uneducated opinion.

Then we have DL. Deep learning, by definition, is just a type of machine learning which uses "deep nets." And I thinnk that is ... a good definition. It leads, ultimately, to the less obvious differences between ML annd DL. Because we have many hidden layers, DL necesarily acts like a black box. Also, DL is much less statistics and much more architecture and feature engineereing. Here you have CNNs, and RNNs, and Transformers, and GANs, and those "architectures" are much more conceptually based then ML algorithms. Like, youu get an idea for what RNN is and why you need and when you need because the structure itself is a result of human intuition rather than careful proof. There is nno proof that RNNs would be good for sequential data; there is probably not even a way to rigurously define "good" in this context. It is not like some mathematician somewhere proved that yeah, if you have sequential data, rnns would be great. It's an intuitive idea, which turned out to be true, and that's really fascinating. In DL,architectures are modeled by the way we, humans, think about stuff. Embeddings are not something "the statistics" would suggest as a solution; it is purely taken from the way humans think about words and complex categorization. For me, this what makes DL a much more compelling field then ML: the fact that it is "closer" to the mind, and closer to AI.

And what is AI? Is image recognition an AI? Is voice detection an AI? Is alpha Zero a AI? Is Dall-e an AI? Is GPT an AI? For me, some of those examples feel more like AI then others, but it is hard to pinpoint what makes them "more AI." I think it might be the degree to which they can innterract with humans? That is a bad definion though; it has nothing to do with the AI itself, and more with how we use it. Still though, image recognition system is predictable: it will recognize images. We kind of, in a way, have a clea expectation of what it is supposed to do. Same with voice detection. Alpha zero is ... trickier. It's suposed to be good at chess, but we dont have such specific expectations for its actions. We dont wait for it to make a particular move. In a way, it feels "more-AI" because it surpasses humans in its activity, making us unable to set concrete expectations. I think the same goes for Dall-e and GPT: they are so good, we do not know what to expect to of them. But there is more to it: they are "generative." I put quotation marks around that beccause in DL the term generative model has a specific meaning and technically all five would be "generating" something. By generating I more likely mean "repurposing" human input. Image recognition does not create new information for us, humans. Same with voie detection. Alpha Zero makes a move based on human input, not only "translating it." Same with Dall-e or GPT - they generate new information on human input, and not just convert the information from one form to another. 

I got off track. So, for me, AI seems like too broad of a definiton really. I think AI must be neccesarily an agent which a human has to be able to interact with. Image recognition is not AI in my opinion: it is a DL model with a very specific, predefined purpose. What makes AI "more-AI" is it's capability to create unique information.

Wow. That was a nice revelation. So yeah, I also want to talk about use cases of AI vs DL, but for now, let's talk more about this "more-AI" concept because it is really fascinating. What makes AGI? ability to create unique information __without__ human input. In other words, it has to be self-sufficient. I mean, this is so huge. It has to be adaptive, and it has to self-sufficient. 

So ... let's talk about those conditions.

#### Adaptive AI

I think this is gonna be a major research topic in the coming years. Because now, with the advent of "lucky ticket" concept for neural nets, the magic kinda wastes away and you see them for what they are - limited, rigid, functions, which we have a convoluted way to findd and define. But, inteligence is more than that. Ultimately, it's not even the fact that human intelligence is different from DL models, it's the fact those models fail in important ways because they lack adaptability. Again, as I am thinking about a possible solution here, I am coming back to human brainn and how it works, which is kinda interesting. You dont ddo that much in ML; there, you turn to math. I mean maybe you should turn to math here as well. What is a way to make something adaptable? What do we mean by adaptable? How much data should the model need to adapt? We dont want it freaking out with every example, but we also dont want to wait years to have enough data for a retrain. And also the process of training should be .. constant? how woudl that work? Maybe doing some reflexive module, where the model trains trying to understand itself? Or weight new examples higher than old to make them more relevant? Or just collect mroe data, so that the continuous training concept makes sense. Our minds are laways in motion; we never stop thinking. The model does; it never thinks. It's a function, a state of AI, so to say. what we call AI is really a snapshot of an AI. 

Which brings us to reinforcement learning? to make AI adaptive, we want it to learn from experiences. That sentence made 0 sense. I feel like RL is the solution, my intuition tells me that, but I can not quite put into words why I think that. 

### Perceptive AI

I will add this category in, because that's what I wanted to talk about initially, but I will go over it briefly. Humans collect a lot of data to worm with __constantly__. We need AI doing the same. Text + image + voice, but all in one model.

### To be continued... 

My brain hurts. I need to turn this into a series, add pictures, and be mroe concise with my writing. Will do tmrw.