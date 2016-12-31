# Scoring

This document outlines the process of scoring content for truthiness.
We will return a score that represents the probability that this content
is trustworthy.

The following are categories of metadata that will be used:

## Sources

- **Publisher** is one factor in trustworthiness. Some websites attempt to gain credibility by stealing branding and using similar domain names. For example, abcnews.com.co is not affiliated with [ABC News](http://abcnews.go.com/), but uses a similar logo and domain name to make their content appear more credible.
- **Author** is another factor in trustworthiness.  Often, "fake news" will also use a fake byline.  An author's history is one way to determine the legitimacy of the content.
- **Deep links** can be processed to determine whether they come from reliable sources. If the article links to other unreliable sources or the article contains no sources at all, then the content is less likely to be true.

## Dates

- **Publish dates** should be consistent with the content. For example, [Ending the Fed](http://endingthefed.com/since-donald-trump-won-the-presidency-ford-shifts-truck-production-from-mexico-to-ohio.html) copied a [CNN story from 2015](http://money.cnn.com/2015/08/13/news/companies/ford-truck-mexico-ohio/) and re-wrote the headline to tell a different narrative.  Current articles that reference old stories are a potential sign that something is being taken out of context.

## Text Analysis

- **Spelling and grammar** are red flags because credible news organizations have style guides,copy editors, and review processes in place.
- **All-caps and excessive punctuation** are also red flags. ARTICLES THAT SCREAM AT YOU ARE LKELY TO BE FAKE!!!

## Images

- **Images** can be taken out of context to tell a different story. Services like [TinEye](https://www.tineye.com/) can be used to verify the image source and compare it to the context of the article.

## HTTPS

- **Encryption** can be seen as a publisher's willingness to certify the authenticity of their content. HTTPS is the minimum requirement to let readers know that the content they are reading is coming unaltered from the publisher.

## Crowd-sourcing

Crowd-sourced verification is dangerous because social networks (trolling) can game the system. If this is used as input to a neural network, then our model would incorrectly classify content. However, there is some value in crowd-sourcing the validity, even if it makes up a smaller portion of the overall score.

- **Social verificaton** would ideally require login from a social network, such as Facebook or LinkedIn, to verify that content is credible.

## Machine learning

Machine learning would be useful for automated classification.  The training data should come from professional fact-checkers or verified sources to ensure accuracy.
