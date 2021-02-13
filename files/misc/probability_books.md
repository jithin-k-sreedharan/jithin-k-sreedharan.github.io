---
title: Suggestions for Probability Books
author: Jithin K. Sreedharan
date: November 9, 2018
header-includes:
    \usepackage{fancyhdr}
    \pagestyle{fancy}
    \fancyhf{}
    \rhead{Jithin K. Sreedharan}
    <!-- \lhead{Lesson 1} -->
    \cfoot{\thepage}
<!-- urlcolor: blue -->
colorlinks: true
---

A friend asked me what is the best comprehensive book on probability that he can purchase for using as a reference. I find it is a bit difficult to answer. According to me, the books based on probability may be roughly classified into the following categories:

* elementary probability: counting arguments, developing intuition, random variables, basic inequalities, basic notion of convergence. These area needs to be very strong. While doing research, we usually encounter various scenarios to model a situation, event or experiment with probabilistic tools, and it challenge us if the basics are not very strong. This is usually the first and crucial step in any research project that is based on probability models.
* probability theory (non-measure theory): syllabus of graduate level course for non-math students. Rigorous explanation and proofs of elementary probability theory. This can also include discrete martingales. This course will be enough for developing probabilistic arguments and writing proofs for a research paper (non-math). A lighter version of this course could be taught for CS first year graduate students.
* probability theory (measure theory): the rigorous study of probability. This is a must course for someone who is going to spend their life on probability. Most of the intriguing and complicated concepts in probability could only be explained in terms of measure-theoretic probability theory.
* stochastic process: various topics such as Markov chains, random walks, discrete and continuous time martingales, and many more.
* statistics: theory of detection and estimation, sampling, theory of machine learning, pattern recognition.

## From my experience
Many of the mathematical topics require years to fully comprehend it. One needs to take a course on the subject (or have proper systematic self study including problem solving and proof writing) and reuse what has learned multiple times in various contexts in various projects. During the later process, one usually refers to the books he/she learned in the former step, would usually know the exact page or location of various topics in a book and would have scribbled little tips and tricks that would quickly help him/her to recollect the material. This is a must if you are serious in a subject, no amount of online learning or Wikipedia can replace it, but may supplement the learning though.

#### Elementary probability
* Introduction to Probability (2e) by Bertsekas and Tsitsiklis.

