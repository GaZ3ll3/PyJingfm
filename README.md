PyJingfm
========

simple CL tool for jingfm(www.jing.fm), a online music(with SNS) website. 

#History of PyJingfm#

I opened 'QTM' project around a year ago right after the jingfm was started. And I used QT4.0 + Python/C++ API to program a client for listening music(can choose from a variety of websites, like douban.fm, jing.fm, googledrive,etc.) for Linux OS(esp. Ubuntu.), and I closed that project on version 1.6, because I found out the memory leaking(or buffering) problem cannot be resolved.

So I shifted to C#/Mono under Windows and Linux respectively, but the interface was not perfect, so I quitted the approach and choose command line environment. 

After that I extract some of the code of QTM to my PyJingfm project, and luckly, it could run at that time.

Later on, Jing.fm changed the API to v2, I slightly changed the code, and now we are on the release version, since the music is in m4a format, it should be somewhat a large file(over 10MB, maybe).

#Audio#

I made the program run with mplayer, one can also use banshee, vlc,etc. It is easy to integrate into it.

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
