---
layout: post
title:  "Lunch with Marc Raibert"
date:   2014-12-06 12:00:00
categories: Robotics
---

This year’s Nyquist Lecture in Electrical Engineering was given by Marc Raibert, ex-professor of Electrical Engineering and Computer Science at CMU and MIT, and the founder of [Boston Dynamics](https://www.youtube.com/results?search_query=boston+dynamics). I was fortunate to have the opportunity to join Dr. Raibert for lunch prior to his talk. 
I was particularly excited about this because Boston Dynamics is a singularly technologically advanced business.  Their robots are the most advanced in the world, and their demos are jaw-dropping. If you haven't seen their demos yet, you owe it to yourself to [check them out at this link](https://www.youtube.com/results?search_query=boston+dynamics)!  How does a company like that come to be? What are the secrets of building such an advanced product? 

Here are some of the surprising things that Dr. Raibert said.

## “The biggest limitation in mobile robots is power"

What is the biggest limitation to mobile robots? It isn’t perception, it isn’t control algorithms, it is power storage and delivery. Currently, robots are far less efficient than humans and far noisier. 

To illustrate this limitation, take the Big Dog robot. The robot is driven by a ~15 horsepower gas-hungry Go-Kart engine. The engine drives a compressor that pressurizes oil to 3,000 PSI. The legs then move based on the variable firing of actuators in the legs, allowing the pressurized oil to flow in.

Whereas a human is perfectly silent while walking, Big Dog is loud - as loud as a Go-Kart. Whereas a human can walk hundreds of miles without sustenance, Big-Dog can walk 10 miles.

Things have improved in recent years. Alpha Dog is now quieter than Big Dog, can carry more load, and has double the range.

Batteries are currently nowhere near energy dense enough to drive these mobile robots. “It is hard to see enough battery improvements coming in the near future to afford their use in mobile robots." 

## “Simple designs"

Open-loop control is the method of control by which the engineer uses a model of how an input affects an output. In order to achieve the desired output, the engineer uses the model to determine how much input to apply. Creating the model is often very complex and time consuming. 

Closed-loop control is the method of control by which the engineer does not have a model of how the input affects the output. In order to achieve the desired output, the system varies the input, then using a feedback loop, ascertains whether that change in input affected the output quantity positively or negatively. Based on this feedback, the system then applies more of the same input or less of it, to eventually iterate towards the desired output. This method is iterative and easier to create.

Upon being asked whether Boston Dynamics focuses more on open-loop control or closed-loop control, Dr. Raibert answered that Boston Dynamics mostly uses simple closed-loop control. “Our robots have thus far been the most capable, which is evidence that at least up until this point, simple has been the right way to go.” 

I found this answer to be particularly surprising. Whereas PetMan, Alpha Dog, and Cheatah look to be the furthest thing from simple from the outside, the mechanism that drives them is the simplest available. 

## “Calibrate your time-constant"

Expanding upon the answer on the Boston Dynamics brand of control theory, Dr. Raibert briefly took a step back to wax philosophical. Some people choose a grand project that is very far away, whereas others focus on an approach that will work now, and then iterate on that approach.

“I happen to believe that by taking the latter approach, you are more likely to reach your grand vision, but some people don’t agree.” We all have to choose which time constant we are aiming for. Boston Dynamics has chosen the short, iterative time constant, which has thus far led to the world’s most advanced robots.

## “Decide who you are”

One may think that “the world’s most advanced all-terrain mobile robots” is a pretty specific mission statement.

According to Dr. Raibert, you need to be even more specific. Why aren’t their robots designed to be more aesthetic, safer, and even more efficient through improved product design?

"You need to decide who you are… we are an R&D outfit that is trying to make advanced technology. We aren’t trying to package a product.”

Product design and advanced technology R&D are different skill sets. Organizations that do both often have problems straddling. Having to choose which of the skills to divert precious engineers to is a real problem. Some robot companies suffer from this straddling. For example, iRobot does both military robots and the Roomba. Moving in both of these directions can cause resource conflicts.

## “Specific functions”

Designers should “leave science fiction at the door” and build practical robots. Much of the general public feels that if we build a robot that appears human-like, it will somehow be human. However, robots are machines - they are not humans. Like all other machines, robots should be built with a particular function in mind, and their form should follow function. 

Boston Dynamics has built some humanoids, which people may consider “general purpose.” But they only did so when driven by functional requirements. For example, one of their humanoids was designed for durability testing of human uniforms, and therefore needed to be in the human shape in order to wear and stress-test the uniforms.

## Conclusion

Prior to this lunch, Boston Dynamics seemed to me as operating in some alternate reality as far as businesses go. Instead of making a simple web app, or a commodity like toothpaste, they produce these incredible walking robots that seem to have been beamed back straight from the future. My default belief was that they must be operating on some different principals than most other businesses: that they had a longer time-constant, that they had a way to manage very complex models, or that they had a more philosophical view of the future than other companies. 

In fact, the opposite seems to be true. Boston Dynamics' laser-like focus on pragmatic, common sense principals enables them to create this amazing technology. Their robots are specifically functional, built with simple models, in an iterative way. Having the opportunity to briefly peer inside Boston Dynamics was a nice reminder that it is these basic fundamentals that are at the core of even technological outliers.
