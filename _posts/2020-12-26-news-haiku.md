---
title: A calmer way to digest the news
layout: post
categories: [Python]
repo: "https://github.com/MarieRoald/news-haiku"
ingress: >
    For the past year, the news have made us more and more anxious, and we have caught ourselves *doomscrolling* a bit too much. Therefore, we decided to change how we consume news, and do it through haikus instead of headlines. We take the RSS feed from NRK, the governmental broad casting service of Norway, and extract haikus from the newspage descriptions. You can read a random haiku <a href="http://nyhetshaiku.visualizards.com">here</a> and read the source code by cloning the <a href="https://github.com/MarieRoald/news-haiku">project repo</a>.
---

<a href="http://nyhetshaiku.visualizards.com"><img src="/assets/images/20-12-26-news-haiku/haiku.png" width="800px" /></a>

We decided to give ourselves one day to make a haiku detection algorithm and figure out how to serve a webpage with Python. To analyse the text and detect haikus, we used [spaCy](https://spacy.io/). This way, could avoid to split the noun chunks, which drastically increased the quality of the haikus. Then, we needed a way to count syllables, which we did by counting the number of vowels, which we thought worked well to count syllables in Norwegian words.

To serve the webpage, we needed two concurrent processes: A simple flask server to generate the HTML, and a background process to fetch the news and extract haikus. We stored the extracted haikus in a JSON file. For each web request, this JSON file is loaded and a random haiku is selected.