---
title: "High Level Query Optimization in Dask"
url: "https://docs.coiled.io/blog/dask-expr-introduction.html"
date: "2023-08-04"
author: "Patrick Hoefler"
feed_url: "https://docs.coiled.io/blog/atom.xml"
---
Introduction Dask DataFrame doesn’t currently optimize your code for you (like Spark or a SQL database would). This means that users waste a lot of computation. Let’s look at a common example which looks ok at first glance, but is actually pretty inefficient.
