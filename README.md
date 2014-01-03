PyJingfm
========

simple CL tool for jingfm.

#Prelude#

Install requests for python.

Install mplayer.

#Use#

In terminal, type python main.py and type in token to login Jing.fm.

#Issue#

Q: mplayer prompts something with  'socket...'

A: edit ~/.mplayer/config , add lirc=no. The problem caused by string format, ended by '\n' not '\r\n'.

Q: terminal says "OSError"

A: please install mplayer.
