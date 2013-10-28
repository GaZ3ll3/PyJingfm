PyJingfm
========

simple CL tool for jingfm.

=Prelude=

Install requests for python.

Install mplayer.

=Use=

Search username and pwd in main.py. Replace by your username and password in the main.py.

In terminal, type python main.py

=Issue=

Q: mplayer prompts something with  'socket...'

A: edit ~/.mplayer/config , add lirc=no. The problem caused by string format, ended by '\n' not '\r\n'.