#### Probability theory (non-measure theory)
* [Probability: A Graduate Course by Allen Gut](https://www.amazon.com/Probability-Graduate-Course-Springer-Statistics/dp/1461447070/ref=dp_ob_title_bk):
Covers basics, convergence in details. The books looks like comprehensive, but does not contain stochastic process. Proofs are very clear. It follows similar style of the author's book on random walks.

* Bruce Hajek's (UIUC) notes: This was used in IISc ECE first year graduate level course on probability. Available online.

* Probability and Counting: Mitzenmacher and Uller. Helps to develop good intuition, and explains many tough topics (mixing times, martingales) in probability theory in an easy way. Mostly oriented towards computer science curriculum (`probability method` sort of)

#### Probability theory (measure theory)
* Probability and Measure by Billingsley
* A first look at rigorous probability theory by Jeffrey Rosenthal: lacks real-life examples, but quite compact and well-written.
* Probability Essentials by Jacob and Protter: very compact book, contains most of the probability topics (up to discrete martingales). This was Vinod Sharma (my MS thesis advisor in IISc) followed and used a quick reference.

#### Stochastic process
* Anurag Kumar's notes on SPQT (Available online. Great notes. Lucid explanation)
* Markov Chains: Gibbs Fields, Monte Carlo Simulation and Queues by Bremaud: Excellent book, especially on many topics of Markov chain monte carlo simulation.
* Markov Chains and Mixing Times by Levin, Wilmer, and Peres (2nd edition): Modern treatment of Markov chains. Must for anyone who is working on discrete Markov chains
* Stochastic Processes by Sheldon Ross: classic book, great explanation. (followed in some of the IISc courses.)
* [Markov Chains and Stochastic Stability](https://www.amazon.com/Stochastic-Stability-Cambridge-Mathematical-Library/dp/0521731828/ref=pd_sim_14_4?_encoding=UTF8&pd_rd_i=0521731828&pd_rd_r=e6c862f4-e40d-11e8-a1fe-b9bdda55dff4&pd_rd_w=CbYKi&pd_rd_wg=uSeh1&pf_rd_i=desktop-dp-sims&pf_rd_m=ATVPDKIKX0DER&pf_rd_p=18bb0b78-4200-49b9-ac91-f141d61a1780&pf_rd_r=EERNMVBCRZH6RW94T2CQ&pf_rd_s=desktop-dp-sims&pf_rd_t=40701&psc=1&refRID=EERNMVBCRZH6RW94T2CQ): Requires measure theoretic background. Very comprehensive book with extensions to abstract spaces.
* Applied Probability and Queues by Ross: A pioneer in the field Prof. Borkar (IITB) suggested this book to get a initial grasp on the subject of MDP.

#### Statistics
* Theory of Point Estimation, 1983, and its companion book, Testing Statistical Hypotheses by E. L. Lehmann.


## Mathoveflow and math.stackexchange suggestions

#### Probability theory (non-measure theory):
* [Probability and Random Processes by Grimmett and Stirzaker](https://www.amazon.com/dp/0198572220/?tag=stackoverflow17-20): "It covers everything up to stochastic calculus without measure theory." (I had referred to it before, found as a good comprehensive book)
* One Thousand Exercises in Probability by Grimmett and Stirzaker. (good book to try many example problems in probability)
* [A Probability Path by S. Resnick](https://www.amazon.com/Probability-Path-Modern-Birkh%C3%A4user-Classics/dp/0817684085/ref=sr_1_1?s=books&ie=UTF8&qid=1540472478&sr=1-1): "advanced, but easy to read"


#### Probability theory (measure theory):
* Probability with Martingales by David Williams: Many good reviews. Short and concise introduction
* Many suggest to avoid Rick Durret's book!
* [A Course in Probability Theory (3e) by Kai Lai Chung](https://www.amazon.com/gp/product/0121741516/ref=dbs_a_def_rwt_hsch_vapi_taft_p1_i0): "is a good one that's rigorous". I have also heard good reviews about this book in my graduate classes.
* [Probability Theory: A Comprehensive Course (2014 Edition) by Achim Klenke](https://www.amazon.com/Probability-Theory-Comprehensive-Course-Universitext/dp/144715360X#customerReviews): Recent book, but good reviews

#### Statistics
* Statistical Inference by Casella and Berger
* All of Statistics by Larry Wasserman
* Theory of Statistics by Mark Schervish.
* Asymptotic statistics from Van der Vaart
* [Probability Theory: The Logic of Science by E. T. Jaynes  (Author)](https://www.amazon.com/dp/0521592712/?tag=stackoverflow17-20): To check

#### Related discussions:
* [stat.stackexchange link 1](https://stats.stackexchange.com/questions/414/introduction-to-statistics-for-mathematicians)
* [stat.stackexchange link 2](https://stats.stackexchange.com/questions/6538/mathematician-wants-the-equivalent-knowledge-to-a-quality-stats-degree?noredirect=1&lq=1): Books needed for becoming a good statistican (for some one with a PhD)
* [mathoverflow discussion](https://mathoverflow.net/questions/31655/statistics-for-mathematicians): Statistics for mathematicians

## To review/check (promising books)
[Probability in Electrical Engineering and Computer Science: An Application-Driven Course by Jean Walrand](https://www.amazon.com/Probability-Electrical-Engineering-Computer-Science/dp/0615899366/ref=sr_1_1?s=books&ie=UTF8&qid=1540475786&sr=1-1): Borkar reviwed it highly.

