---
layout: post
title: Geometric Intro To Probability
---

# Work in progress
## Motivation

Q1 &rarr; *1% of women at age forty who participate in routine screening have breast cancer. 80% of women with breast cancer will get positive mammographies. 9.6% of women without breast cancer will also get positive mammographies. A woman in this age group had a positive mammography in a routine screening. What is the probability that she actually has breast cancer?*

**ALERT** - Solving this question using a calculator and Bayes's Theorem is easy. What I challenge you to do is without picking up your calculator or writing a single digit, estimate the answer upto an accuracy of let us say $\pm 5\%$. And yes, you are allowed to use pen-paper but only for diagrams.

**tl;dr** Try to estimate the answer, without explicitly applying the Baye's Theorem.

> But why, would be your next logical question.  
> Well, take a simpler question.  
> Q2 &rarr; Given a dice, what is the probability that it will land upon a prime number ?  
> You won't even take 10 seconds, to do this question. You are proficient with a question like this to the extent that you can visualize all the possible 6 dice throws and consider only those in which a prime number comes. Aka, you can visualise the question. 

But can you visualise the original question asked ? 
Well, if you can and got the answer correct by merely eyeballing, then you may altogether ignore this blog post. But if not, then I would urge you to read forward.

## Abstract

In the coming few paragraphs, I will try to gradually build up on different visualisations which I personally think of for different kind of scenarios. I assume you already would know about most of these, but the idea here is not to merely show the method, but to inutively question the "why"

## Independent Events

Before handling questions where events are inter-dependent on each other making things complex (as seen in Q1), first let us handle the simple cases.

#### Case 1 - A single event (Relevant to Q2)
Let us say we have an event $A$. Let, the probability of the event be $P(A)$. 
Now how do we visualise this probability - 

 - Let all the possibilities be named as $a_{1}, a_{2}, ... $. Now formally $P(A) = n(A) / n(Total)$, where $n(A)$ stands for the number of possibilies where event $A$ happends and $n(Total)$ stands for the total number of possibilities.
 - So we could represent all these possibilities $a_{1}, a_{2}... $ as points on an axis, and let the green points be those which belong to $A$ and red points be those which don't.
 - Add_diagram_here

#### Case 2 - 2 independent events
What does 2 independent events mean firstly?
Answer...
Let us say we have another event $B$ and similarly let us define $P(B)$ as the probability of $B$ happening and $b_{1}, b_{2}, ... $ be all the possibilities, out of which a subset of them belong to $B$ and others don't, such that $P(B) = n(B) / n(Total)$

 - Now how do we represent this visually ?
 - On the same line we could both of these events, something like this - 
 - Add_diagram_here
 - But is this diagram good enough for our purpose ?
 - Unfortunately no, because it doesnt provide us with the answers to the relationships between these 2 events.
 - Example - Let us try to determine $P(A \cup B)$, it should be basically be n(pairs of $a_{i}, b_{j}$, where $a_{i}$ belongs to A or $b_{j}$ belongs to B) / n(all possible pairs)
 - Now what is this in our above diagram ?
 - Well if the number of possibilities are finite, then we can do arithmetic and multiply quantities, but does that satisfy us ?
 - No, because our aim was to obtain it visually not algebraically.
 - Ah! Moment, we can simply rotate the line segment of B by 90 degrees, and treat this as a 2 dimensional thing.

