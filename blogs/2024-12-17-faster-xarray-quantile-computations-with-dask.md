---
title: "Faster Xarray Quantile Computations with Dask"
url: "https://docs.coiled.io/blog/array-quantile.html"
date: "2024-12-17"
author: "Patrick Hoefler"
feed_url: "https://docs.coiled.io/blog/atom.xml"
---
Dec 17, 2024 2m read Patrick Hoefler There have been a number of engineering improvements to Dask Array like consistent chunksizes in Xarray rolling-constructs and improved efficiency in map_overlap . Notably, as of Dask version 2024.11.2, calculating quantiles is much faster and more reliable. Dask dashboard of the new quantile implementation, which is ~20x faster for this microbenchmark.
