---
title: "Finding Alpha on the Internet Part 1"
date: 2022-01-04T21:46:34+08:00
draft: false
cover: /posts/covers/pexels-andrea-piacquadio-941555.jpg
author: Derek Wong
categories:
  - Research
tags:
  - Research
  - Process
---

The internet is teeming with resources for potential alpha. How do you separate the wheat from the chaff? In this series of blog posts, I will explain my process for identifying sources worth diving deeper into and extracting some kind of benefit to a portfolio or strategy. This will be a side-by-side view of my workflow as an individual. As of now, I have no idea what even to research or how I will go about doing it. So let us begin.

<!--more-->

Let me set expectations. First off, if you found it on the internet, it's probably not 'alpha' in the purest sense of the undiscovered profitable phenomenon. That is completely fine. It still may end up being something that helps our overall portfolio or inspires us to do something innovative with it. To be perfectly honest, where this ends up will probably be a dud. I am coming from the perspective of a single, at-home quantitative researcher. I will be using python and as much free data to do this as possible. If I use some other source, it will be noted.

Why are most ideas from the internet garbage? Well, there is survivorship bias in ideas. No one posts a bad backtest. Academics want their P values for publishing, not trading, and if it's excellent, you will not see it at all, and it will be cranking away returns in a room silently until it stops working. 

Some generalized reasons why things found on the internet does not work:

1. Not replicable. It could be cherry-picked. There is just not enough detail to copy the idea.
2. Edge is less than transaction costs.
3. Purely nonsense. This can be in the form of hybrid discretion, or the logical flow of the idea has gaps.
4. We lack the resources to try (infrastructure, data, processing, skills). Not necessarily the idea's fault, but if I cannot verify, I am back at square one anyway.

## Finding an idea worth pursuing

The first step is we need an idea. There are many blogs, tweets, youtube videos (i am still skeptical of these, I prefer written content), and pre-publishing websites.

My favorite places for idea scraping are (in no particular order):

- http://ssrn.com/
- https://arxiv.org/
- https://quantocracy.com/
- https://quantpedia.com/
- https://www.sr-sv.com/

![pexels-pixabay-277593](/imgs/internetAlpha/pexels-pixabay-277593.jpg)

## Selecting potential candidates

There are already hundreds of thousands of potential links, posts, and white papers on the resources I gave. What mainly am I looking for? This depends on what I am trying to build at the moment or something that strikes my fancy. Maybe improving my machine learning game since it's a new area for me. Or I have a specific use case, e.g., to enhance a portfolio optimizer. So I have 3 approaches.

1. I have a specific problem that needs solving, so I can immediately hone in on that area. E.g., regime detection or portfolio optimization.
2. I am interested in a new area and want to explore it. E.g., gaussian mixture models, machine learning, vol of vol.
3. I just stumble across a piece of content that I say, "oh, that's interesting."

We are faced with a barrage of information all the time. I have a backlog of bookmarks of things that require further inspection. Once you start just bookmarking something that fits any of those categories, you will have more research work than hours. 

I have narrowed it down to two ideas, one from SSRN and the other from a blog. I have only scanned through after reading the abstracts. This is a game of failing fast, if for any reason I read something and it does not pass the smell test it goes in the bin. 

1. [The Search for Crisis Alpha: Weathering the Storm Using Relative Momentum](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=2739520) By Nathan Faber of [Newfound Research](https://www.thinknewfound.com/)

2. 1. Crisis alpha always interests me as I am a divergent trader at heart and believe in the power of protecting the downside. Quickly reading the abstract, it seems relatively straightforward and uses liquid fixed-income ETFs for which data should be easy to obtain.

3. [Using an unsupervised machine learning algorithm to detect different stock market regimes](https://medium.datadriveninvestor.com/using-an-unsupervised-machine-learning-algorithm-to-detect-different-stock-market-regimes-5c6354a1826a) by [Ethan Johnson-Skinner,](https://ethanskinner94.medium.com/?source=post_page-----5c6354a1826a-----------------------------------)

4. 1. Regime detection and Gaussian Mixture Models are in my interest category and getting more into machine learning, so I will probably learn something while I build. Again, keeping data and resources in mind when evaluating as an independent. This article comes with python code and has 2 implementations. One uses only S&P 500 returns, which will be easy to source, and another uses macroeconomic data (which is just the 10 Year yield), so it should not be too bad. 

<!-- Begin Mailchimp Signup Form -->
<link href="//cdn-images.mailchimp.com/embedcode/horizontal-slim-10_7.css" rel="stylesheet" type="text/css">

<style type="text/css">
	#mc_embed_signup{background:#fff; clear:left; font:14px Helvetica,Arial,sans-serif; width:100%;}
	/* Add your own Mailchimp form style overrides in your site stylesheet or in this style block.
	   We recommend moving this block and the preceding CSS link to the HEAD of your HTML file. */
</style>
<div id="mc_embed_signup">
<form action="https://dwongresearch.us5.list-manage.com/subscribe/post?u=142fa4a592b63e3b9722442ef&amp;id=6c4483a227" method="post" id="mc-embedded-subscribe-form" name="mc-embedded-subscribe-form" class="validate" target="_blank" novalidate>
    <div id="mc_embed_signup_scroll">
	<label for="mce-EMAIL">Subscribe</label>
	<input type="email" value="" name="EMAIL" class="email" id="mce-EMAIL" placeholder="email address" required>
    <!-- real people should not fill this in and expect good things - do not remove this or risk form bot signups-->
    <div style="position: absolute; left: -5000px;" aria-hidden="true"><input type="text" name="b_142fa4a592b63e3b9722442ef_6c4483a227" tabindex="-1" value=""></div>
    <div class="clear"><input type="submit" value="Subscribe" name="subscribe" id="mc-embedded-subscribe" class="button"></div>
    </div>
</form>
</div>

<!--End mc_embed_signup-->

## Next Steps

Now I have to read both of these papers and decide which one to move forward on. I am going to be thinking about a few things while I read.

1. Can I understand the basic principles of why this should work?
2. What resources do I need to put together to replicate this (data, code, packages, study some background information)?
3. How do I replicate this as close to the paper as possible? If there are some gaps in the logic, or things are vague what assumptions do I need to make? Are the logical leaps too large?

I will read these and answer those questions. Coming up next, I will select the paper to move forward with, and answer the above questions. 



Photos:

Cover Photo by **[Andrea Piacquadio](https://www.pexels.com/@olly?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)** from **[Pexels](https://www.pexels.com/photo/photo-of-a-woman-thinking-941555/?utm_content=attributionCopyText&utm_medium=referral&utm_source=pexels)**

