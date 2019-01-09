Annotation archive
==================

This repo is mad for archiving YouTube annotations before they're gone on
January 15th. If you would like to contribute, please send a pull request!

How to get annotation data
--------------------------

1. Install [youtube-dl](http://rg3.github.io/youtube-dl/).
2. Run this command with the URL of a YouTube video, playlist, or channel:
	```
	youtube-dl --continue --retries 4 --ignore-errors --skip-download --write-annotations
	```
	This will write the annotation data into an .xml file, or if given a
	playlist or channel, do so for every video contained within.
3. Submit a pull request with the fresh data. I will ***not*** respond to
	issues.

Note that currently the files are categorized into folders based on the
original channel. It is encouraged that you do the same for ensure easy
access.
