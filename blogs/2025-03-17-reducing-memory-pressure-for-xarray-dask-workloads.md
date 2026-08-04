---
title: "Reducing Memory Pressure for Xarray + Dask Workloads"
url: "https://docs.coiled.io/blog/dask-array-queueing.html"
date: "2025-03-17"
author: "Patrick Hoefler"
feed_url: "https://docs.coiled.io/blog/atom.xml"
---
Mar 17, 2025 3m read Patrick Hoefler Historically, Dask scheduled thousands of data-loading tasks at once, overloading the system. The new queuing mechanism prevents this, making Xarray workloads smoother and more reliable. As of Dask 2025.1.0, Dask-backed Xarray workloads are more memory-efficient.
