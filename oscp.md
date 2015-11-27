## OSCP resources

    Taken from a blog that I found at http://justpentest.blogspot.in/2015/11/myOSCPreview.html

#### Study That I did before OSCP:

I knew that we can use metasploit in the Labs and in Exam. So I started with learning metasploit.
Thou I know a bit of it as thought in C.E.H classes, but I need to know more.
There is a friend of mine named Chetan who told me to do metasploit from security tube.

#### Learning Metasploit

1. I collected all the videos of Metasploit from securitytube. Trust me guyz no one could explain metasploit and post-exploitation with metasploit better that Vivek Ramachandran.
It can be found here [http://www.securitytube.net/groups?operation=view&groupId=8](http://www.securitytube.net/groups?operation=view&groupId=8)
2. Udemy metasploit tutorial given by Mr. Hitesh Choudhary It can be found here [https://www.udemy.com/draft/93016/](https://www.udemy.com/draft/93016/)
The above course material is available for Free ;) if u know what I mean.

#### Learning Python:

1. I used security tube python scripting videos for learning python. It can be found here [http://www.securitytube-training.com/online-courses/securitytube-python-scripting-expert/index.html](http://www.securitytube-training.com/online-courses/securitytube-python-scripting-expert/index.html)
I learnt only the first and 3rd module from it. Basically python basics and socket programming is required for bufferoverflow exploitation and OSCP.

#### Learning buffer overflow:

It is the most interesting and challenging part in OSCP. This was the module that I had to work really hard for. I saw some videos on bufferoverflow. It was initially difficult to understand until I read the following site [http://www.primalsecurity.net/0x0-exploit-tutorial-buffer-overflow-vanilla-eip-overwrite-2/](http://www.primalsecurity.net/0x0-exploit-tutorial-buffer-overflow-vanilla-eip-overwrite-2/)
It explain buffer overflow in details.

Secondly I used Exploit research Megaprimer [http://www.securitytube.net/groups?operation=view&groupId=7](http://www.securitytube.net/groups?operation=view&groupId=7)
Lastly I set up my own lab and practiced buffer overflow. I wrote 2 of such buffer overflow exploit on my blog:

- [http://justpentest.blogspot.in/2015/08/echoserver-strcpy-bufferoverflow.html](http://justpentest.blogspot.in/2015/08/echoserver-strcpy-bufferoverflow.html)
- [http://justpentest.blogspot.in/2015/07/minishare1.4.1-bufferoverflow.html](http://justpentest.blogspot.in/2015/07/minishare1.4.1-bufferoverflow.html)

#### Learning port forwarding and pivoting:

I've documented it on my blog [http://justpentest.blogspot.in/2015/07/port-forwarding-and-pivoting.html](http://justpentest.blogspot.in/2015/07/port-forwarding-and-pivoting.html)

#### Practicing on vulnhub.com vm's

This is one of the most important and interesting part. Before enrolling for OSCP labs I've done ten's of Vulnerable Vm's from [https://www.vulnhub.com/](https://www.vulnhub.com/)

I would recommend the following Vm's:

1. Kioptrix series present here [https://www.vulnhub.com/series/kioptrix,8/](https://www.vulnhub.com/series/kioptrix,8/)
2. Troll series present here [https://www.vulnhub.com/series/tr0ll,49/](https://www.vulnhub.com/series/tr0ll,49/)
3. Pegasus present here [https://www.vulnhub.com/entry/pegasus-1,109/](https://www.vulnhub.com/entry/pegasus-1,109/)
4. Command Injection OS by Security tube [https://www.vulnhub.com/entry/command-injection-iso-1,81/](https://www.vulnhub.com/entry/command-injection-iso-1,81/)   (Try to do this without metasploit, as I've done here [http://justpentest.blogspot.in/2015/07/pentester-academy-command-injection-iso-basilic-exploit.html](http://justpentest.blogspot.in/2015/07/pentester-academy-command-injection-iso-basilic-exploit.html) )

The practical exposure  I've got from vulnhub.com A big thanks to the guyz who made it.

#### Post exploitation and privilege escalation:

The ultimate resource on post exploitation and privilege escalation that I've found so far can be found here [https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/Draft/Privilege%20Escalation%20%26%20Post-Exploitation.md#winpost](https://github.com/rmusser01/Infosec_Reference/blob/master/Draft/Draft/Privilege%20Escalation%20%26%20Post-Exploitation.md#winpost)

Some privilege escalation tools that I've used for Linux:

1. Linux priv check [www.securitysift.com/download/linuxprivchecker.py](www.securitysift.com/download/linuxprivchecker.py)
2. LinEnum [http://www.rebootuser.com/?p=1758#.VkG1BSvHU1I](http://www.rebootuser.com/?p=1758#.VkG1BSvHU1I)

Linux exploit suggester can be found here [https://github.com/PenturaLabs/Linux_Exploit_Suggester](https://github.com/PenturaLabs/Linux_Exploit_Suggester)
I guess 90% of the privilege escalation loopholes can be enumerated from the above tool.
Privilege escalation is an art, trust me it troubled me a lot in OSCP labs. Privilege escalation is all about how well you know Linux.

Some privilege escalation tools that I've used for Windows:

1. Windows Exploit suggester  [https://blog.gdssecurity.com/labs/2014/7/11/introducing-windows-exploit-suggester.html](https://blog.gdssecurity.com/labs/2014/7/11/introducing-windows-exploit-suggester.html)

Some good information regarding Windows privilege escalation can be found in security tube metasploit megaprimer.
