# Essays-on-topics-in-Algorithmic-Data-Analysis
Here are some of the essay reports I wrote after critically analysing papers in specific domains of algorithmic data analysis.

Topic 1: Deep Learning: The Best Thing Since Sliced Bread or Just Another Bottle of Snake Oil?
To answer to this assignment, you must have a good understanding of machine learning techniques in general, and deep learning techniques in special.
The most talked-about data analysis topic of last year or two has definitely been deep learning. Many researchers have claimed that they have obtained impressive results with deep learning: they can classify images [7], write LaTeX articles that almost compile [8], dream up images [9], and even win the best humans on GO [10].
Explain what is deep learning and how did the cited applications use various deep learning techniques. Do they all use one unified "deep learning algorithm"? If not, explain the differences and similarities between the approaches. Are they all really only about deep learning? For example, in your opinion, is the AlphaGo primarily deep learning or reinforcement learning method? Did it do all feature selection automatically, or were there hand-crafted rules?
And have all these applications really been resounding success stories? Read also [11] and [12]. How do they effect on your opinion on deep learning? Does deep learning have anything to do with data mining and knowledge discovery? Is deep learning the best thing since sliced bread, just another bottle of snake oil, ill-defined term under which people place all kinds of research, or what?

Topic 2: Look, Mom, no hands!
One of the advantages of using Minimum Description Length (MDL) [1] is that it allows to define parameter-free methods [2]. Some people go as far as claiming this is the future of data mining [3] as it allows for true exploratory data mining. Is this so? Where did the parameters go, and what about any assumptions? Is MDL a magic wand? What if we do not like what MDL says is the best? Discuss critically.

Topic 3: Caveat Lector

Determining causal relations from data is perhaps the holiest of grails in data mining. Not surprisingly, it is not an easy task. We recently proposed a new approach to inferring whether XX causes YY, or vice versa. The main principle is simple; if describing XX is easier when given YY, than vice versa, we say that YY is more likely to be caused XX than vice versa. Our first attempt to instantiate this principle was by defining a practical score based on cumulative entropy. Experiments show it works rather well. At the same time, it's a first attempt. And first attempts always mean there are some points of improvement.

In this assignment your task is to carefully read [6] and critically discuss it. That is, identify the most important choices the author makes, and evaluate whether you agree with him, or whether alternate solutions (also) make (more) sense. In other words, find as many points of improvement of the principle, as well as of the practical instantiation, as possible. That is, you should consider every aspect critically. Does considering ΔX′→YΔX′→Y instead of ΔX→YΔX→Y really make more sense? Further, instead of calculating it directly, we estimate conditional and multivariate cumulative entropy. What are the effects of the way we estimate it on the causality score? Would it be possible to improve in theory? Would it be possible to improve in practice? How?

(Bonus) Recall from the lecture that Heikinheimo et al. [7] show how to mine low entropy sets and trees, and that these trees may seem to represent some kind of causality. Investigate the connection to [6].
