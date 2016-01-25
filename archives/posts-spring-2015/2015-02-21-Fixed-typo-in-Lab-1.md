---
layout: post
title: Fixed typo in Lab 1
summary:
status: draft
hn-discussion:
comments: true
date: 2015-02-21 20:49:37
---

Someone had a question to clarify the implementation of SSB() and there is a
typo in the docstring of the function.  In addition to fixing the typo, I've
also expanded on the process.  The steps should be:

1. Calculate the mean over the entire dataset
2. Calculate the sum of squares between the mean of each cluster and the overall
   mean, then multiply by the size of the cluster (number of samples).  Repeat
   this for each cluster
3. Return the sum of all of the values from #2.
