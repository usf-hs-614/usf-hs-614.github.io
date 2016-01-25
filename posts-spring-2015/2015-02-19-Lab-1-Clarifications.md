---
layout: post
title: Lab 1 Clarifications
summary:
status: draft
hn-discussion:
comments: true
date: 2015-02-19 08:29:44
---

I hope you've had a chance to take a look at Lab 1.  Below are some
clarifications to the assignment:

1. I did not mean to include the hba1c.csv and hba1c2.csv files so please ignore
   them.  You're welcome to take a look at them but you can (and should)
   complete the lab without every opening these files.  Doing so might confuse
   you more.

2. For the clustering related functions, your example data is in
   the ```data/cluster/``` directory

3. For the classification related functions, your example data is in the
   ```data/classify/``` directory.

4. I just noticed that I did not commit the expected outputs for the
   classification functions and will do so shortly.

5. For both the clustering and classification functions, there are two input
   files for each example, one contains the model and one contains the
   associated data.  For clustering, you have access to all of the data used
   with the model.  For classification, you only have the test data.

6. In the clustering data, you only have the features (i.e. the input data that
   is used by the model to learn).
   
7. In the classification data, you have the features and the label.  Each sample
   contains the A1C result and a 0 or 1 to indicate "not diabetic" and
   "diabetic", respectively.

8. You **do not** need to do anything related to cross validation since that
   will be covered in a different module.  **HINT:** This module and lab focus only on
   functions that you can find in sklearn.metrics

9. Please experiment and try out other functions within sklearn.metrics.  I am
   not explicitly covering most of the available functions but am happy to
   answer any questions you may have.  It's highly likely that you'll end up
   using some of the other scores at some point in your employment - we just
   don't have the time to cover them all in this course.
