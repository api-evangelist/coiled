---
title: "Fine Performance Metrics and Spans"
url: "https://docs.coiled.io/blog/fine-performance-metrics.html"
date: "2023-08-23"
author: "Guido Imperiale"
feed_url: "https://docs.coiled.io/blog/atom.xml"
---
While it’s trivial to measure the end-to-end runtime of a Dask workload, the next logical step - breaking down this time to understand if it could be faster - has historically been a much more arduous task that required a lot of intuition and legwork, for novice and expert users alike. We wanted to change that. There are a few questions that someone who wants to optimize the performance of their Dask workflow typically asks: How much time am I losing to GIL contention ?
