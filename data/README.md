# Dataset Documentation

This document provides information about the datasets used in the phishing detection project.

## Raw Data Files

### urlset.csv
This file contains raw phishing URLs collected from PhishTank, a collaborative clearinghouse for data about phishing websites.

**Source:** [PhishTank](https://www.phishtank.com/)

**Format:**
- Contains URLs that have been verified as phishing attempts
- Additional metadata may include verification status, submission date, etc.

### verified_online.csv
This file contains legitimate (non-phishing) URLs used as a control dataset.

**Source:** [Common Crawl](https://www.commoncrawl.org/)

**Format:**
- Contains URLs that are known to be legitimate/benign
- May include various categories of websites (e.g., news, e-commerce, educational)

## Processed Data Files

### legitimate.csv
Features extracted from the legitimate URLs in the raw data.

### phishing.csv
Features extracted from the phishing URLs in the raw data.

### urldata.csv
Combined dataset with features from both legitimate and phishing URLs.
