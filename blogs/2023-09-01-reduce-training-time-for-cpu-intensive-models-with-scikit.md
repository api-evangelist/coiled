---
title: "Reduce training time for CPU intensive models with scikit-learn and Coiled Functions"
url: "https://docs.coiled.io/blog/coiled-run-scikit-learn.html"
date: "2023-09-01"
author: "Patrick Hoefler"
feed_url: "https://docs.coiled.io/blog/atom.xml"
---
Sep 1, 2023 3m read Patrick Hoefler You can use Coiled Run and Coiled Functions for easily running scripts and functions on a VM in the cloud. In this post we’ll use Coiled Functions to train a RandomForestClassifer on a cloud-hosted machine that has enough cores to speed up our training process. The model parallelizes very well, which means that training time on my local machine is only bound by the number of cores available.
