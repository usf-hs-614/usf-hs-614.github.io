---
layout: post
title: Update - Required packages
summary:
status: draft
hn-discussion:
comments: true
date: 2015-02-09 16:46:49
---

Thanks to Nikhil for catching an error in the hs-614-requirements.txt that I
sent out a couple days ago.  The link in the previous post has been updated and
is available again here:
http://usf-hs-614.github.io/files/hs-614-requirements.txt

If you had created the virtualenv previously, please remove it and create a new
one with the current file.

The file should look like:

```
Jinja2==2.7.3
MarkupSafe==0.23
backports.ssl-match-hostname==3.4.0.2
certifi==14.05.14
gnureadline==6.3.3
ipython==2.4.1
matplotlib==1.4.2
mock==1.0.1
nose==1.3.4
numpy==1.9.1
pyparsing==2.0.3
python-dateutil==2.4.0
pytz==2014.10
pyzmq==14.5.0
scikit-learn==0.15.2
scipy==0.15.1
six==1.9.0
tornado==4.1
wsgiref==0.1.2
```
