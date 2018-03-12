# python-web-scraper
Web Scraper that Scrapes my Blogs and Ingest the Data into Elasticsearch

## About

I have a couple of blogs running on ghost and a blog running on github-pages, and the idea was to have a central search ui, where this scraper will be responsible for scraping the `url, categories and title` of the blogposts and ingest them into Elasticsearch.

The searched results will appear with a title and categories, and inside the returned items, will be the href link to the url.

With this way, I can have one search ui to search for all my posts across all blogposts.

## Resources:
- https://gist.github.com/ruanbekker/9d41095043f6d38e7e7cf3674b2e5d6f
- https://gist.github.com/ruanbekker/0e08a0ee46cfcfedafdb62efbefe524a
- https://gist.github.com/ruanbekker/bcf5f00a0a8ed7b9c6a7fbac7e92f7e6
