### Level 9

```
gurukiran@ch3ster:~$ ssh bandit9@bandit.labs.overthewire.org -p 2220
This is a OverTheWire game server. More information on http://www.overthewire.org/wargames

bandit9@bandit.labs.overthewire.org's password: 
Linux bandit.otw.local 5.4.8 x86_64 GNU/Linux

bandit9@bandit:~$ ls -a
.  ..  .bash_logout  .bashrc  data.txt  .profile
bandit9@bandit:~$ strings data.txt | egrep -o '={2,}(.*)'
========== the*2i"4
========== password
========== is
========== truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk
```
