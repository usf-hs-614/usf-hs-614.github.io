---
layout: post
title: Required packages
summary:
status: draft
hn-discussion:
comments: true
date: 2015-02-07 22:36:29
---

My last post was about the correct version of Python and using Virtualenv to
manage your package environment.  This will focus on installing the necessary
packages for the assignments in HS 614.  **Do not use any packages not listed
below as it will cause your code to not run within the test/grading
environment.**

# Installing the required packages #

If you have *pip* installed (you should), download the following file:

[hs-614-requirements.txt](/files/hs-614-requirements.txt)

Then, after activating your virtualenv, run the following command:

```
pip install -r hs-614-requirements.txt
```

This should install the correct versions of all the libraries needed for HS 614.
If this list changes for any reason, I will post the new requirements and
instructions for upgrading/migrating.

# Verifying Installed Packages for HS 614 #

To get a list of the installed packages in your virtualenv, you can run:

```
pip list
```

... which will list all packages available in your virtual environment.  To
verify your environment, compare it to:

```
backports.ssl-match-hostname (3.4.0.2)
certifi (14.05.14)
cov-core (1.15.0)
coverage (3.7.1)
execnet (1.2.0)
gnureadline (6.3.3)
ipython (2.3.1)
Jinja2 (2.7.3)
libxml2-python (2.9.1)
MarkupSafe (0.23)
matplotlib (1.4.2)
mock (1.0.1)
nose (1.3.1)
numpy (1.8.1)
pandas (0.15.2)
pip (1.5.6)
py (1.4.26)
pycairo (1.10.0)
pyparsing (2.0.3)
pyproj (1.9.3)
pytest (2.6.4)
pytest-cov (1.8.1)
pytest-xdist (1.11)
python-dateutil (2.4.0)
pytz (2014.10)
PyYAML (3.11)
pyzmq (14.4.1)
scikit-learn (0.15.2)
scipy (0.15.1)
setuptools (7.0)
six (1.9.0)
tornado (4.0.2)
wsgiref (0.1.2)
```

If you have a package that is not in the above list and you didn't install it
separately, please come see me to verify your environment.

If you have a package that is not in the above list and you installed it
separately, please remove it or be sure not to use it in any of your code.  If
you do, it will not be compatible with the grading environment and you will
receive a 0.
