---
title: "Parallel Serverless Functions at Scale"
url: "https://docs.coiled.io/blog/parallel-coiled-functions.html"
date: "2023-09-07"
author: "James Bourbeau"
feed_url: "https://docs.coiled.io/blog/atom.xml"
---
Data Local Coiled Speed Up 500 GB NetCDF 305 mins 4.7 mins 65x The cloud offers amazing scale, but it can be difficult for Python data developers to use. This post walks through how to use Coiled Functions to run your existing code in parallel on the cloud with minimal code changes. Example: Processing Many Parquet Files on S3 In the code snippet below we load NYC Taxi Data from AWS (data lives in region us-east-1 ), process that data, and then upload the processed data back to AWS.
