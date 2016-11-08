# What is this? #

I outsourced the python code of tvheadend to create a reusable HTSP client library for python.

# Goals #

- made some improvements regarding HTSP communication between a python HTSPClient and an TVHeadend instance
- example files

# Examples implemented #

## scripts/merge_channels.py ##

Before you start, enter your server settings (hostname, username, password) in this file.

A small demonstration of the api to create a merged channel:

- Lookup the channels by entering the name
- select the channels you want to merge
- enter the name and channel number of the new merged channel
- optional: disable old channels

Just run the code with python2.

![NBj8BqM.png](https://bitbucket.org/repo/opqn7a/images/324472350-NBj8BqM.png)