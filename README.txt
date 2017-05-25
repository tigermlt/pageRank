This project writes a simple web page crawler, computes a simple version of Google's Page Rank algorithm and visulizes the resulting network.

spider.py: read pages from the web, get the link followed and about to be followed
spider.sqlite: database that stores the link information
sprank.py: compute the page rank of the data inside spider.sqlite
spreset.py: reset the data
spjson.py: dump data from spider.sqlite into force.js
force.html: visualize page rank data
spdump.py: dump data into text format

Run:
follow the running process shown in the schematic
