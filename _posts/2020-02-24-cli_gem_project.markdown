---
layout: post
title:      "CLI Gem Project"
date:       2020-02-24 17:48:41 +0000
permalink:  cli_gem_project
---

I decided to create an application that would allow a user to view a list of novels, select a novel from that list and read a review of that novel. 
To visualize the structure of the application, I put together a flow diagram. 

![Imgur](https://i.imgur.com/fPTihWg.png)

I would need a user interface, a scraper class to extract the data from [The Guardian](https://www.theguardian.com/books/2015/aug/17/the-100-best-novels-written-in-english-the-full-list), and a novel class responsible for creating the objects. I started by setting up the file structure with `bundle gem best_novels`. 
I created the CLI interface first, using fake data to insure my code was functioning properly. Then I created the Novel class that would hold the attributes of a novel.

Then I created the Scraper class in lib/scraper.rb. Here I define two methods. The .scrape_novels method is responsible for scraping the index page that lists all of the novels and the .scrape_key_info method is responsible for scraping an individual novel’s page for the review.
You can check out my project here: [https://github.com/jblair87/best_novels_cli](https://github.com/jblair87/best_novels_cli)
