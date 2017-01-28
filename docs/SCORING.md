# Scoring

The API will return a score that represents the credibility of the input URL.

## Credibility Checklist

The following are criteria that will be used to determine credibility.

> **NOTE**: [Ideas](IDEAS.md) for new criteria are in another document.

### Sources

- **Publisher** is one factor in trustworthiness. Some websites attempt to gain credibility by stealing branding and using similar domain names. For example, abcnews.com.co is not affiliated with [ABC News](http://abcnews.go.com/), but uses a similar logo and domain name to make their content appear more credible.

### HTTPS

- **Encryption** can be seen as a publisher's willingness to certify the authenticity of their content. HTTPS is the minimum requirement to let readers know that the content they are reading is coming unaltered from the publisher.

### Text Analysis

- **Spelling and grammar** are red flags because credible news organizations have style guides, copy editors, and review processes in place.
- **All-caps and excessive punctuation** are also red flags. ARTICLES THAT SCREAM AT YOU ARE LIKELY TO BE FAKE!!!
- **Slander** words are used to defame or harm the reputation of another individual. Credible sources do not resort to ad hominem attacks, so the presence of these terms can be used to detect untrustworthy content.

### Crowd-sourcing

- [Web of Trust](https://www.mywot.com/en/aboutus) is a website reputation and review service that helps people make informed decisions about whether to trust a website or not. Web of Trust data enables us to provide a reputation score and a level of confidence in that score.

