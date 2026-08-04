---
title: "Easy Heavyweight Serverless Functions"
url: "https://docs.coiled.io/blog/easy-serverless.html"
date: "2023-08-01"
author: "Matthew Rocklin"
feed_url: "https://docs.coiled.io/blog/atom.xml"
---
tl;dr What is the easiest way to run Python code in the cloud, especially for compute jobs? We briefly compare common options (Lambda, EC2, Fargate, Modal) and then pitch a new contender: Coiled Run. Motivation to Run Python Code in the Cloud We want to run jobs in the cloud for a few common reasons: Data proximity: Our data lives in the cloud, and we want to process it where it lives to avoid costly egress charges Speed and Scale: We have many things to process and don’t want to wait Hardware access: We want GPUs or big-memory machines Always-on Coordination: We want to respond to actions in 
