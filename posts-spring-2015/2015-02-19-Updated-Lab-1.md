---
layout: post
title: Updated Lab 1
summary:
status: draft
hn-discussion:
comments: true
date: 2015-02-19 10:33:02
---

If you haven't seen the clarifications, please take a look at my [last
post](/2015/02/19/Lab-1-Clarifications.html).

I have added the sample outputs for the classification functions and I've also
added a missing F-score function.

I've also added sample ROC plots.

### Additional info regarding sample data ###

The sample data that have been provided for the clustering and classification
functions have different directory structures.

As you can see, the data for the clustering are contained in individual
directories - each directory is an independent example and contains the model,
data, and expected outputs.

For the classification examples, all of the files are contained in the
same directory.  However, they are grouped by an underscore followed by a
letter.  So, all of the files ending with _a are related, _b are related, etc.

This was done purposely to get you accustomed to getting files in a variety of
formats and structures.
