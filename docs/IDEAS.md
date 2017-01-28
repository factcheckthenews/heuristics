## Unimplemented Ideas

These criteria are not implemented, but could be useful at a later time.

### Sources

- **Author** is another factor in trustworthiness.  Often, "fake news" will also use a fake byline. An author's history is one way to determine the legitimacy of the content. This is currently not implemented because it is fairly difficult to parse out the author's name from non-standard HTML documents. HTML meta tags cannot be relied upon because they aren't always used (or they're used incorrectly). Furthermore, every website places the author's name in a different place.
- **Deep links** can be processed to determine whether they come from reliable sources. If the article links to other unreliable sources or the article contains no sources at all, then the content is less likely to be true.  Parsing links is not difficult, but it could get expensive to process every link and store it in a database.

### Dates

This is useful, but the ROI for implementing this feature is low because it adds significant complexity and only provides a small amount of additional information.

- **Publish dates** should be consistent with the content. For example, [Ending the Fed](http://endingthefed.com/since-donald-trump-won-the-presidency-ford-shifts-truck-production-from-mexico-to-ohio.html) copied a [CNN story from 2015](http://money.cnn.com/2015/08/13/news/companies/ford-truck-mexico-ohio/) and re-wrote the headline to tell a different narrative.  Current articles that reference old stories are a potential sign that something is being taken out of context.

### Images

Image analysis is difficult (and resource intensive), but there are imaging APIs that could be used. At this time, these services are too expensive to use.

- **Images** can be taken out of context to tell a different story. Services like [TinEye](https://www.tineye.com/) can be used to verify the image source and compare it to the context of the article.

### Machine learning

Machine learning could be useful for automated classification.  The training data should come from professional fact-checkers or verified sources to ensure accuracy.
