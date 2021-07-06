---
title: "Twitter Misinformation Research"
date: 2021-07-06T22:49:07+09:00
draft: false
categories: [projects]
tags: [Python, Pytorch, NLP, XLNET, BERT, GPT-2, PostgreSQL]
---

### Researcher

A research project dedicated to differentiating between state-backed misinformation campaigns on Twitter with mentorship from Ariel Herbert Voss, PhD Harvard, fellow at Berkman Klein Center.

## Project Outline
We are investigating NLP methods for fighting misinformation campaigns on public forums and social media platforms like Twitter. The basic premise is to differentiate between state backed misinformation campaigns and regular tweets

 Currently we are mapping country origin of tweet based on a bert embedding similarity metric to existing Twitter misinformation database. Given that we can have a confidence score as to the origin of the tweet. This might be important later on for determining whether or not this is an authentic Twitter profile or behaves like a bot.

## Technology
 With cross institutional support and mentorship from Harvard's Ariel Herbert Voss we are employing state of the art NLP models like BERT, GPT-2, and XLNet for classification, clustering, regression, and semantic analysis tasks. 

## Data
 All good Machine Learning models require good data. Currently we are using Twitter's open disinformation data dumps which include millions of tweets from verified state-backed agencies and actors trying to spread disinformation. For supervised training tasks, we're using scraped data from twitter alongside pre-scraped and pre-compiled datasets online. 

