---
layout: post
title: Update to Pre-Lab
summary:
status: draft
hn-discussion:
comments: true
date: 2016-01-31 08:41:54
---

Some updates and clarifications around the Pre-Lab assignment:

This lab is difficult for everyone - it's intended to get you to start thinking
about how to apply your Python programming to solve real problems.  You are not
expected to know anything about the `pickle` module or necessarily how to
open or read files.  The key is being able to find the associated documentation
(some of which I have provided links and some of which I have not) and learn how
to read that documentation and apply it to the current problem at hand.

My comments are about 611 should not be interpreted as, "You should have learned
all of the items covered in the Pre-Lab previously."  Instead, my point is that
611 provides a slightly more gradual path to developing your Python programming
skills.

Based on some feedback and some bugs that your classmates have found, here are
some clarifications:

- Within the `test` directory, create a blank file named `__init__.py` (that's
  two underscores, init, two underscores, and .py)
- The command to run the unit tests had a typo and should be `python -m unittest
  discover` and should be run from the root of the project directory
- Within the `mshi` directory, there is a file `generate.py` that's missing. I
  have added this file to the repository so you can
  [pull](http://usf-hs-611.github.io/git-web-course/content/syncing-code/pulling.html)
  the files but since we haven't covered that, you can also download the file
  from
  [here](https://drive.google.com/a/usfca.edu/file/d/0B-5GjaosMAovUEFqVURMcGd0aDA/view?usp=drivesdk)
  and copy it into the `mshi` directory.  This should take care of the import
  errors related to `mshi.generate`
- For the F-score calculation, there are available functions that can calculate this for
  you.  However, you are being asked to implement this manually as an exercise
  in learning how to read mathematical equations and translating that to code.
