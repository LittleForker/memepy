Installation
============

Place meme.py somewhere on your PATH. Requires PyQuery.

Usage
=====

Usage: meme.py <meme> <line1> [additional lines...]

Options:
  -h, --help            show this help message and exit
  -l, --list            list all available memes
  -s STRING, --search=STRING
                        list memes with name or option containing string
  -p MEME, --preview_url=MEME
                        Prints the URL for the meme's base image. Does not
                        generate.

ex.
$ meme.py COOL_STORY_HOUSE "nice script"


Future
======

* Package this "properly".
* Allow user config in ~/.memepy
* Automatically copy url to clipboard
* Option to send to imgur.com and get that url instead
