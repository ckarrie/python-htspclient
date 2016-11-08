# What is this? #

I outsourced the python code of tvheadend to create a reusable HTSP client library for python.

# Goals #

- made some improvements regarding HTSP communication between a python HTSPClient and an TVHeadend instance
- example files

# Examples implemented #

## scripts/merge_channels.py ##

A small demonstration of the api to create a merged channel:

- Lookup the channels by entering the name
- select the channels you want to merge
- enter the name and channel number of the new merged channel
- optional: disable old channels

Just run the code with python2.
