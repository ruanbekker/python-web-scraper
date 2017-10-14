# python-web-scraper
Web Scraper that Scrapes my Blogs and Ingest the Data into Elasticsearch

## About

I have a couple of blogs running on ghost and a blog running on github-pages, and the idea was to have a central search ui, where this scraper will be responsible for scraping the `url, categories and title` of the blogposts and ingest them into Elasticsearch.

The searched results will appear with a title and categories, and inside the returned items, will be the href link to the url.

With this way, I can have one search ui to search for all my posts across all blogposts.
