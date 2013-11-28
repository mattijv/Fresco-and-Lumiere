fresco
======

A ComputerCraft program for building full color images with Glowstone Illuminators.

1. download the program to your turtle with 

  pastebin get KU8RWSQd fresco

2. find a nice picture on the internet and copy the URL
3. run fresco with

  fresco http://www.example.com/img1337.png

4. watch the turtle build you a pretty picture


You can find a more detailed guide of the setup here: http://imgur.com/a/nkguh

Options
-------

Full syntax for invoking fresco is

  fresco [-h] [-u playername] [url] [size]

- -h parameter makes the turtle build the image horizontally instead of vertically.
- With -u you can specify a player name and fresco will get the skin the player uses and builds the face part of it.
- Size is the size in blocks for the largest dimension (by default all pictures are scaled down to 128 on the largest dimension, but you can request smaller or larger). Player faces are 8 x 8 by default.
